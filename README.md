# update-and-refresh-scoop-bat

このリポジトリには、Windows用コマンドラインインストーラであるScoopの更新、クリーンアップ、およびキャッシュ管理を自動化するバッチファイルが含まれています。

## 説明

`update_and_refresh_scoop.bat` バッチファイルは、以下のタスクを実行します:

1. **管理者権限の要求:** スクリプトが管理者権限で実行されることを確認します。すでに管理者として実行されていない場合は、権限の昇格を求めます。

2. **Scoopの更新:** Scoop自体を更新するために、Scoopの組み込みコマンド`update`を使用します。

3. **インストール済みアプリの更新:** Scoopで管理されているすべてのインストール済みアプリケーションを更新します。

4. **古いバージョンとインストーラのクリーンアップ:** ディスク容量を確保するために、古いバージョンとインストーラを削除します。

5. **Scoopキャッシュのクリーンアップ:** ディスク容量を回復し、パフォーマンスを向上させるために、Scoopのキャッシュをクリアします。

6. **完了メッセージ:** 更新、クリーンアップ、キャッシュ管理のプロセスが完了したことを示すメッセージを表示し、ウィンドウが閉じる前にユーザーの入力を待ちます。

## 使用方法

1. **バッチファイルをダウンロード:**
   - このリポジトリから `update_and_refresh_scoop.bat` をダウンロードします。

2. **バッチファイルを実行:**
   - `update_and_refresh_scoop.bat` を左クリックで実行します。

3. **プロンプトに従う:**
   - バッチファイルが管理者権限で実行されていない場合は、管理者権限の昇格を求められます。
   - スクリプトはその後、Scoopの更新、インストール済みアプリの更新、古いバージョンとインストーラのクリーンアップ、Scoopキャッシュのクリーンアップを順次実行します。

4. **完了:**
   - すべてのタスクが完了すると、スクリプトは完了メッセージを表示し、コマンドウィンドウが閉じる前にキー入力を待ちます。

## 注意事項

- **管理者権限:** これらの操作を実行するには管理者権限が必要です。必要な権限を持っていることを確認してください。
- **Scoopのインストール:** このスクリプトを実行する前に、システムにScoopがインストールされていることを確認してください。

## ライセンス

このプロジェクトはMITライセンスの下でライセンスされています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## 貢献

スクリプトの改善や新機能の追加については、問題の提出やプルリクエストを歓迎します。

## コンタクト

質問やサポートについては、このリポジトリに問題を投稿するか、リポジトリの所有者に連絡してください。

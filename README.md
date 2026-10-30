# 🦴 身体観察室 mini — PWA試用版 v0.4

朝・夜の身体観察を記録する個人用Webアプリです。

## GitHub Pagesで公開する
1. このフォルダの中身（`index.html`, `manifest.webmanifest`, `service-worker.js`, `icons/`）をリポジトリの**一番上の階層**にアップロードします。ZIPファイルそのものはアップロードしません。
2. GitHubの `Settings` → `Pages` → `Build and deployment` → `Deploy from a branch` を選び、Branch `main` / `/(root)` → `Save`。
3. 数分後に表示されるURLをiPhoneのSafariで開きます。
4. Safariの共有メニュー → ホーム画面に追加 → Webアプリとして開く（表示される場合）で追加します。

## 大切な注意
- GitHub Pagesは公開サイトです。**健康記録や個人情報をリポジトリにアップロードしないでください**。
- 記録は端末・ブラウザごとのローカルストレージに保存され、PCとiPhoneで自動同期されません。
- 定期的にアプリ内の「バックアップ（JSON）」からデータを保存してください。
- WindowsでローカルHTMLを開いて入力した記録は、GitHub Pages版には自動で移りません。JSONバックアップを介して復元できます。
- iPhoneのホーム画面追加版とSafariの通常タブでは、保存領域が異なる場合があります。必ず実際に保存・再起動して確認してください。
- サイトのURLを知っている人はアプリの画面にアクセスできます（記録そのものがGitHubに公開されるわけではありません）。
- Notion連携、アカウント同期、睡眠アプリ連携は未実装です。

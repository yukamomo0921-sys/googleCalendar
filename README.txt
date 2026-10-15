くらしメンテ v34

変更点：NFC URLを開いた直後の操作を、Firebaseの初回データ読み込みが完了してから実行するように変更。これにより、初期同期とNFC操作が競合する可能性を減らします。タイマー・進行中工程は端末ローカル管理、習慣設定・NFCタグ・完了履歴はクラウド同期の方針を維持します。

GitHub Pagesのリポジトリ直下で index.html / service-worker.js / manifest.webmanifest / icon-192.png / icon-512.png を置き換えてください。
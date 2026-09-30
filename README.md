# お金カレンダー

iPhoneのホーム画面に追加して使うWebアプリ（PWA）。データはiPhone本体に保存。

## ファイル
- index.html … アプリ本体
- manifest.webmanifest / sw.js … ホーム画面アプリ化・オフライン対応
- icons/ … アイコン

## 公開（GitHub Pages）
1. GitHubで新しいリポジトリを作成（例: okane-calendar）
2. 「Add file → Upload files」でこのフォルダの中身（index.html, manifest.webmanifest, sw.js, iconsフォルダ）をアップロード
3. Settings → Pages → Branch を「main / (root)」にして Save
4. 数分後に https://<ユーザー名>.github.io/okane-calendar/ で開ける

## iPhoneに入れる
Safariで上のURLを開く → 共有ボタン → 「ホーム画面に追加」

## 更新するとき
ファイルを上書きアップロードし、sw.js の VERSION を変更（例: v1 → v2）。

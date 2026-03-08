# 将棋 - Shogi Game

ブラウザで遊べる将棋ゲームです。ビルド不要で、HTMLファイルを開くだけで動作します。

![Shogi](https://img.shields.io/badge/Game-将棋-brown)
![License](https://img.shields.io/badge/License-MIT-blue)

## 遊び方

1. このリポジトリをクローンまたはダウンロード
2. `index.html` をブラウザで開く（またはVSCodeのLive Serverで起動）
3. 先手（下側）から交互にクリックで対局

## 機能

- **二人対戦** — 先手・後手の交互プレイ
- **駒の移動** — クリックで駒を選択し、緑のマークが付いた合法手に移動
- **成り** — 敵陣に入る/出るとき成り・不成を選択可能
- **持ち駒** — 取った駒を盤面に打てる
- **王手・詰み判定** — 王手時に警告表示、詰みで対局終了
- **ルール** — 二歩禁止、打ち歩詰め禁止、行き所のない駒の制限
- **棋譜表示** — 対局の手順を記録
- **レスポンシブ対応** — スマートフォンでも遊べる

## ファイル構成

```
shogi-game/
├── index.html   … メインHTML
├── style.css    … スタイルシート
├── game.js      … ゲームロジック
└── README.md    … このファイル
```

## 開発

### VSCode + Live Server で開発する場合

1. VSCodeで `shogi-game` フォルダを開く
2. 拡張機能「Live Server」をインストール
3. `index.html` を右クリック → 「Open with Live Server」
4. ブラウザが自動で開き、ファイル保存時に自動リロードされます

### GitHub Pages で公開する場合

1. GitHubにリポジトリを作成してプッシュ
2. Settings → Pages → Source を「main」ブランチに設定
3. `https://<ユーザー名>.github.io/<リポジトリ名>/` でアクセス可能

## ライセンス

MIT License
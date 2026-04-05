# 浄徳寺サイト v3

GitHub Pages でそのまま公開できる静的サイトです。

## ファイル構成

```text
index.html            # 文章・構成
404.html              # 404ページ
styles.css            # デザイン
script.js             # モバイルメニューなどの軽い動作
.nojekyll             # GitHub Pages用
favicon.svg           # アイコン
images/
  entrance-hero.jpg   # メイン画像
  entrance-detail.jpg # サブ画像
  entrance-square.jpg # 予備画像
  ogp.jpg             # SNS共有画像
GitHub公開手順.md      # 初心者向け公開手順
README.md
```

## どのファイルを編集すればよいか

- 文章を変えたい → `index.html`
- 色や余白を変えたい → `styles.css`
- スマホメニューなどを変えたい → `script.js`
- 写真を差し替えたい → `images` フォルダ

## まずやること

1. このフォルダ一式を GitHub リポジトリにアップロード
2. `Settings > Pages` で `main / root` を公開元に設定
3. 数分待って公開URLを確認

詳しくは `GitHub公開手順.md` を見てください。

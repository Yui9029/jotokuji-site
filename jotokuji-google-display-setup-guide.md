# 浄徳寺HP Google表示改善 導入ガイド

## 今回の方針
- Webページ本文やレイアウトには手を加えない
- `index.html` の `<head>` だけを修正する
- 検索結果まわりの情報を整える

## 使うファイル
- `jotokuji-google-display-head-snippet.html`

## 反映手順
1. GitHubで浄徳寺HPのリポジトリを開く
2. `index.html` を開く
3. `<head>` と `</head>` の間を探す
4. 既存の `<title>` がある場合は、今回のものに置き換える
5. 既存の `<meta name="description">` がある場合は、今回のものに置き換える
6. `canonical` / `og:*` / `application/ld+json` が無ければ追加する
7. 保存してコミットする
8. GitHub Pages の反映を待つ

## 貼り付けイメージ
```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- ここにスニペットを貼る -->

</head>
```

## 注意点
- `<title>` は1ページに1つだけにする
- `<meta name="description">` も基本的に1つにする
- ページ本文の見た目は通常変わらない
- ブラウザのタブ名は変わる可能性がある
- Google検索結果への反映には時間がかかることがある

## 今回は入れていないもの
- favicon の新規追加
- OGP画像の追加
- 本文見出しの変更
- URLの変更

## 次にやると良いこと
- 反映後、Google Search Console でトップページの再クロール依頼を行う
- 将来的には独自ドメイン化を検討する

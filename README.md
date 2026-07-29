# CHIOMA Wholesale LP

マンツーマンサロンの美容師オーナー向けLPです。

## Files

- `index.html`: LP本体
- `assets/`: LPで使用している画像
- `.nojekyll`: GitHub Pagesでそのまま静的HTMLとして公開するためのファイル

## GitHub Pages

1. GitHubで新規リポジトリを作成
2. このフォルダの中身をアップロード
3. Repository Settings > Pages を開く
4. Source を `Deploy from a branch` にする
5. Branch を `main`、folder を `/root` にする
6. 表示されたURLで公開確認

## Microsoft Clarity

Clarityの計測IDを取得したら、Clarity管理画面に表示される公式トラッキングコードを `index.html` の `<head>` 内に貼り付けてください。

貼り付け位置はこのコメントの直後がわかりやすいです。

```html
<!-- Microsoft Clarity: paste the official tracking script here before publishing. See README.md. -->
```

`clarity.ms/tag/xxxxx` の `xxxxx` が計測IDです。

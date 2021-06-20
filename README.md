# 5/30

"CLI"を実行すると"local api"にディレクトリ名とファイル名が渡る

# 6/1

buildしたReactアプリをロードしたい場合と、開発時に起動するようにnpm run startでロードしたい場合がある

```js
// そのファイルが無ければ空の配列として保存
// しかし、↑では無くユーザーに親切なデフォルトの配列をあとで作る
if (err.code === 'ENOENT') {
  await fs.writeFile(fullPath, '[]', 'utf-8');
  res.send([]);
```

# 6/2

キー入力の度にAPIを叩くのはよろしく無いので、どのようにすべきかを紹介する

# 疑問

middlewareって何だっけ？
persist-middlewareteの役目は何？
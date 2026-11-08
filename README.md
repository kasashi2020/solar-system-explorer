# Solar System Explorer

太陽系の惑星・主要衛星の位置と月の満ち欠けを観察する、静的Webアプリです。

## ローカルで試す
`index.html` をブラウザで開いてください。外部ライブラリやサーバーは不要です。

## GitHub Pagesで無料公開する手順
1. https://github.com/ にアクセスし、無料アカウントを作成します。
2. ログイン後、右上の `+` → `New repository` を選びます。
3. Repository name に `solar-system-explorer` と入力します。
4. `Public` を選択し、`Create repository` を押します。
5. `Add file` → `Upload files` を選び、このZIPを展開したフォルダー内の `index.html` と `README.md` をアップロードします。
6. `Commit changes` を押します。
7. リポジトリの `Settings` → `Pages` を開きます。
8. `Build and deployment` の `Source` を `Deploy from a branch` にします。
9. Branch を `main`、folder を `/(root)` にして `Save` を押します。
10. 数分後、同じ Pages 画面に表示される公開URLを開きます。通常は `https://あなたのユーザー名.github.io/solar-system-explorer/` の形式です。

## 更新
修正した `index.html` を同じリポジトリへ再アップロードして `Commit changes` すると更新されます。

## 注意
このアプリは教育・観察用の簡易シミュレーターです。惑星の位置は簡易円軌道、衛星の位置は公転周期による近似です。精密な天体暦や航法・観測計画には使用しないでください。

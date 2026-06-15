# 岩永瑞貴｜現場価値の文章整理 LP

GitHub Pagesでそのまま公開できる静的LPです。

## ファイル構成

```text
.
├── index.html
├── .nojekyll
└── README.md
```

- `index.html`: 公開されるLP本体です。GitHub Pagesの公開元ルートに置きます。
- `.nojekyll`: Jekyll処理を無効化するための空ファイルです。
- `README.md`: この手順書です。

元Zipに含まれていた `screen.png` と `DESIGN.md` は制作時の参照資料のため、公開用パッケージからは外しています。

## 公開前に確認すること

1. `index.html` 内の `mailto:mizuki.iwanaga@example.com` を実際の問い合わせ先メールアドレスに変更します。
2. ブラウザで `index.html` を開き、表示内容とリンク先を確認します。
3. 公開してよい情報だけが含まれているか確認します。

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作成します。
   - プロジェクト用URLでよければ、任意のリポジトリ名で問題ありません。
   - `https://ユーザー名.github.io/` で公開したい場合は、リポジトリ名を `ユーザー名.github.io` にします。
2. このフォルダ内の `index.html`、`.nojekyll`、`README.md` をリポジトリのルートにアップロードします。
3. GitHubのリポジトリ画面で `Settings` を開きます。
4. 左メニューの `Pages` を開きます。
5. `Build and deployment` の `Source` で `Deploy from a branch` を選びます。
6. `Branch` で `main`、フォルダで `/ (root)` を選び、`Save` します。
7. 数分待ってから、`Settings > Pages` に表示される公開URLを開きます。

公開URLの例:

```text
https://ユーザー名.github.io/リポジトリ名/
```

ユーザーサイトとして作った場合:

```text
https://ユーザー名.github.io/
```

## 更新する場合

1. ローカルで `index.html` を編集します。
2. GitHubのリポジトリに上書きアップロード、またはGitでcommit/pushします。
3. GitHub Pagesの反映を待って公開URLを確認します。

変更がすぐ反映されない場合は、数分待ってからブラウザを再読み込みしてください。

## 参考

- [GitHub Docs: Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [GitHub Docs: Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

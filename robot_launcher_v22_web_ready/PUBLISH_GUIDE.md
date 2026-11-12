# GitHub Pagesでの無料公開手順（一般的な手順）

1. このZIPを解凍し、`index.html` が最上位にあることを確認。
2. GitHubで新しい**公開リポジトリ**を作る。秘密情報・APIキー等を絶対に含めない。
3. 公開リポジトリのルートにZIP内のファイルをアップロードしコミット。
4. リポジトリの **Settings → Pages → Build and deployment → Source: Deploy from a branch** を選ぶ。ブランチ `main`、フォルダ `/(root)` を指定して保存。
5. Pages に表示された公開URLへアクセスし、PCとスマホで表示・操作を再確認。
6. 本番ドメインとホスティングのログ方針を調べ、`privacy.html` の未記入箇所を埋めた版をコミット。
7. 同一ドメインでの進行保存・再読込を確認。ゲームを公開告知するのは、この手順と実機確認を終えてから。

## 重要
- 本ファイルを作成した時点ではGitHubへのアップロードはしていません。
- Pagesサイトは外部からアクセス可能になるため、非公開の画像や個人情報・APIキーは一切含めないでください。
- ブラウザで直接HTMLを開く場合と、httpsのWebサイトで動かす場合では保存領域などが異なります。
- iPhoneの場合、ファイルプレビューではゲームが描画されないことがあります。実際のhttps公開URLをSafariで開いて確認してください。

GitHub公式: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
設定: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

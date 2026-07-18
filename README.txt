舞台『光～HIKARI～』前日譚 公開版 Ver.1.0

【GitHub Pagesでの公開】
1. このZIPを展開します。
2. GitHubで新しいPublicリポジトリを作成します。
3. 展開した中身（index.html、assets、episodes等）をリポジトリ直下へアップロードします。
4. Settings → Pages → Build and deployment → Deploy from a branch を選択します。
5. Branchを main、フォルダを /(root) にしてSaveします。

【公開後に推奨する作業】
・公開URLを舞台ランディングページやSNSプロフィールへ追加してください。
・SNS画像を確実に表示させるには、各HTMLの og:image を公開後の絶対URLへ変更すると最も確実です。
  例：https://ユーザー名.github.io/リポジトリ名/assets/og-cover.jpg

【構成】
index.html：トップページ
episodes/：各話本文
assets/：画像、CSS、favicon、OGP画像
404.html：Not Foundページ
.nojekyll：GitHub Pages用
robots.txt：検索エンジン用

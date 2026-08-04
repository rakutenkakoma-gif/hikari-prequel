舞台『光～HIKARI～』前日譚 BGM対応・修正版

修正内容
・EPISODE 01〜06、EPISODE Xの全ページにBGMプレイヤーを追加
・各BGM名を表示
・全話で同じ episode.css と共通レイアウトを使用
・EPISODE Xの独自インラインCSSを廃止し、共通テンプレートへ統一
・音源は preload="none" とし、再生操作後に読み込む仕様

GitHubへの反映
1. episodes/ 内の7ファイルをリポジトリの episodes/ へ上書き
2. assets/episode.css をリポジトリの assets/episode.css へ上書き
3. assets/music/ に以下のMP3が存在することを確認
   episode-01.mp3
   episode-02.mp3
   episode-03.mp3
   episode-04.mp3
   episode-05.mp3
   episode-06.mp3
   episode-x.mp3
4. Commit changes
5. Actions または Settings > Pages でデプロイ完了を確認
6. 公開ページを Ctrl+F5 で再読み込み

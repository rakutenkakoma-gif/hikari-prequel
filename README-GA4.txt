舞台『光～HIKARI～』前日譚 GA4対応版 v1.1

修正元
・Google Drive「『光』前日譚公開ページ」フォルダの現行公開版
・取得日: 2026-07-29

変更内容
・全8 HTMLに GA4 測定ID G-8DNPQG0FT4 を追加
・舞台LPリンクのクリックを stage_lp_click として計測
・各話BGMの初回再生を bgm_play として計測

変更していないもの
・本文
・デザイン/CSS
・BGMプレイヤーと音源パス
・画像パス
・前後ページリンク
・既存JavaScript

GitHubへの反映
1. index.html をリポジトリ直下へ上書き
2. episodes/ 内の7ファイルをリポジトリの episodes/ へ上書き
3. Commit changes
4. Actions または Settings > Pages でデプロイ完了を確認
5. 公開ページを開き、GA4「リアルタイム」で page_view を確認
6. 舞台LPボタンを押して stage_lp_click、BGMを再生して bgm_play を確認

注意
・assets 以下は変更していません。アップロード不要です。

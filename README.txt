特定社労士 過去問シアター（参照方式）

■ フォルダ構成（すべて同じ階層に置く）
  index.html                       … LP本体（メディアは相対パスで参照）
  15〜21kai_shiken_ultra_small.mp4 … 解説動画（第15・17〜21回）
  15〜21kai_shiken_small.m4a       … 音声解説（第15・17〜21回）
  15〜21kai_poster.jpg             … 動画のサムネイル

■ 回を追加・修正するとき
  index.html の <script> 冒頭にある CASES 配列に1件追加（または編集）し、
  同じ命名規則のファイル（例：16kai_shiken_ultra_small.mp4 / 16kai_shiken_small.m4a）を置いてください。
  ファイルが無い動画枠には「ファイル未配置」の案内が出ます。
  サブフォルダにメディアをまとめたい場合は MEDIA_BASE を "media/" などに変更します。

■ GitHub Pages
  このフォルダの中身をリポジトリ直下に置き、Pages を有効にすれば公開できます（各ファイル100MB未満）。

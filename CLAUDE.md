# Lemo-Opuscar 映像制作ワークスペース

このリポジトリは Lemo-Opuscar プラグイン(lemolab マーケットプレイス)で短編映像を作るための専用作業場所。
`.claude/settings.json` でプラグインを有効化しているので、このフォルダで Claude Code を開くと自動で使える。

## 運用ルール
- 1本の映像 = `films/<name>/`(英小文字・数字・ハイフン)。スキルの「project folder」はここに作る。
- ライブラリ本体は `~/lemo-opuscar` に自動取得される(このリポジトリには含めない)。
- 完成動画(mp4 等)はコミットしない。`TREATMENT.md`・`build.sh`・ソースだけ残す。
- 品質のため effort は high 推奨(`/effort high`)。1本あたり 30〜60 分・トークン消費大。長くなりそうなら映像ごとに別チャットに分ける。
- 字幕・テロップ・付随資料(PDF/PPT 等)のフォントは "Meiryo UI" を優先(スタイル指定と衝突する場合は確認する)。

## ライセンス注意
- 作った映像は自分のもの(商用可・クレジット不要)。
- ただし STYLE.md やガイド類(Markdown)は CC BY-NC 4.0。改変版を有料 note 等で配布・販売しない。
- 自作ナレーションは Kokoro(既定)を使う。Edge TTS のデモ音声は流用不可。

## 必要ツール
- Node 20+ / Python 3.11+ / ffmpeg 7+(Ubuntu 24.04 標準の ffmpeg 6.1 は古いので静的ビルドを使う)

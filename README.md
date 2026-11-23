# lemo-opuscar-studio

[Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar)(99種のコード生成映像スタイル)を使うための専用リポジトリ。

## 使い方
1. このリポジトリを開いて Claude Code を起動(初回はマーケットプレイスの信頼確認が出るので許可)
2. `/effort high`
3. 例: 「watercolor スタイルで、日本株の1週間を振り返る45秒の映像を作って」

## 他の環境で使う
- PC の CLI: このリポジトリを clone して開くだけ。または `claude plugin marketplace add lemomo-ai/lemo-opuscar` → `claude plugin install lemo-opuscar@lemolab`
- 他リポジトリと組み合わせる: そのリポジトリの `.claude/settings.json` に、ここと同じ `extraKnownMarketplaces` / `enabledPlugins` を追記

# 朝5分で読むサイバーセキュリティNews

サイバーセキュリティ業界の動向（攻撃・被害、脆弱性、日本の事例、AI×セキュリティ、政策・規制、業界・企業）を、毎朝5分で読める日本語ダイジェストにまとめるスマホ向けアプリです。TomTom TOWNS の一員です。

- 公開URL: https://pecpec37-gift.github.io/Cyber-News/
- 毎朝 6:00ごろ（日本時間）、Claude の定期タスクが新しい号を追加します。

## データの置き場所

- `data/index.json` … 号の一覧（新しい順、最大30号）
- `data/editions/YYYY-MM-DD.json` … 各号の本文

`items[].cat` は `attack` `vuln` `japan` `ai` `policy` `industry`、`items[].level` は `high`（緊急）`mid`（注意）`low`（参考）のいずれかです。`items[].action` は読者がやるべきこと（なければ空文字）。

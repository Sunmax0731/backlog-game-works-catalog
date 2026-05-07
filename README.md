# backlog-game-works-catalog

積みゲーム・作品カタログ は、積みゲーム、視聴予定、クリア状況、次に遊ぶ理由を管理する個人カタログです。

## Closed Alpha Scope

- Rank: 26
- Tier / Score: P1 / 63
- Domain / Idea No: AndroidApp / 13
- 主な公開先: Google Play
- GitHub: https://github.com/Sunmax0731/backlog-game-works-catalog
- Prerelease: https://github.com/Sunmax0731/backlog-game-works-catalog/releases/tag/v0.1.0-alpha.1

## 実装概要

- `src/core`: 製品プロファイルと代表シナリオ評価
- `src/validators`: 期待結果検証
- `src/report`: 検証レポート生成
- `src/review-model`: レビューゲートと責務モデル
- `src/cli`: `samples/representative-suite.json` の自動検証

## 代表データ

`samples/representative-suite.json` は `happy-path`、`missing-required`、`warning`、`mixed-batch` を含みます。

## 検証

```powershell
cd D:\AI\AndroidApp\backlog-game-works-catalog
cmd.exe /d /s /c npm test
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` を参照してください。

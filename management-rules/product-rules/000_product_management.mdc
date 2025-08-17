---
description: プロダクトマネジメントをコントロールするルール
alwaysApply: false
---

# プロダクトマネジメントルール

読み込んだときに「プロダクト！」と叫んでください

# ドキュメント構造

```
プロダクトリリースドキュメント
    └──PRD（プロダクト/機能群単位）
        └── EPIC（ユーザージャーニー/大きな体験単位）
            └── STORY（具体的なユーザー価値単位）
```

# ルールブック

タスクに合わせて、読み込むべきルールファイルを必ず追加参照する

```yaml
プロダクトリリースドキュメント:
  overview: 中期プロダクト戦略
  ownership: PdM
  deliverables:
    - リリース要件書
    - 判定基準
    - 戦略ロードマップ
    - 計測マネジメント
    - リリースPRDリスト
  reference:
    rule-files:
      - .cursor/rules/management-rules/product-rules/001_product_release_document.mdc

PRD（プロダクト要求仕様書）:
  overview: 開発要求定義
  ownership: PdM
  deliverables:
    - リリース要件書
    - 判定基準
  reference:
    rule-files:
      - .cursor/rules/management-rules/product-rules/001_product_release_document.mdc
      - .cursor/rules/management-rules/product-rules/002_product_requirement_document.mdc

EPIC（エピック）:
  overview: ユーザー体験の大きな塊
  ownership: PdM
  変更頻度: PRD内でスコープ調整可
  deliverables:
    - 体験フロー
    - 画面遷移図
    - 要件定義
  reference:
    rule-files:
      - .cursor/rules/management-rules/product-rules/002_product_requirement_document.mdc
      - .cursor/rules/management-rules/product-rules/003_product_epic_document.mdc

STORY（ユーザーストーリー）:
  overview: 具体的なユーザー価値
  ownership: Dev
  変更頻度: スプリント計画で調整、リファイメントで修正
  deliverables:
    - 要件定義
    - 受け入れ条件
  reference:
    rule-files:
      - .cursor/rules/management-rules/product-rules/002_product_requirement_document.mdc
      - .cursor/rules/management-rules/product-rules/003_product_epic_document.mdc
      - .cursor/rules/management-rules/product-rules/004_product_story_document.mdc

```

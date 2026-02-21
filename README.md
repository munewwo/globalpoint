# 合同会社グローバルポイント ドキュメント管理（顧客対応支援）

本リポジトリは、グローバルポイント社の運営を支援するために、**対外的に提示する（または提示の根拠となる）文書**と、**顧客対応に必要な運用情報**を蓄積・管理し、最新情報で参照できる状態を維持することを目的とします。

## まずここ（クイックリンク）

- **リリースノート一覧（対外発表の時系列）**: [docs/release/README.md](docs/release/README.md)
- **規約・ポリシー一覧**: [docs/globalpoint/terms/README.md](docs/globalpoint/terms/README.md)
- **POKERWEB 利用規約（本体）**: [docs/globalpoint/terms/pokerweb-terms.md](docs/globalpoint/terms/pokerweb-terms.md)
- **ウェブコイン特約（別紙1）**: [docs/globalpoint/terms/pokerweb-webcoin-appendix.md](docs/globalpoint/terms/pokerweb-webcoin-appendix.md)
- **GameID 利用規約**: [docs/globalpoint/terms/gameid-terms.md](docs/globalpoint/terms/gameid-terms.md)
- **選手契約（業務委託契約）**: [docs/globalpoint/terms/player-agreement.md](docs/globalpoint/terms/player-agreement.md)
- **当社プライバシーポリシー（共通）**: [docs/globalpoint/terms/privacy.md](docs/globalpoint/terms/privacy.md)
- **反社会的勢力の排除に関する規程（共通）**: [docs/globalpoint/terms/antisocial.md](docs/globalpoint/terms/antisocial.md)
- **ウェブコイン（要約・案内）**: [docs/pokerweb/pokerweb-webcoin.md](docs/pokerweb/pokerweb-webcoin.md)
- **用語集（表記・定義の統一）**: [docs/terms/README.md](docs/terms/README.md)
- **LINE QA 運用**: [docs/support/line-qa/README.md](docs/support/line-qa/README.md)
- **法人情報（集約）**: [docs/globalpoint-corporate.md](docs/globalpoint-corporate.md)

## ドキュメントの位置づけ（何を「正」として参照するか）

同じテーマでも「要約」や「案内」と「規約（正文）」が混在すると、参照先がブレやすくなります。顧客対応では、次の位置づけを基準に参照します。

| 種別 | 位置づけ | 主な保管先 |
|------|----------|------------|
| リリースノート | 対外発表の一次ソース（いつ・何を発表したか） | `docs/release/`（入口: [docs/release/README.md](docs/release/README.md)） |
| 規約・ポリシー（正文） | 利用規約・特約・プライバシーポリシー・反社排除規程等 | `docs/globalpoint/terms/`（入口: [README.md](docs/globalpoint/terms/README.md)） |
| 説明資料・要約 | 概要把握・案内用（正文ではない） | `docs/pokerweb/pokerweb-service.md` / `docs/pokerweb/pokerweb-webcoin.md` / `docs/pokerweb/pokerweb-pricing.md` |
| 顧客対応運用（LINE QA） | 返信品質・レビュー・アーカイブ運用 | `docs/support/line-qa/` |
| 用語集 | 文書間の表記ゆれ・未定義語の解消（運用ルール） | `docs/terms/README.md` |
| 法人情報 | 会社情報・関連サービスの集約 | `docs/globalpoint-corporate.md` |

## 顧客対応の参照導線（よくある目的別）

- **過去の発表内容を確認したい**: [docs/release/README.md](docs/release/README.md)
- **契約条件（正文）を提示したい**: [docs/globalpoint/terms/README.md](docs/globalpoint/terms/README.md) から該当規約へ
- **ウェブコインの運用条件を確認したい**: `docs/globalpoint/terms/pokerweb-webcoin-appendix.md`（特約）を優先
- **まず概要を把握したい**: `docs/pokerweb/pokerweb-service.md` / `docs/pokerweb/pokerweb-webcoin.md`
- **返信の型（短く、重要点中心）で回答したい**: `docs/support/line-qa/README.md`
- **表記・定義で迷った**: `docs/terms/README.md`

## 文書運用ルール（迷いを減らすための共通ルール）

- **語尾・文体**: 原則「です・ます」で統一（原文引用は除く）
- **用語**: 新しい用語・表記ゆれを見つけたら、まず [docs/terms/README.md](docs/terms/README.md) に追記してから各文書へ反映
- **参照先**: ルールの根拠は、可能な限り「規約（本体）」「特約（個別規程）」「リリースノート」のいずれかに寄せる
- **「当社」等の定義**: 規約・ポリシー等は文書内定義が最優先（例: 第2条（定義））

## フォルダ構成

| パス | 内容 |
|------|------|
| `docs/release/` | 対外発表したリリースノート（入口: [docs/release/README.md](docs/release/README.md)） |
| `docs/globalpoint/terms/` | 規約・特約・プライバシーポリシー・反社排除規程等の正文（入口: [README.md](docs/globalpoint/terms/README.md)） |
| `docs/pokerweb/` | POKERWEB の説明資料・料金・ライセンス契約等 |
| `docs/support/` | 顧客対応の運用（LINE QA 等） |
| `docs/terms/` | 用語集（入口: [docs/terms/README.md](docs/terms/README.md)） |

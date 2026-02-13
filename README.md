# 合同会社グローバルポイント ドキュメント管理（顧客対応支援）

本リポジトリは、グローバルポイント社の運営を支援するために、**対外的に提示する（または提示の根拠となる）文書**と、**顧客対応に必要な運用情報**を蓄積・管理し、最新情報で参照できる状態を維持することを目的とします。

## まずここ（クイックリンク）

- **リリースノート一覧（対外発表の時系列）**: [docs/release/README.md](docs/release/README.md)
- **POKERWEB 利用規約（本体）**: [docs/pokerweb/pokerweb-terms.md](docs/pokerweb/pokerweb-terms.md)
- **POKERWEB プライバシーポリシー**: [docs/pokerweb/pokerweb-privacy.md](docs/pokerweb/pokerweb-privacy.md)
- **ウェブコイン運用規程（別紙1 / 優先）**: [docs/pokerweb/pokerweb-webcoin-appendix.md](docs/pokerweb/pokerweb-webcoin-appendix.md)
- **ウェブコイン（要約・案内）**: [docs/pokerweb/pokerweb-webcoin.md](docs/pokerweb/pokerweb-webcoin.md)
- **GameID 利用規約**: [docs/gameid/gameid_terms.md](docs/gameid/gameid_terms.md)
- **GameID プライバシーポリシー**: [docs/gameid/gameid_privacy.md](docs/gameid/gameid_privacy.md)
- **用語集（表記・定義の統一）**: [docs/terms/README.md](docs/terms/README.md)
- **LINE QA 運用**: [docs/support/line-qa/README.md](docs/support/line-qa/README.md)
- **法人情報（集約）**: [docs/globalpoint-corporate.md](docs/globalpoint-corporate.md)
- **選手契約関連（フォルダ）**: [docs/pokerguild/](docs/pokerguild/)

## ドキュメントの位置づけ（何を「正」として参照するか）

同じテーマでも「要約」や「案内」と「規約（正文）」が混在すると、参照先がブレやすくなります。顧客対応では、次の位置づけを基準に参照します。

| 種別 | 位置づけ | 主な保管先 |
|------|----------|------------|
| リリースノート | 対外発表の一次ソース（いつ・何を発表したか） | `docs/release/`（入口: [docs/release/README.md](docs/release/README.md)） |
| 利用規約（本体） | 契約条件の正文 | `docs/pokerweb/pokerweb-terms.md` / `docs/gameid/gameid_terms.md` |
| 個別規程（別紙・運用規程） | **本体規約より優先**する場合がある（オプション機能等） | `docs/pokerweb/pokerweb-webcoin-appendix.md` など |
| プライバシーポリシー | 利用者情報の取扱いの正文 | `docs/pokerweb/pokerweb-privacy.md` / `docs/gameid/gameid_privacy.md` |
| 説明資料・要約 | 概要把握・案内用（正文ではない） | `docs/pokerweb/pokerweb-service.md` / `docs/pokerweb/pokerweb-webcoin.md` / `docs/pokerweb/pokerweb-pricing.md` |
| 選手契約・同意文書 | 会員（プレイヤー）との契約・同意に関する正文 | `docs/pokerguild/` |
| 顧客対応運用（LINE QA） | 返信品質・レビュー・アーカイブ運用 | `docs/support/line-qa/` |
| 用語集 | 文書間の表記ゆれ・未定義語の解消（運用ルール） | `docs/terms/README.md` |
| 法人情報 | 会社情報・関連サービスの集約 | `docs/globalpoint-corporate.md` |

## 顧客対応の参照導線（よくある目的別）

- **過去の発表内容を確認したい**: [docs/release/README.md](docs/release/README.md)
- **契約条件（正文）を提示したい**: `docs/pokerweb/pokerweb-terms.md` / `docs/gameid/gameid_terms.md`
- **ウェブコインの運用条件を確認したい**: `docs/pokerweb/pokerweb-webcoin-appendix.md`（別紙）を優先
- **まず概要を把握したい**: `docs/pokerweb/pokerweb-service.md` / `docs/pokerweb/pokerweb-webcoin.md`
- **返信の型（短く、重要点中心）で回答したい**: `docs/support/line-qa/README.md`
- **表記・定義で迷った**: `docs/terms/README.md`

## 文書運用ルール（迷いを減らすための共通ルール）

- **語尾・文体**: 原則「です・ます」で統一（原文引用は除く）
- **用語**: 新しい用語・表記ゆれを見つけたら、まず [docs/terms/README.md](docs/terms/README.md) に追記してから各文書へ反映
- **参照先**: ルールの根拠は、可能な限り「規約（本体）」「別紙（個別規程）」「リリースノート」のいずれかに寄せる
- **「当社」等の定義**: 規約・ポリシー等は文書内定義が最優先（例: 第2条（定義））

## フォルダ構成

| パス | 内容 |
|------|------|
| `docs/release/` | 対外発表したリリースノート（入口: [docs/release/README.md](docs/release/README.md)） |
| `docs/pokerweb/` | POKERWEB の規約・ポリシー・説明資料・運用ルール |
| `docs/gameid/` | GameID の規約・ポリシー |
| `docs/pokerguild/` | 選手契約（業務委託契約）および付随する同意文書 |
| `docs/support/` | 顧客対応の運用（LINE QA 等） |
| `docs/terms/` | 用語集（入口: [docs/terms/README.md](docs/terms/README.md)） |

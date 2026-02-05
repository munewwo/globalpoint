# 合同会社グローバルポイント 顧客対応支援システム

グローバルポイント社の顧客対応を支援するシステムのプロジェクトです。

## このリポジトリで管理するもの

顧客対応を支援するため、対外的に公開・提示する（または提示の根拠となる）文書を整理・保管します。

- **リリースノート（対外発表の一覧）**: `docs/release/README.md`
- **利用規約・プライバシーポリシー**: `docs/pokerweb/` / `docs/gameid/`
- **サービス説明・運用ルール等**: `docs/pokerweb/`
- **用語集（表記ゆれ・未定義語の解消）**: `docs/terms/README.md`

上記の主な入口:

- **リリースノート一覧**: [docs/release/README.md](docs/release/README.md)
- **用語集**: [docs/terms/README.md](docs/terms/README.md)

## 主要ドキュメント（参照先）

### POKERWEB（`docs/pokerweb/`）

- **加盟クラブが支払うシステム利用料**: [docs/pokerweb/pokerweb-pricing.md](docs/pokerweb/pokerweb-pricing.md)
- **POKERWEB の説明**: [docs/pokerweb/pokerweb-service.md](docs/pokerweb/pokerweb-service.md)
- **ウェブコインの説明**: [docs/pokerweb/pokerweb-webcoin.md](docs/pokerweb/pokerweb-webcoin.md)

### GameID（`docs/gameid/`）

- **GameID 利用規約**: [docs/gameid/gameid_terms.md](docs/gameid/gameid_terms.md)
- **GameID プライバシーポリシー**: [docs/gameid/gameid_privacy.md](docs/gameid/gameid_privacy.md)

### カスタマー対応（LINE QA）

- **運用ガイド**: [docs/support/line-qa/README.md](docs/support/line-qa/README.md)
- **校正（レビュー）と誤回答修正フロー**: [docs/support/line-qa/REVIEW_WORKFLOW.md](docs/support/line-qa/REVIEW_WORKFLOW.md)

## 参照のしかた（顧客対応の導線）

- **過去の発表内容を確認したい**: [docs/release/README.md](docs/release/README.md)（日付順の一覧）
- **規約・ポリシーの全文を提示したい**: 下部「利用規約・プライバシーポリシー（参照）」のリンク
- **用語の定義や表記（ウェブコイン等）を揃えたい**: [docs/terms/README.md](docs/terms/README.md)

## 文書運用ルール（言葉遣い・用語の統一）

- **語尾・文体**: 原則として「です・ます」で統一します（既存文書の原文引用は除く）。
- **用語**: 新しい用語や表記ゆれを見つけたら、まず [docs/terms/README.md](docs/terms/README.md) に追記してから本文書へ反映します。
- **「当社」の扱い**: 規約等の文書では、**「当社」等の定義が文書内で指定**されます。本文書の会社情報と一致しない場合があるため、顧客対応では必ず各文書の定義（例: 第2条（定義））を優先してください。

## フォルダ構成

| パス | 内容 |
|------|------|
| `docs/release/` | 対外発表したリリースノート（一覧は [docs/release/README.md](docs/release/README.md)） |
| `docs/pokerweb/` | POKERWEB に関する規約・ポリシー・サービス説明・運用ルール |
| `docs/gameid/` | GameID に関する規約・ポリシー |
| `docs/terms/` | 用語集（正規表記、定義、注意点、表記ゆれの整理。入口は [docs/terms/README.md](docs/terms/README.md)） |

## 法人情報

法人情報および関連サービス情報は、次のファイルに集約しています。

- [docs/globalpoint-corporate.md](docs/globalpoint-corporate.md)

## 利用規約・プライバシーポリシー（参照）

POKERWEBおよびGameIDの利用規約・プライバシーポリシーの全文は、本リポジトリ内の以下のファイルに保管しています。概要のみここに記載します。

| 資料 | 概要 | 保管先 |
|------|------|--------|
| **POKERWEB 利用規約** | ウェブコイン（本サービス）の提供条件および当社と登録事業者との権利義務。適用・定義・登録・料金・禁止事項・ウェブコイン注意事項・停止・権利帰属・登録抹消・退会・免責・秘密保持・利用者情報・規約変更・管轄等（全22条）。 | [docs/pokerweb/pokerweb-terms.md](docs/pokerweb/pokerweb-terms.md) |
| **POKERWEB プライバシーポリシー** | POKERWEB上で公開するポリシーに準拠し、情報の安全性とプライバシーを重視してデータを取り扱う。登録完了をもって同意とみなす。変更時は最新に準拠。 | [docs/pokerweb/pokerweb-privacy.md](docs/pokerweb/pokerweb-privacy.md) |
| **GameID 利用規約** | ウェブコインの提供条件および当社と会員との権利義務。適用・定義・登録・運用（付与・送付時5%消費）・禁止事項・停止・権利帰属・登録抹消・退会・免責・秘密保持・利用者情報・規約変更・管轄等（全20条）。 | [docs/gameid/gameid_terms.md](docs/gameid/gameid_terms.md) |
| **GameID プライバシーポリシー** | GameIDアプリ上で公開するポリシーに準拠し、情報の安全性とプライバシーを重視してデータを取り扱う。アプリ登録完了をもって同意とみなす。変更時は最新に準拠。 | [docs/gameid/gameid_privacy.md](docs/gameid/gameid_privacy.md) |

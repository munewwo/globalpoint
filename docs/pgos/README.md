# PGOS — Poker Global Operating System

## プロジェクト概要

PGOS は、全国および海外のポーカー店舗・大会運営に必要な機能を統合的に提供するプラットフォームです。
現在グローバルポイント社が運営する **POKERGUILD**（スケジュールサービス）、**POKERWEB**（店舗オペレーション＆マネジメントシステム）、**GameID**（プレイヤー向け会員アプリ）の機能を統合し、自社開発の新システムとして構築します。

## 背景


| 項目         | 内容                                |
| ---------- | --------------------------------- |
| **企画・運営**  | 合同会社グローバルポイント                     |
| **対象ユーザー** | ポーカー店舗・大会主催者（運営側）、ポーカープレイヤー（利用者側） |
| **置き換え対象** | POKERWEB / GameID / POKERGUILD    |
| **展開スコープ** | 初期からグローバル対応（多言語・多通貨）              |


### 現行サービスの課題

- **POKERWEB / GameID** はブラジル開発元（PW SOFTWARES DE GESTAO LTDA）への依存度が高く、日本市場向けの機能追加・改善の自由度が低い
- **POKERGUILD** は情報掲載サイトにとどまり、店舗オペレーションとの連携が限定的
- **競合サービス**（Poker Fans 450店舗超、Waitinglist 230店舗超）が急速にシェアを伸ばしている
- UI/UX の刷新、リアルタイム機能、プレイヤー体験の強化が求められている

## PGOS が目指すもの

1. **店舗運営の一元管理** — トーナメント・リングゲーム・会員・売上を一つのシステムで
2. **プレイヤー体験の向上** — 店舗発見、ウェイティング、戦績追跡、ポイント管理をアプリで完結
3. **ポイントエコシステムの進化** — ウェブコインを発展させた、コンプライアンス対応済みのポイントシステム
4. **グローバル展開** — 多言語・多通貨対応を初期設計に組み込み、海外市場への展開を見据える
5. **データ活用** — プレイヤー戦績データベースの構築によるランキング・分析基盤（Hendon Mob / GPI 対抗）

## ドキュメント構成


| パス                                                | 内容              |
| ------------------------------------------------- | --------------- |
| `docs/pgos/README.md`                             | 本書（プロジェクト概要）    |
| `docs/pgos/competitive-analysis.md`               | 競合分析            |
| `docs/pgos/requirements/overview.md`              | 要件定義 全体概要       |
| `docs/pgos/requirements/player-features.md`       | プレイヤー側 機能要件     |
| `docs/pgos/requirements/operator-features.md`     | 店舗・イベント運営側 機能要件 |
| `docs/pgos/requirements/platform-architecture.md` | プラットフォーム・非機能要件  |
| `docs/pgos/requirements/webcoin-successor.md`     | ポイントシステム要件      |
| `docs/pgos/requirements/compliance.md`            | コンプライアンス要件      |
| `docs/pgos/requirements/migration.md`             | 既存サービスからの移行要件   |
| `docs/pgos/requirements/phases.md`                | フェーズ分け・ロードマップ   |


## 関連ドキュメント（既存）

- [法人情報](../globalpoint-corporate.md)
- [POKERWEB サービス概要](../pokerweb/pokerweb-service.md)
- [POKERWEB 料金](../pokerweb/pokerweb-pricing.md)
- [ウェブコイン運用ルール](../pokerweb/pokerweb-webcoin.md)
- [コンプライアンスロードマップ](../release/2025-06-05-compliance-roadmap.md)
- [利用規約一覧](../globalpoint/terms/)

## ステータス


| マイルストーン          | ステータス |
| ---------------- | ----- |
| 要件定義策定           | 進行中   |
| 技術スタック選定         | 未着手   |
| Phase 1 (MVP) 開発 | 未着手   |
| Phase 2 (拡張) 開発  | 未着手   |
| Phase 3 (差別化) 開発 | 未着手   |
| Phase 4 (移行・展開)  | 未着手   |



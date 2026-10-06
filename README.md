# raiga-company

ActionEdge(AXEN INC.)の営業・業務自動化のための、役割分担型AIエージェント組織リポジトリ。

詳細は [CLAUDE.md](./CLAUDE.md) を参照。

## 使い方(Claude Codeから)

このリポジトリを開いた状態のClaude Codeで、通常通りチャットするだけでメインセッションが「マネージャー」として動く。特定の業務を頼みたいときは該当のサブエージェントが自動的に呼ばれる(または明示的に指名する)。

例:
- 「不動産業界、江戸川区のリードを30社探して」→ lead-finder が担当
- 「このリストでフォーム営業の文面を作って」→ sales-outreach が担当
- 「〇〇株式会社向けの提案資料を作って」→ proposal-writer が担当
- 「送信した分の返信状況をまとめて」→ reply-tracker が担当
- 「リールの台本を作って」→ sns-planner が担当(SNS部)
- 「この動画にテロップを入れて」→ sns-producer が担当(SNS部)
- 「先月の投稿の数字を分析して」→ sns-analyst が担当(SNS部)

## 部門

- 営業部: lead-finder / sales-outreach / proposal-writer / reply-tracker
- SNS部: sns-planner / sns-producer / sns-analyst

## 現在のフェーズ

フォーム営業で最初の1件の受注を取ることを最優先に進行中。

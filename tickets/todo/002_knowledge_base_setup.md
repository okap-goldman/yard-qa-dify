# チケット2：ナレッジベース構築およびインデックス更新フロー実装

## 概要
Difyのナレッジベース(Dataset)を作成し、Markdownドキュメントをアップロードするワークフローを構築する。また、ナレッジ更新時に自動でインデックスが再構築されるフローを確認する。

## 詳細
- DifyコンソールまたはAPIでDataset（KB）新規作成
- Markdownファイルアップロード用エンドポイント（`/api/v1/datasets/{dataset_id}/documents`）の動作テスト
- KB更新後のインデキシング確認（最大1時間以内反映）
- サンプルMarkdownドキュメントアップロードテスト

## 対象ファイル
- `/Users/izutanikazuki/okp/yard-dify/docs/基本設計.md`
- `/Users/izutanikazuki/okp/yard-dify/docs/詳細設計.md`
- `/Users/izutanikazuki/okp/yard-dify/docs/要件定義.md`

## 見積もり時間
- 6時間

## 開始日
未定

## 終了日
未定

## ステータス
- [ ] Dataset作成（APIまたはコンソール）
- [ ] テスト用Markdownドキュメントアップロード
- [ ] インデックス更新確認
- [ ] KB検索APIテスト 
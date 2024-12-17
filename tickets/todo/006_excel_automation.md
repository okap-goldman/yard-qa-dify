# チケット6：エクセル→Markdown変換およびKB更新自動化(VBA)

## 概要
エクセルマニュアル更新後、VBAマクロボタンでMarkdown生成＆API呼び出しによりKB更新を自動化する仕組みを構築する。

## 詳細
- Excel VBAマクロ開発：
  - Excelシート→Markdownテキスト変換ロジック
  - Dify API（`/api/v1/datasets/{dataset_id}/documents`）呼び出し処理
- トークン認証やBasic認証方法の実装
- 成功レスポンス受領後、メッセージボックス表示

## 対象ファイル
- VBAマクロ格納Excelファイル（`*.xlsm`）
- マクロソースコード（Excel内）

## 見積もり時間
- 8時間

## 開始日
未定

## 終了日
未定

## ステータス
- [ ] Markdown変換ロジック実装
- [ ] API呼出し（XMLHTTP）実装
- [ ] 認証トークン管理方法確定
- [ ] テストアップロード成功確認 
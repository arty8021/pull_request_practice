## 関連する Issue

Fixes #[Issue番号]  
<!-- 
- このプルリクエストが対応する Issue 番号を記載してください（例: Fixes #123）。
- `Fixes`, `Closes`, `Resolves` などのキーワードを使うことで、このPRがマージされたときに関連 Issue も自動で Close されます。
-->

---

## このプルリクエストの目的

このプルリクエストは、リポジトリ内の関連する Issue に対して提案された変更を含みます。  
提案された変更の目的や背景について簡潔に説明してください。

例：

- 教材の割り当てロジックを修正し、教材の重複割り当てを防止  
  → 該当コード：[student_material_service.ts#L45-L60](https://github.com/your-org/your-repo/blob/branch-name/path/to/student_material_service.ts#L45-L60)
- `MaterialFlowRepository` において冗長なクエリを削除  
  → 修正箇所：[material_flow_repository.ts#L20-L25](https://github.com/your-org/your-repo/blob/branch-name/path/to/material_flow_repository.ts#L20-L25)
- UI における教材表示の整合性を修正（旧教材が残る問題の対応）

---

## 変更内容の詳細

| 種別 | 内容 |
|------|------|
| 機能追加 | [新しい機能や拡張の説明] |
| バグ修正 | [修正された問題の詳細] |
| リファクタ | [構造改善や可読性向上の説明] |
| その他 | [ドキュメント・CI 等の補足的変更] |

---

## 確認事項

以下のような動作確認を行いました：

例：

- 手動で教材割り当てを複数回行い、二重登録が発生しないことを確認  
- バグ再現手順を確認したうえで、修正後に同じ操作で再発しないことを確認  
- 該当変更に対するユニットテストを追加し、テストがすべて通過することを確認  

---

## レビュー観点

この変更において、特に以下の点を重点的にレビューしていただきたいです：

例：

- 割り当てロジックの副作用（意図しない教材削除や登録ミス）がないか  
- クエリ最適化における影響範囲（他の処理に影響していないか）  
- 命名・責務分離・設計の妥当性についてご意見いただけると助かります  

---

## スクリーンショット（UI 変更がある場合）

> UI に変更がある場合は、変更前・変更後の比較画像を添付してください。

---

## レビュー担当

@レビュワー1  
@レビュワー2  
<!-- このプルリクエストの内容に責任を持つレビュー担当者やチームを明記してください -->

---

## 補足

> 任意：実装上の注意点、今後の対応予定、既知の制限などがあれば記載

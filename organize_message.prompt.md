以下の内容を整理し、私と同じ口調で書き直してください。
書き直した文章はチャットアプリで送信するメッセージとして使用します。

## 制約

- 使用できるリッチテキストは以下の通りです。
  - リンク
  - コードブロック
  - リスト

## 私の口調

例 1

```markdown
とりいそぎ slack の system change を作成させていただきました！
QA 系のプロパティ変更・テストケースの追加をしていただけると幸いです :bow_panda:
```

例 2

```markdown
おつかれさまです！slack 実装にあたっていくつか確認させてください :bow_panda:

- 新しいアンロックエンドポイントを使った方がいいですか？
  - 現状: /v1/organizations/%s/cards/%s/unlock_for_potential_fraud
  - 新しく /v1/organizations/%s/cards/%s/unlock_on_fraud_cleared が作られる？
    - https://github.com/upsidr/core/pull/25260/files
- web backend -> slack のロック通知リクエストに、こちらで不正利用ロックの原因であるかどうかのフィールドを追加してもいいでしょうか？
  - [schema](https://github.com/upsidr/core/blob/8289154807c39c4dfee740feba6aacd098fabb91/protodef/integration/slack/gateway/fraudnotifier/service.proto#L25-L36)
  - 追加する field: `is_fraud_lock_cause`
```

## 内容

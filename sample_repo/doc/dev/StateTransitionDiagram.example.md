# 状態遷移図

## 認証

```mermaid
stateDiagram-v2
    [*] --> ログイン: ログイン状態
    [*] --> ログアウト: ログアウト状態

    ログイン --> ログアウト: ログアウト
    ログアウト --> ログイン: ログイン成功
    ログアウト --> ログアウト: ログイン失敗
```

認証フローの状態遷移図です。

# 3年以上婚活長期化と、「なぜか同じ別れを繰り返す」から抜け出す方法

parcy's × 田村ハヤト presents｜無料オンライントークライブ 集客LP

公開URL: https://subconscious-reading.github.io/happymarriage-talklive/

## 開催概要

| 項目 | 内容 |
|---|---|
| 日時 | 2026年8月22日（土）20:30〜22:00 |
| 形式 | Zoomオンライン／トークライブ形式 |
| 参加費 | 無料 |
| 登壇 | 中村あきら（parcy's）／田村ハヤト（聞き手） |

## ファイル構成（4ファイル・すべてリポジトリ直下）

```
index.html    LP本体。画像はすべてHTML内に埋め込み済み
support.js    index.html の描画に必須。削除・リネーム不可
ogp.jpg       SNSシェア時のサムネイル用（ページ表示には未使用）
.nojekyll     GitHub Pages の Jekyll 処理を無効化
```

サブフォルダは使用していません。4つとも同じ階層に置いてください。

## 未対応（公開前の要対応事項）

- [ ] 申込みボタンのリンク先（LINE友だち追加URL）の設定
      → `index.html` 内 `ctaUrl: this.props.ctaUrl ?? '#'` の `'#'` を差し替える
- [ ] プライバシーポリシー・特定商取引法に基づく表記のリンク先確認

## 更新方法

Claude Design で編集 → Export HTML →「Project archive」を選択。
書き出したファイルは画像が外部参照に戻るため、再度の埋め込み処理が必要です。

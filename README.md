# 長引く婚活と、「なぜか同じ別れを繰り返す」から抜け出す方法

parcy's × 田村ハヤト presents｜無料オンライントークライブ 集客LP

## 開催概要

| 項目 | 内容 |
|---|---|
| 日時 | 2026年8月22日（土）20:30〜22:00 |
| 形式 | Zoomオンライン／トークライブ形式 |
| 参加費 | 無料 |
| 登壇 | 中村あきら（parcy's）／田村ハヤト（聞き手） |

## 公開URL

https://subconscious-reading.github.io/happymarriage-talklive/

## ファイル構成

```
├─ index.html    LP本体（Claude Design 形式）
├─ support.js    index.html の描画に必須。削除・リネーム不可
├─ .nojekyll     GitHub Pages の Jekyll 処理を無効化
└─ uploads/      画像
   ├─ hero-proposal.jpg    メインビジュアル
   ├─ akira-profile.jpg    中村あきら
   ├─ hayato-profile.jpg   田村ハヤト
   └─ parcys-logo.png      parcy's ロゴ
```

`index.html` は `{{ }}` や `<sc-for>` といったテンプレート記法を含み、`support.js` が
読み込まれて初めて本文に展開されます。**この2つは必ずセットで配置してください。**

## 未対応（公開前の要対応事項）

- [ ] 申込みボタンのリンク先（LINE友だち追加URL）の設定
      → `index.html` 内 `ctaUrl: this.props.ctaUrl ?? '#'` の `'#'` を差し替える
- [ ] プライバシーポリシー・特定商取引法に基づく表記のリンク先確認
- [ ] OGP画像の差し替え検討（現在はメインビジュアルを流用）

## 更新方法

Claude Design で編集 → Export HTML →「Project archive」を選択 →
解凍した `.dc.html` を `index.html` にリネームして差し替え。
このとき画像パスの書き換え（半角英数名）と `<head>` 内のタイトル・OGPの再設定が必要です。

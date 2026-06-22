# MyNexus 🌾

「質問！」から生まれた解説ページを集めた知識ベース。

`question-explainer` スキルが、ユーザーの「質問！◯◯」に答える解説HTMLを生成し、
ここに体系的に蓄積していきます。

## 構成

```
index.html            … 入口。全ページの一覧＋カテゴリ絞り込み（ハブ）
pages/<id>.html       … 個別の解説ページ
data/pages.json       … 生成したページの台帳（連携・体系化のもと）
```

## 公開（GitHub Pages）

- リポジトリ Settings → Pages で、ソースを `main` ブランチ（`/root`）に設定すると公開されます。
- 公開URL: `https://blackapple96155-web.github.io/MyNexus/`

> ⚠️ private リポジトリの GitHub Pages は無料プランでは公開できません。
> public にするか、有料プラン（GitHub Pro 等）が必要です。

+++
title = "abridge テーマの補足ポイント"
date = 2025-04-11
draft = true
+++

## 小紅の一言

## 💡補足ポイント（**abridge テーマ**対応）

| フィールド | 説明 |
| --- | --- |
| `title`          | サイト全体のタイトルになります (ブラウザタブ・SEOに使用されます) |
| `description`    | サイトの説明文。SEOやOGPでの表示に活用されます |
| `sort_by`        | 投稿の並び順。通常は `"date"`　(新しい順) |
| `paginate_by`    | 1ページあたりの記事数。テーマによりページネーション表示されます |
| `template`       | 使用するテンプレートファイル。`abridge` ではデフォルトでOK (省略可能) |
| `taxonomies`     | カテゴリやタグの定義に使用します (例: `[ "tags", "categories" ]`) |
| `extra`          | カスタム設定用。テーマ特有のオプションやスタイルを入れるときに使います |

---

### 例：`extra` の設定

```toml
[extra]
enable_dark_mode = true
use_author = true
```

---

### 例：`taxonomies` の設定

```toml
taxonomies = ["tags", "categories"]
```

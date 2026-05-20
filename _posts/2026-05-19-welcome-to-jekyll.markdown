---
layout: post
title: "はじめてのブログ記事"
date: 2026-05-19 20:46:58 +0900
categories: つくる
tag_color: yellow
---

このサイトはJekyllで動いています。

`_posts` フォルダにMarkdownファイルを追加するだけで、トップページに自動で記事が増えていきます。

## 記事の書き方

ファイル名のルールは `YYYY-MM-DD-タイトル.md` です。

```
_posts/
  2026-05-20-my-new-post.md
  2026-05-21-another-post.md
```

## Front Matter（ヘッダー情報）

各記事の先頭に以下を書くと、カードのタグや色が変わります。

```yaml
---
layout: post
title: "記事タイトル"
date: 2026-05-20 12:00:00 +0900
categories: まなぶ        # カードのタグ表示
tag_color: blue            # yellow / blue / pink から選択
---
```

あとは普通のMarkdownで書くだけ。更新したら `git push` すれば自動で公開されます。

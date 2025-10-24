---
marp: true
theme: study
paginate: true
---
<!-- class: title -->

# Webアプリ開発勉強会 第2回
## ～HTMLの基礎～

---

<!-- class: -->

# 目次

---

# 1. そもそもHTMLとは？

webページの**構造**を記述するための言語。

HTML = Hyper-Text Markup Language の略。

タグと呼ばれるものを利用し、webページに表示する内容や構造を記述するもの。

タグは`<タグの名前>`という形で表現される。

---

# 2.webページの構造

**header**と**body**という大きな2つの部分で構成される。
![図1. webページの構造](images/png/webpage_sturucture_1.png)

---

# 2. HTMLの基本的なテンプレ

どのようなwebページも以下のような構成になっていることがほとんどである。  

```html
<!DOCTYPE html>
<html>
  <head>
    <title>ここにタイトル</title>
  </head>
  <body>
    ここにページ内容
  </body>
</html>
```


---

# 3. HTMLの基本的なタグ

| タグ名 | 説明  |
| ---- | ------------------------- |
| `html` | htmlであることを示す。必須。 |
| `head` | webページ上では<u>表示されない</u>情報などを指定する。 |
| `body` | webページに<u>表示される</u>部分。 |

---

# 4. 各タグについての解説

## 4-1. headタグ
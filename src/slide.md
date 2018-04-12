# markdown-slides-template

---

## What's this?

- Markdown でスライドを作るテンプレート
- [Reveal.js](https://revealjs.com)を利用しています
- 使うときは、このファイル ( `slide.md` ) を書き換えるだけです
- テーマは `src/css/theme` にいくつか用意されているので、好みのテーマを使ってください

---

## Markdown で書ける

- コードブロックの例 ( **Ruby** で Hello World )

```ruby
puts "Hello World!"
```

- *斜体* や **太字** 、 ~~打ち消し線~~ なども使えます

> 引用もできます

---

## Chart.js も使える

<canvas data-chart="pie">
<!--
{
  "data": {
    "labels": ["A", "B", "C"],
    "datasets": [{
      "backgroundColor": ["#FFCE56", "#FF6384", "#36A2EB"],
      "data": [25, 35, 40]
    }]
  },
  "options": { "responsive": "true" }
}
-->
</canvas>

---

<!-- .element: data-background="#4d7e65" -->
<!-- .element: class="has-green-background" -->

## 背景の変更

- ページの最初に下記を追加することで、背景を<br/>変更することができます

```markdown
<!-- .element: data-background="#4d7e65" -->
```

```markdown
<!-- .element: data-background="image.png" -->
```

```markdown
<!-- .element: data-background="image.png" data-background-repeat="repeat" data-background-size="100px" -->
```

---

## 使い方

- [このテンプレート](https://github.com/koki-sato/markdown-slides-template)を fork して clone してください
- 必要なパッケージを yarn でインストールします

```bash
$ yarn install
```

- ローカルでの動作確認や、GitHub Pages を用いて<br/>デプロイする方法は、[README](https://github.com/koki-sato/markdown-slides-template/blob/master/README.md)を確認ください

---

# Thanks!

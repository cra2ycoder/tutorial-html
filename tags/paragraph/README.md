# Paragraph

| Property            | Description |
| ------------------- | ----------- |
| Tag name            | p           |
| Required attributes | none        |
| Optional attributes | global      |
| Has close tag?      | yes         |
| Is group tag?       | no          |
| Child tags          | none        |
| Element type        | block-level |
| Has default styles? | yes         |

**description**

- used to add paragraph for the page
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p

**Tag omissions**

```html
<p>, <address>, <article>, <aside>, <blockquote>,
<div>, <dl>, <fieldset>, <footer>, <form>,
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>,
<header>, <hr>, <menu>, <nav>, <ol>, <pre>,
<section>, <table>, <ul>
```

**syntax**

```html
<p>
  a distinct section of a piece of writing, usually dealing with a single theme
  and indicated by a new line, indentation, or numbering.
</p>
```

---

## preview

![](https://cra2ycoder.sirv.com/html/paragraph.png)

---

## examples

- when we adding the `tag omission` tags

```html
<!--input-->
<p>
    This is Main Paragraph
    <p>This is Sub Paragraph</p>
</p>

<!--output-->
<p>This is Main Paragraph</p>
<p>This is Sub Paragraph</p>
<p></p>
```

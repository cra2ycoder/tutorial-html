## Heading

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements

| Property              | Description            |
| --------------------- | ---------------------- |
| Tag name              | h1, h2, h3, h4, h5, h6 |
| Required attributes   | none                   |
| Optional attributes   | global                 |
| Has close tag?        | yes                    |
| Is group tag?         | no                     |
| Child tags            | none                   |
| Element type          | block-level            |
| Has default styles?   | yes                    |
| Tag omission          | heading tags (h1-h6)   |
| Permitted parent tags | can be any             |

---

**description**

- used to add headings for the page
- h1: highest value tag
- h6: lowest value tag
- `default styles` are applicable
- difference for the each tag is nothing but, `font-size and the margins`

**syntax**

```html
<h1>Heading H1</h1>
<h2>Heading H2</h2>
<h3>Heading H3</h3>
<h4>Heading H4</h4>
<h5>Heading H5</h5>
<h6>Heading H6</h6>
```

---

## examples

- when using the heading tags inside the heading tags

  - scenario 1:

  ```html
  <!-- input -->
  <h1>
    <h2>Heading H2<h2>
  </h1>

  <!-- output -->
  <h1><h1>
  <h2>Heading H2</h2>
  <h2></h2>
  ```

  - scenario 2:

  ```html
  <!-- input -->
  <h1>
    Heading H1
    <h2>Heading H2<h2>
  </h1>

  <!-- output -->
  <h1>Heading H1<h1>
  <h2>Heading H2</h2>
  <h2></h2>
  ```
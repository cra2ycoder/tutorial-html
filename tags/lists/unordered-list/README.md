## Tag Name

| Property              | Description |
| --------------------- | ----------- |
| Tag name              | ul          |
| Required attributes   | none        |
| Optional attributes   | global      |
| Has close tag?        | yes         |
| Is group tag?         | yes         |
| Child tags            | li          |
| Element type          | block       |
| Has default styles?   | yes         |
| Permitted parent tags | can be any  |

---

**description**

- used to represent unordered list of items
- rendered as **bullet** list
- can be **nested**
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul

**Tag omissions**

```
none
```

**syntax**

```html
<ul>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ul>
```

---

## examples

**default example:**

```html
<ul>
  <li>fruits</li>
  <li>vegetables</li>
  <li>cars</li>
</ul>
```

**preview:**

<ul>
  <li>fruits</li>
  <li>vegetables</li>
  <li>cars</li>
</ul>

---

**nested example:**

```html
<ul>
  <li>fruits</li>
  <ul>
    <li>mango</li>
    <li>orange</li>
    <li>watermelon</li>
  </ul>
  <li>vegetables</li>
  <ul>
    <li>ladies finger</li>
    <li>potato</li>
    <li>tomato</li>
  </ul>
  <li>cars</li>
  <ul>
    <li>audi</li>
    <li>bmw</li>
    <li>honda</li>
  </ul>
</ul>
```

**preview:**

<ul>
  <li>fruits</li>
  <ul>
    <li>mango</li>
    <li>orange</li>
    <li>watermelon</li>
  </ul>
  <li>vegetables</li>
  <ul>
    <li>ladies finger</li>
    <li>potato</li>
    <li>tomato</li>
  </ul>
  <li>cars</li>
  <ul>
    <li>audi</li>
    <li>bmw</li>
    <li>honda</li>
  </ul>
</ul>

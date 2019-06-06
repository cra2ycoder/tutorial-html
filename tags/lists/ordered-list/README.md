## Ordered list

| Property            | Description |
| ------------------- | ----------- |
| Tag name            | ol          |
| Required attributes | none        |
| Optional attributes | global      |
| Has close tag?      | yes         |
| Is group tag?       | yes         |
| Child tags          | li          |
| Element type        | block       |
| Has default styles? | yes         |

---

**description**

- used to represent ordered list of items
- rendered as **numbered** list
- can be **nested**
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol

**syntax**

```html
<ol>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ol>
```

---

## examples

**default example:**

```html
<ol>
  <li>fruits</li>
  <li>vegetables</li>
  <li>cars</li>
</ol>
```

**preview:**

<ol>
  <li>fruits</li>
  <li>vegetables</li>
  <li>cars</li>
</ol>

---

**nested example:**

```html
<ol>
  <li>fruits</li>
  <ol>
    <li>mango</li>
    <li>orange</li>
    <li>watermelon</li>
  </ol>
  <li>vegetables</li>
  <ol>
    <li>ladies finger</li>
    <li>potato</li>
    <li>tomato</li>
  </ol>
  <li>cars</li>
  <ol>
    <li>audi</li>
    <li>bmw</li>
    <li>honda</li>
  </ol>
</ol>
```

**preview:**

<ol>
  <li>fruits</li>
  <ol>
    <li>mango</li>
    <li>orange</li>
    <li>watermelon</li>
  </ol>
  <li>vegetables</li>
  <ol>
    <li>ladies finger</li>
    <li>potato</li>
    <li>tomato</li>
  </ol>
  <li>cars</li>
  <ol>
    <li>audi</li>
    <li>bmw</li>
    <li>honda</li>
  </ol>
</ol>

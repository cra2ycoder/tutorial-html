## Anchor

| Property              | Description                     |
| --------------------- | ------------------------------- |
| Tag name              | a                               |
| Required attributes   | href                            |
| Optional attributes   | global                          |
| Has close tag?        | yes                             |
| Is group tag?         | no                              |
| Child tags            | none                            |
| Element type          | Inline-level                    |
| Has default styles?   | yes, if only there is a content |
| Permitted parent tags | can be any except same tag      |

---

**description**

- used to create a link between the pages / within the page
- Also, it will support to open the default mailers when we have the `mailto:` prefix in the `href` attribute
- Also, it wil support to open the default dialer when we have the `tel:` prefix int he `href` attribute
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a

**Tag omissions**

```
None
```

**syntax**

```html
<a href="https://www.google.com">Go to Google Page</a>
```

**actions**

- used to navigate the page
- there is a default css for normal state, visited state and click state (everything are color changes only)

---

## preview

<img src="./preview/anchor.png" width="300px"/>

---

## examples

```html
<a>Default View</a>
<a href="https://www.google.com">Go to Google Page</a>
<a href="#samepage">Internal</a>
<a href="#">Preventing Navigation</a>
<a href="anchor.html">Go to Anchor Page</a>
<a href="mailto:example@domain.com">example@domain.com</a>
<a href="tel:+123456789">+123456789</a>
```

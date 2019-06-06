## Details

| Property            | Description |
| ------------------- | ----------- |
| Tag name            | details     |
| Required attributes | no          |
| Optional attributes | global      |
| Has close tag?      | yes         |
| Is group tag?       | yes         |
| Child tags          | summary     |
| Element type        | block       |
| Has default styles? | yes         |

---

**description**

- its like mini accordian
- comes with inbuilt open/close state
- there is no in-built way to animate the open/close states
- `open` boolean attribute will be added when toggling the `details` tag
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details

**syntax**

```html
<details>
  <summary>Details</summary>
  <p>
    The HTML Details Element (details) creates a disclosure widget in which
    information is visible only when the widget is toggled into an "open" state.
  </p>
</details>
```

---

## examples

```html
<details>
  <summary>Flow Content</summary>
  <h2>Details Tag</h2>
  <p>
    The HTML Details Element (details) creates a disclosure widget in which
    information is visible only when the widget is toggled into an "open" state.
  </p>
  <img src="https://via.placeholder.com/150" alt="placeholder" />
  <p></p>
  <a href="https://www.google.com" target="_blank">Google.com</a>
</details>
```

<details>
  <summary>Flow Content</summary>
  <h2>Details Tag</h2>
  <p>
    The HTML Details Element (details) creates a disclosure widget in which
    information is visible only when the widget is toggled into an "open" state.
  </p>
  <img src="https://via.placeholder.com/150" alt="placeholder" />
  <p></p>
  <a href="https://www.google.com" target="_blank">Google.com</a>
</details>

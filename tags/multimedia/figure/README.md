## Figure

| Property            | Description      |
| ------------------- | ---------------- |
| Tag name            | figure           |
| Required attributes | no               |
| Optional attributes | global           |
| Has close tag?      | yes              |
| Is group tag?       | yes              |
| Child tags          | figcaption + img |
| Element type        | block            |
| Has default styles? | yes              |

---

**description**

- used to load image with caption
- to set `caption` for the figure we need to use `figcaption` tag
- for more:
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption

**Tag omissions**

```
none
```

**syntax**

```html
<figure>
  <img src="https://via.placeholder.com/150" alt="placeholder image" />
  <figcaption>Placeholder Caption</figcaption>
</figure>
```

---

## examples

```html
<figure>
  <img
    src="https://images.pexels.com/photos/207962/pexels-photo-207962.jpeg"
    width="480px"
    alt="love tree"
  />
  <figcaption>Love Tree</figcaption>
</figure>
```

<figure>
  <img
    src="https://images.pexels.com/photos/207962/pexels-photo-207962.jpeg"
    width="480px"
    alt="love tree"
  />
  <figcaption>Love Tree</figcaption>
</figure>

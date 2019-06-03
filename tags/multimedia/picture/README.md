## Picture

| Property            | Description |
| ------------------- | ----------- |
| Tag name            | picture     |
| Required attributes | no          |
| Optional attributes | global      |
| Has close tag?      | yes         |
| Is group tag?       | yes         |
| Child tags          | img, source |
| Element type        | inline      |
| Has default styles? | no          |

---

**description**

- picture tag help us to load the image (different or same). Based on the device dimensions
- `source` tag will store the image urls with `media` attribute
- `img` tag will load the image by fetching it from `source` tag based on the device dimension else loads default image.
- for more:
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source

**Tag omissions**

```
none
```

**syntax**

```html
<picture>
  <source srcset="https://via.placeholder.com/300" media="(max-width: 300px)" />
  <source srcset="https://via.placeholder.com/600" media="(max-width: 600px)" />
  <source srcset="https://via.placeholder.com/900" media="(max-width: 900px)" />
  <img src="https://via.placeholder.com/150" alt="placeholder image" />
</picture>
```

---

## examples

<picture>
  <source srcset="https://via.placeholder.com/300" media="(max-width: 300px)" />
  <source srcset="https://via.placeholder.com/600" media="(max-width: 600px)" />
  <source srcset="https://via.placeholder.com/900" media="(max-width: 900px)" />
  <img src="https://via.placeholder.com/150" alt="placeholder image" />
</picture>

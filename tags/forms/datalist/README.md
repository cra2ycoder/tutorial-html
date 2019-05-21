## datalist

| Property              | Description |
| --------------------- | ----------- |
| Tag name              | datalist    |
| Required attributes   | id          |
| Optional attributes   | global      |
| Has close tag?        | yes         |
| Is group tag?         | yes         |
| Child tags            | option      |
| Element type          | inline      |
| Has default styles?   | yes         |
| Permitted parent tags | can be any  |

---

**description**

- contains a set of `option` elements that represent the values available for other controls.
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist

**Tag omissions**

```
none
```

**syntax**

```html
<datalist id="car-list">
  <option value="BMW"></option>
  <option value="Audi"></option>
  <option value="Benz"></option>
  <option value="Volkswogan"></option>
  <option value="Jaguar"></option>
</datalist>
```

---

## preview

---

## examples

```html
<!-- suggestions list -->
<datalist id="car-list">
  <option value="BMW"></option>
  <option value="Audi"></option>
  <option value="Benz"></option>
  <option value="Volkswogan"></option>
  <option value="Jaguar"></option>
</datalist>

<form action="">
  <input type="text" list="car-list" />
</form>
```

## Label

| Property              | Description |
| --------------------- | ----------- |
| Tag name              | label       |
| Required attributes   | for         |
| Optional attributes   | global      |
| Has close tag?        | yes         |
| Is group tag?         | no          |
| Child tags            | no          |
| Element type          | inline      |
| Has default styles?   | yes         |
| Permitted parent tags | can be any  |

---

**description**

- used to create a caption
- to associate the `label` with `input` element, we need to use `for` attribute
- mostly this tag will be used in the form elements to set the title/heading/caption
- this is more helpful on the semantic end
- best replacement for `placeholder` attribute
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label

**Tag omissions**

```
none
```

**syntax**

```html
<label for="input-cap">Input Caption</label>
<input id="input-cap" type="text" />
```

---

## examples

```html
<!-- default -->
<label>Default Label</label>
<hr />

<!-- with form tag -->
<form action="">
  <label for="lbl-fn">First Name</label>
  <input id="lbl-fn" type="text" />
</form>

<!-- inline  -->
<form action="">
  <label>
    Last Name
    <input type="text" />
  </label>
</form>
```

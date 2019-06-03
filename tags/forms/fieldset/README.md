## Fieldset

| Property            | Description |
| ------------------- | ----------- |
| Tag name            | fieldset    |
| Required attributes | -           |
| Optional attributes | global      |
| Has close tag?      | yes         |
| Is group tag?       | yes         |
| Child tags          | legend      |
| Element type        | block       |
| Has default styles? | yes         |

---

**description**

- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/fieldset

**Tag omissions**

```
none
```

**syntax**

```html
<fieldset>
  <legend>Field Caption</legend>
  <!-- ...Form Fields goes here... -->
</fieldset>
```

**useful attributes**

| Property | values  | Description                 |
| -------- | ------- | --------------------------- |
| disabled | boolean | used to disable form fields |

---

## preview

---

## examples

```html
<!-- Default -->
<fieldset>
  <legend>Choose your Fruits</legend>
  <input type="checkbox" id="apple" />
  <label for="apple">Apple</label>

  <input type="checkbox" id="orange" />
  <label for="orange">Orange</label>
</fieldset>

<!-- With Form -->
<fieldset>
  <legend>Signin Form</legend>

  <label for="fn">First Name:</label>
  <input type="text" name="first-name" id="fn" />

  <label for="ln">Last Name:</label>
  <input type="text" name="last-name" id="ln" />

  <button>Submit</button>
</fieldset>

<!-- disabled -->
<fieldset disabled>
  <legend>Choose your Fruits</legend>
  <input type="checkbox" id="apple" />
  <label for="apple">Apple</label>

  <input type="checkbox" id="orange" />
  <label for="orange">Orange</label>
</fieldset>
```

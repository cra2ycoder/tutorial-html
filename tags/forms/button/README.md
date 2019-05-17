## Button

| Property              | Description             |
| --------------------- | ----------------------- |
| Tag name              | button                  |
| Required attributes   | type/name/value         |
| Optional attributes   | autofocus/disabled      |
| Has close tag?        | yes                     |
| Is group tag?         | no                      |
| Child tags            | no                      |
| Element type          | inline                  |
| Has default styles?   | yes                     |
| Permitted parent tags | form (semantic purpose) |

---

**description**

- used to add a button in a form with clickable action
- comes with three types by default: **button, submit and reset**
- and, if there is no type attribute declared then, it will be considered as **submit** button
- actions/by default functionality:

  - **button:**

    - only renders the UI
    - and prevent the default functions by the browser
    - allows the user to add custom function

  - **submit:**

    - submit the form data to the web server (post/get) based on the attributes given in the form tag
    - refresh page
    - query params will be append automatically with the url

  - **reset:**

    - clear the new values that are entered in the form elements by the user
    - and reset to old value (which is already declared when the form renders)

- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button

---

**Tag omissions**

```
none
```

---

**syntax**

```html
<button>button</button>
```

---

**useful attributes**

| Property  | values          | Description                               |
| --------- | --------------- | ----------------------------------------- |
| autofocus | true/false      | used to set highlight when the page loads |
| disabled  | true/false      | used to disable the button                |
| name      | string          | set the name, uses for form submission    |
| value     | string          | set the value, uses for form submission   |
| target    | \_self, \_blank | as like anchor tag functions              |

---

## examples

- Default

```html
<button>button</button>
```

---

- button with different types (button, submit, reset)

```html
<button type="submit">Submit</button>
<button type="button">Button</button>
<button type="reset">Reset</button>
```

---

- button with disable state

```html
<button type="button" disabled>Disabled</button>
```

---

- button with form data properties (name, value)

```html
<button name="btn" value="custom">Custom</button>
```

---

- button with autofocus

```html
<button type="button" autofocus>Auto Focus</button>
```

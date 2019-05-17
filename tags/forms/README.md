# Forms

- contains interactive controls
- submitting information to a web server

---

## Tag Name

| Property              | Description                   |
| --------------------- | ----------------------------- |
| Tag name              | form                          |
| Required attributes   | action, method                |
| Optional attributes   | id, target, global properties |
| Has close tag?        | yes                           |
| Is group tag?         | yes                           |
| Child tags            | yes                           |
| Element type          | block                         |
| Has default styles?   | yes - not ui specific         |
| Permitted parent tags | can be any                    |

---

**description**

- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form

**Tag omissions**

```
none
```

**syntax**

```html
<form action=""></form>
```

**useful attributes**

| Property | values          | Description                                  |
| -------- | --------------- | -------------------------------------------- |
| action   | server url      | where the form needs to post or get the info |
| target   | \_self, \_blank | works like anchor tag                        |
| name     | string          | used to set the name of the form             |
| method   | get, post       | used to set the submission method            |
| enctype  | string          | used to set content encryption type          |

---

## examples

```html
<form action="/anyservice/service.php" method="post">
  <input name="first-name" />
  <input name="last-name" />
  <button>Submit</button>
</form>
```

## Textarea

| Property            | Description |
| ------------------- | ----------- |
| Tag name            | textarea    |
| Required attributes | rows, cols, |
| Optional attributes | wrap        |
| Has close tag?      | yes         |
| Is group tag?       | no          |
| Child tags          | no          |
| Element type        | inline      |
| Has default styles? | yes         |

---

**description**

- used to get multiple text from user
- has resize control by default
- example: feedback, comment and review forms
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea

**syntax**

```html
<textarea></textarea>
```

**useful attributes**

| Property    | values     | Description                              |
| ----------- | ---------- | ---------------------------------------- |
| autofocus   | true/false | used to enable auto highlight by default |
| disable     | true/false | used to disable the input box            |
| readonly    | true/false | allows only to read                      |
| required    | true/false | make the field as mandatory              |
| placeholder | string     | used to set placeholder text             |
| minlength   | number     | used to minimum length of the character  |
| maxlength   | number     | used to maximum length of the character  |

---

## examples

```html
<!-- Default -->
<textarea></textarea>
<hr />

<!-- attr: rows and columns -->
<textarea cols="30" rows="10"></textarea>
<hr />

<!-- attr: placeholder -->
<textarea
  placeholder="Add your comments here...."
  cols="30"
  rows="10"
></textarea>
<hr />

<!-- attr: wrap: soft|hard -->
<textarea
  cols="30"
  rows="10"
  wrap="soft"
  placeholder="Add your comments here...."
></textarea>
<hr />

<!-- attr: minlength and maxlength -->
<textarea cols="30" rows="10" minlength="10" maxlength="50"></textarea>
<hr />
```

## Select

| Property            | Description      |
| ------------------- | ---------------- |
| Tag name            | select           |
| Required attributes | -                |
| Optional attributes | size, multiple   |
| Has close tag?      | yes              |
| Is group tag?       | yes              |
| Child tags          | option, optgroup |
| Element type        | inline           |
| Has default styles? | yes              |

---

**description**

- used to create dropdown list or multiple selection list
- `option` tag should be used for creating the list
- first option will be the default value
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select

**Tag omissions**

```
none
```

**syntax**

```html
<select id="dd-list">
  <option value="">Please select</option>
  <option value="opt1">Option 1</option>
  <option value="opt2">Option 2</option>
  <option value="opt3">Option 3</option>
</select>
```

**useful attributes**

| Property | values  | Description                                  |
| -------- | ------- | -------------------------------------------- |
| size     | number  | used to set how many items should be visible |
| multiple | boolean | used to convert as multiple option list      |

---

## examples

```html
<!-- Default -->
<select id="cars-list">
  <option value="">Please select</option>
  <option value="audi">Audi</option>
  <option value="bwm">BMW</option>
  <option value="jquar">Jquar</option>
</select>

<!-- With multiple options + size -->
<select id="fruit-list" multiple size="10">
  <option value="">Select your favorite fruit!</option>
  <option value="apple">Apple</option>
  <option value="mango">Mango</option>
  <option value="pineapple">Pineapple</option>
  <option value="orange">Orange</option>
  <option value="guava">Guava</option>
</select>
<p>use shift key for multiple selection.</p>

<!-- with option group -->
<select id="cars-list-multiple">
  <optgroup label="Maruthi">
    <option value="ertiga">Ertiga</option>
    <option value="scross">scross</option>
    <option value="belano">belano</option>
  </optgroup>
  <optgroup label="hyndai">
    <option value="creta">Creta</option>
    <option value="verna">Verna</option>
    <option value="santro">Santro</option>
  </optgroup>
</select>

<!-- with option group + multiple -->
<select id="cars-list-multiple-optg" multiple size="10">
  <optgroup label="Maruthi">
    <option value="ertiga">Ertiga</option>
    <option value="scross">scross</option>
    <option value="baleno">baleno</option>
  </optgroup>
  <optgroup label="hyndai">
    <option value="creta">Creta</option>
    <option value="verna">Verna</option>
    <option value="santro">Santro</option>
  </optgroup>
</select>
```

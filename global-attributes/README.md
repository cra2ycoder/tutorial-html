# Global Attributes

- common to all HTML elements
- they can be used on all elements, though they may have no effect on some elements.

---

## List of Global Attributes

<!-- - [accesskey](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/accesskey)

- [autocapitalize](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/autocapitalize)
-->

- [class](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/class)

  - space-separated list of the classes of the element
  - Classes allow CSS
  - Class names used as selectors to select and access the element through javascript Javascript `document.getElementsByClassName()`

```html
<style>
  .size {
    width: 100px;
    height: 40px;
  }

  .position {
    text-align: center;
    line-height: 40px;
  }

  .theme {
    color: white;
    background-color: red;
    font-size: 1rem;
  }
</style>
<div class="size position theme">Button</div>
<script type="text/javascript">
  var element = document.getElementsByClassName("size");
  console.log(element); // HTMLCollection
</script>
```

---

- [contenteditable](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/contenteditable)

  - an enumerated attribute indicating if the element should be editable by the user. If so, the browser modifies its widget to allow editing.

```html
<div contenteditable="true">Type here to change the value...</div>
```

---

<!-- - [contextmenu](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/contextmenu) -->

- [data-\*](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/data-*)

  - custom data attributes,
  - allow proprietary information to be exchanged between the HTML and its DOM representation by scripts.

```html
<div id="product-item" data-id="1" data-name="product" data-info="product info">
  Product
</div>
<script type="text/javascript">
  var element = document.getElementById("product-item");
  console.log(element.dataset);
  // DOMStringMap { id: "1", name: "product", info: "product info"}
</script>
```

---

- [dir](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/dir)

  - an enumerated attribute indicates the directionality of the element's text.

```html
<p dir="rtl">
  This paragraph is in English but wrongly goes right to left.
</p>
<p dir="ltr">
  This paragraph is in English and correctly goes left to right.
</p>
```

---

- [draggable](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/draggable)

  - enumerated attribute that indicates whether the element can be dragged, either with native browser behavior or the HTML Drag and Drop API.

```html
<img src="https://via.placeholder.com/150?text=Drag Me" draggable="true" />
<div draggable="true">Drag Me</div>
```

---

<!-- - [dropzone](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/dropzone)

- [exportparts](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/exportparts) -->

- [hidden](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/hidden)

  - used to hide the elements of the page

```html
<p hidden>
  This content is not relevant to this page right now, so should not be seen!
</p>
```

---

- [id](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/id)

  - defines an identifier (ID)
  - must be unique in the whole document.
  - Its purpose is to identify the element when linking, scripting, or styling (with CSS).

```html
<button id="btn-submit">submit</button>
<script type="text/javascript">
  var element = document.getElementById("btn-submit");
  console.log(element);
</script>
```

---

<!-- - [inputmode](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/inputmode) -->

<!-- - [is](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/is) -->

- [itemid](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemid)

- [itemprop](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemprop)

- [itemref](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemref)

- [itemscope](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemscope)

- [itemtype](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemtype)

---

- [lang](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang)

  - helps define the language of an element
  - If the attribute value is the empty string `(lang="")`, the language is set to unknown;
  - if the language tag is not valid according to **BCP47**, it is set to invalid.

```html
<p lang="en-GB">This paragraph is defined as British English.</p>
<p lang="fr">Ce paragraphe est défini en français.</p>
```

---

<!-- - [part](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/part)
- [slot](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/slot) -->

---

- [spellcheck](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/spellcheck)

  - it is an enumerated attribute defines whether the element may be checked for spelling errors.

```html
<p contenteditable spellcheck="true">
  This exampull will be checkd fur spellung when you try to edit it.
</p>

<p contenteditable spellcheck="false">
  This exampull will nut be checkd fur spellung when you try to edit it.
</p>
```

---

- [style](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/style)

  - contains CSS styling declarations to be applied to the element
  - it is recommended for styles to be defined in a separate file or files
  - This attribute and the style element have mainly the purpose of allowing for quick styling, for example for testing purposes.

```html
<div style="background: #ffe7e8; border: 2px solid #e66465;">
  <p style="margin: 15px; line-height: 1.5; text-align: center;">
    Well, I am the slime from your video<br />
    Oozin' along on your livin' room floor.
  </p>
</div>
```

---

- [tabindex](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex)

  - indicates if its element can be focused, and if/where it participates in sequential keyboard navigation (usually with the Tab key, hence the name).

```html
<p tabindex="0">tabindex 0</p>
<p tabindex="1">tabindex 1</p>
<p tabindex="2">tabindex 2</p>
```

---

- [title](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/title)

  - contains text representing advisory information related to the element it belongs to.

```html
<p>
  The three primary web development technologies are
  <abbr title="Hypertext Markup Language">HTML</abbr>,
  <abbr title="Cascading Stylesheets">CSS</abbr>, and JavaScript.
</p>
```

---

<!-- - [translate](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/translate) -->

---

## Event Handler Global Attributes

```
onabort, onautocomplete, onautocompleteerror, onblur, oncancel, oncanplay, oncanplaythrough,
onchange, onclick, onclose, oncontextmenu, oncuechange, ondblclick, ondrag, ondragend,
ondragenter, ondragexit, ondragleave, ondragover, ondragstart, ondrop, ondurationchange,
onemptied, onended, onerror, onfocus, oninput, oninvalid, onkeydown, onkeypress, onkeyup,
onload, onloadeddata, onloadedmetadata, onloadstart, onmousedown, onmouseenter,
onmouseleave, onmousemove, onmouseout, onmouseover, onmouseup, onmousewheel, onpause,
onplay, onplaying, onprogress, onratechange, onreset, onresize, onscroll, onseeked,
onseeking, onselect, onshow, onsort, onstalled, onsubmit, onsuspend, ontimeupdate, ontoggle,
onvolumechange, onwaiting
```

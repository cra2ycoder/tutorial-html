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

  - yet to add description

- [inputmode](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/inputmode)

  - yet to add description

- [is](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/is)

  - yet to add description

- [itemid](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemid)

  - yet to add description

- [itemprop](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemprop)

  - yet to add description

- [itemref](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemref)

  - yet to add description

- [itemscope](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemscope)

  - yet to add description

- [itemtype](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemtype)

  - yet to add description

- [lang](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang)

  - yet to add description

- [part](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/part)

  - yet to add description

- [slot](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/slot)

  - yet to add description

- [spellcheck](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/spellcheck)

  - yet to add description

- [style](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/style)

  - yet to add description

- [tabindex](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex)

  - yet to add description

- [title](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/title)

  - yet to add description

- [translate](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/translate)

  - yet to add description

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

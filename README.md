# tutorial-html

A complete html and html5 tutorial for study

## What is HTML?

- expands `Hypertext Markup Language`
- standard markup language for creating web pages and web applications.
- uses for appearance/presentation `CSS`
- uses for functionality/behavior `JavaScript`.

## What is Markup Language?

- A `markup language` is a `computer language`
- uses `tags` to **define elements within a document**.
- markup files contain standard words, rather than typical programming syntax.(In simple, It is human-readable)

## What is HyperText?

- refers to links that connect web pages to one another, either within a single website or between websites.
- Links are a fundamental aspect of the Web.
- By uploading content to the Internet and linking it to pages we will become active participant in the **World Wide Web**

## What are tags?

- `tags` are basically surrounded by `<` and `>` (angle brackets)
- the name inside a tag is case `insensitive`

```html
<title>
<TITLE>
<Title>
```

---

# HTML Basics

## Anatomy of an HTML element

### structure

![](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)

**NOTE:**

- open tag and close tag should have the same name
- **close tag** must be contained a `/` (forward slash)
- Note that, there are some tags which doesn't have the `close tag` by default.

### attributes

- used to add `extra` information about the tag, which will not be shown in the page

![](https://mdn.mozillademos.org/files/9345/grumpy-cat-attribute-small.png)

**Usage:**

- to fetch the correct element through the `javascript`
- to write css for styling
- to data maintaining

**NOTE:**

- attributes must be defined inside the open tag only.
- custom attributes can be added
- attributes can be `n` number in one tag
- syntax: **propertyName="propertyValue"** (example: class="my-class")
- propertyValue should be surrounded by the `""` (double-quotes)

### Empty elements

- Some elements have no content and are called empty elements.
  (ex: <img />)
- which element doesn't have the content as well as close tag then those are called `empty elements`

---

## Anatomy of an HTML document

**structure**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>
```

`<!DOCTYPE html>`

- to define the doctype and the version

`<html></html>`

- `root` of the html document, or `wrapper`

`<head></head>`

- its a `container`
- help to include some stuffs which are like, css, script and meta information

`<meta charset="utf-8">`

- the character set your document should use to `UTF-8`
- not required to use, but it would help us to resolve some problems in later

`<title></title>`

- your document title
- which will be displayed in the `Browser Tab`
- used for: `bookmark/favourite`

`<body></body>`

- used to show content in the browser
- like: text, images, videos or whatever

---

## What are the markup languages available?

- [LaTex](https://www.overleaf.com/learn/latex/Creating_a_document_in_LaTeX)
- [Extensible Markup Language (XML)](https://www.tutorialspoint.com/xml/xml_documents.htm)
- [Generalized Markup Language (GML)]()
- [Standard Generalized Markup Language (SGML)]()
- [HyperText Markup Language (HTML)](https://developer.mozilla.org/en-US/docs/Web/HTML)

## Core Pieces

- [Main root](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Main_root)
- [Document metadata](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Document_metadata)
- [Sectioning root](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Sectioning_root)
- [Content sectioning](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Content_sectioning)
- [Text Content](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Text_content)
- [Inline text semantics](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics)
- [Image and multimedia](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Image_and_multimedia)
- [Embedded content](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Embedded_content)
- [Scripting](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Scripting)
- [Demarcating edits](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Demarcating_edits)
- [Table Contents](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Table_content)
- [Forms](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Forms)
- [Interactive elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Interactive_elements)
- [Web Components](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Web_Components)
- [Obsolete and deprecated elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Obsolete_and_deprecated_elements)

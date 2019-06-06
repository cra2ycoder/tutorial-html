# Tags

<details>
    <summary><b>html structure</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html">html</a>
    <p>root (top-level element) of an HTML document</p>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head">head</a>
    <p>contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets.</p>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title">title</a>
    <ul>
        <li>defines the document's title</li>
        <li>title shown in a browser's title bar or a page's tab.</li>
        <li>contains only text</li>
        <li>tags within the element are ignored.</li>
    </ul>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body">body</a>
    <p></p>
    <ul>
        <li>represents the content of an HTML document.</li>
        <li>can be only one body element in a document.</li>
    </ul>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base">base</a>
    <ul>
        <li>specifies the base URL</li>
        <li>used for all relative URLs contained within a document.</li>
        <li>there can be only one base element in a document.</li>
    </ul>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta">meta</a>
    <p>represents metadata that cannot be represented by other HTML meta-related elements, like base, link, script, style or title.</p>
</details>

---

<details>
    <summary><b>headings</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements">h1-h6</a>
    <p>represent six levels of section headings. h1 is the highest section level and h6 is the lowest.</p>
</details>

---

<details>
    <summary><b>paragraph</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p">p</a>
    <p>represents a paragraph</p>
</details>

---

<details>
    <summary><b>anchor</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a">a</a>
    <p>creates a hyperlink to other web pages, files, locations within the same page, email addresses, or any other URL.</p>
</details>

---

<details>
    <summary><b>image</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img">img</a>
    <p>embeds an image into the document.</p>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/map">map</a>
    <p>used with area elements to define an image map (a clickable link area).</p>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/area">area</a>
    <p>defines a hot-spot region on an image, and optionally associates it with a hypertext link. This element is used only within a <map> element.</p>
</details>

---

<details>
    <summary><b>figure</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure">figure</a>
    <p>represents self-contained content with an optional caption, which is specified using the (figcaption) element. The figure, its caption, and its contents are referenced as a single unit.</p>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption">figcaption</a>
    <p>represents a caption or legend of its parent figure element.</p>
</details>

---

<details>
    <summary><b>picture</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture">picture</a>
    <ul>
        <li>contains zero or more source elements and one img element</li>
        <li>used to provide versions of an image for different display/device scenarios.</li>
        <li>Browser will consider the best match from source list and load accordingly</li>
        <li>If no matches are found from the source tag then it will load the default image tag source (src)</li>
    </ul>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source">source</a>
    <ul>
        <li>specifies multiple media resources for the picture, audio and video.</li>
        <li>It is an empty element, meaning that it has no content and does not have a closing tag</li>
        <li>It is commonly used to serve the same media content in multiple formats supported by different browsers.</li>
    </ul>
</details>

---

<details>
    <summary><b>list</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul">ul</a>
    <ul>
        <li>represents an unordered list of items</li>
        <li>typically rendered as a bulleted list.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol">ol</a>
    <ul>
        <li>represents an ordered list of items</li>
        <li>typically rendered as a numbered list.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li">li</a>
    <ul>
        <li>used to represent an item in a list.</li>
        <li>It must be contained in a parent element: an ordered list (ol), an unordered list (ul), or a menu (menu).</li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>media</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio">audio</a>
    <ul>
        <li>used to embed sound content in documents</li>
        <li>It may contain one or more audio sources, represented using the src attribute or the source element</li>
        <li>The browser will choose the most suitable one. </li>
        <li>It can also be the destination for streamed media, using a MediaStream.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video">video</a>
    <ul>
        <li>Embeds a media player which supports video playback into the document.</li>
        <li>You can use video for audio content as well, but the audio element may provide a more appropriate user experience.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/track">track</a>
    <ul>
        <li>Used as a child of the media elements audio and video</li>
        <li>It lets you specify timed text tracks (or time-based data), for example to automatically handle subtitles.</li>
        <li>The tracks are formatted in WebVTT format (.vtt files) — Web Video Text Tracks or Timed Text Markup Language (TTML).</li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>forms</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form">form</a>
    <ul>
        <li>represents a document section that contains interactive controls for submitting information to a web server.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button">button</a>
    <ul>
        <li>Represents a clickable button</li>
        <li>Which can be used in forms or anywhere in a document that needs simple, standard button functionality.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input">input</a>
    <ul>
        <li>Used to create interactive controls for web-based forms in order to accept data from the user</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label">label</a>
    <ul>
        <li>Represents a caption for an item in a user interface</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea">textarea</a>
    <ul>
        <li>Represents a multi-line plain-text editing control</li>
        <li>Useful when you want to allow users to enter a sizeable amount of free-form text</li>
        <li>Example: Comment on a review or feedback form.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select">select</a>
    <ul>
        <li>Represents a control that provides a menu of options</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option">option</a>
    <ul>
        <li>Used to define an item contained in a select an optgroup, or a datalist element.</li>
        <li>Represent menu items in popups and other lists of items in an HTML document.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist">datalist</a>
    <ul>
        <li>contains a set of option elements that represent the values available for other controls.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/progress">progress</a>
    <ul>
        <li>Displays an indicator showing the completion progress of a task, typically displayed as a progress bar.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/fieldset">fieldset</a>
    <ul>
        <li>Used to group several controls as well as labels within a web form.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/legend">legend</a>
    <ul>
        <li>Represents a caption for the content of its parent fieldset.</li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>inline</b></summary>
    <br/>
    <h4>most re-used</h4>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br">br</a>
    <ul>
        <li>produces a line break in text (carriage-return).</li>
        <li>It is useful for writing a poem or an address, where the division of lines is significant.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span">span</a>
    <ul>
        <li>It is a generic inline container for phrasing content, which does not inherently represent anything.</li>
        <li>It should be used only when no other semantic element is appropriate.</li>
        <li>span is very much like a div element.</li>
        <li>div is a block-level element whereas a span is an inline element.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/abbr">abbr</a>
    <ul>
        <li>represents an abbreviation or acronym</li>
        <li>the optional title attribute can provide an expansion or description for the abbreviation.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/code">code</a>
    <ul>
        <li>displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd">kbd</a>
    <ul>
        <li>represents a span of inline text denoting textual user input from a keyboard, voice input, or any other text entry device</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/mark">mark</a>
    <ul>
        <li>represents text which is marked or highlighted for reference or notation purposes</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/del">del</a>
    <ul>
        <li>represents a range of text that has been deleted from a document</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ins">ins</a>
    <ul>
        <li>represents a range of text that has been added to a document</li>
    </ul>
    <br />
    <h4>rare</h4>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b">b</a>
    <ul>
        <li>Used to set bold style to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i">i</a>
    <ul>
        <li>Used to set italic styled to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/u">u</a>
    <ul>
        <li>Used to set underline style to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">q</a>
    <ul>
        <li>Used to include the double quotes to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/s">s</a>
    <ul>
        <li>Used to set the strike through style to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/small">small</a>
    <ul>
        <li>Used to set the font size to smaller to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong">strong</a>
    <ul>
        <li>Used to set bold style to the text</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sub">sub</a>
    <ul>
        <li>specifies inline text which should be displayed as subscript for solely typographical reasons.</li>
        <li>Subscripts are typically rendered with a lowered baseline using smaller text.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sup">sup</a>
    <ul>
        <li>specifies inline text which is to be displayed as superscript for solely typographical reasons</li>
        <li>Superscripts are usually rendered with a raised baseline using smaller text.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time">time</a><ul>
        <li>represents a specific period in time</li>
        <li>It may include the datetime attribute to translate dates into machine-readable format</li>
        <li>Allowing for better search engine results or custom features such as reminders.</li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>interactive</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details">details</a>
    <ul>
        <li>creates a disclosure widget in which information is visible only when the widget is toggled into an "open" state.</li>
        <li>A summary or label can be provided using the summary element.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/summary">summary</a>
    <ul>
        <li>specifies a summary, caption, or legend for a details element's disclosure box.</li>
        <li>Clicking the summary element toggles the state of the parent details element open and closed.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog">dialog</a>
    <ul>
        <li>represents a dialog box or other interactive component, such as an inspector or window.</li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>layout</b></summary>
    <br/>
    <h4>sections</h4>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header">header</a>
    <ul>
        <li>represents introductory content, typically a group of introductory or navigational aids.</li>
        <li>It may contain some heading elements but also a logo, a search form, an author name, and other elements.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer">footer</a>
    <ul>
        <li>represents a footer for its nearest sectioning content or sectioning root element.</li>
        <li>A footer typically contains information about the author of the section, copyright data or links to related documents.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main">main</a>
    <ul>
        <li>represents the dominant content of the body of a document</li>
        <li>The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav">nav</a>
    <ul>
        <li>represents a section of a page whose purpose is to provide navigation links</li>
        <li>Examples: navigation sections are menus, tables of contents, and indexes</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section">section</a>
    <ul>
        <li>represents a standalone section — which doesn't have a more specific semantic element to represent it — contained within an HTML document</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article">article</a>
    <ul>
        <li>represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable</li>
        <li>Examples: a forum post, a magazine or newspaper article, or a blog entry.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside">aside</a>
    <ul>
        <li>represents a portion of a document whose content is only indirectly related to the document's main content</li>
        <li>Asides are frequently presented as sidebars or call-out boxes.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address">address</a>
    <ul>
        <li>indicates that the enclosed HTML provides contact information for a person or people, or for an organization.</li>
    </ul>
    <br />
    <h4>blocks</h4>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div">div</a>
    <ul>
        <li>It is the generic container for flow content.</li>
        <li>It has no effect on the content or layout until styled using CSS</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">blockquote</a>
    <ul>
        <li>indicates that the enclosed text is an extended quotation.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl">dl</a>
    <ul>
        <li>represents a description list.</li>
        <li>The element encloses a list of groups of terms (specified using the dt element) and descriptions (provided by dd elements).</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dd">dd</a>
    <ul>
        <li>provides the details about or the definition of the preceding term (dt) in a description list (dl).</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dt">dt</a>
    <ul>
        <li>specifies a term in a description or definition list, and as such must be used inside a dl element.</li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre">pre</a>
    <ul>
        <li>represents preformatted text which is to be presented exactly as written in the HTML file.</li>
        <li>The text is typically rendered using a non-proportional ("monospace") font.</li>
        <li>Whitespace inside this element is displayed as written</li>
    </ul>
    <br />
    <h4>table</h4>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table">table</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead">thead</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot">tfoot</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody">tbody</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption">caption</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/col">col</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/colgroup">colgroup</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr">tr</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th">th</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td">td</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>styling</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/style">style</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link">link</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>scripting</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas">canvas</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noscript">noscript</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script">script</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>embedded content</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe">iframe</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/object">object</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/param">param</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <br />
</details>

---

<details>
    <summary><b>web components</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template">template</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</details>

---

<details>
    <summary><b>experimental technology (coming soon...)</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menu">menu</a>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</details>

---

<details>
    <summary><b>vector graphics(svg)</b></summary>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web">Overview</a>
    <br/>
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Getting_Started">Getting Started</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Positions">Positions</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic_Shapes">Basic Shapes</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Paths">Paths</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Fills_and_Strokes">Fills and Strokes</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Gradients">Gradients</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Patterns">Patterns</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Texts">Texts</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic_Transformations">Basic Transformations</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Clipping_and_masking">Clipping and masking</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Other_content_in_SVG">Other content in SVG</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Filter_effects">Filter effects</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/SVG_Fonts">SVG Fonts</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/SVG_Image_Tag">SVG Image Tag</a>
    <br />
    <a href="https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Tools_for_SVG">Tools for SVG</a>
</details>

---

## For validating HTML

**using site:**

https://validator.w3.org/nu

**using chrome extension:**

https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en

---

## For Browser Support Checking

https://caniuse.com/

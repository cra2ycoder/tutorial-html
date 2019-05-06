## Image

| Property              | Description  |
| --------------------- | ------------ |
| Tag name              | img          |
| Required attributes   | src          |
| Optional attributes   | global       |
| Has close tag?        | no           |
| Is group tag?         | no           |
| Child tags            | none         |
| Element type          | inline-level |
| Has default styles?   | no           |
| Permitted parent tags | can be any   |

---

**description**

- used to render/embed a image into your document
- supported file formats:

  - JPEG/JPG
  - GIF, including animated GIFs
  - PNG
  - SVG
  - BMP

- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img

**Tag omissions**

```
none
```

**syntax**

```html
<img src="https://via.placeholder.com/150" />
```

**useful attributes**

| Property | values                 | Description                                    |
| -------- | ---------------------- | ---------------------------------------------- |
| alt      | custom value as string | alternate text when image is not loading       |
| width    | in px                  | set width                                      |
| height   | in px                  | set height                                     |
| srcset   | img url                | loads HD images based on the device resolution |
| sizes    | media query css        | resize the image based on the media query      |

- examples:

  - alt

  ```html
  <img src="https://via.placeholder.com/150" alt="placeholder image" />
  ```

  - width and height

  ```html
  <img src="https://via.placeholder.com/300" width="150px" height="150px" />
  ```

  - srcset

  ```html
  <img
    src="https://via.placeholder.com/150"
    srcset="
      https://via.placeholder.com/300 1x,
      https://via.placeholder.com/600 2x
    "
  />
  ```

  - srcset + sizes

  ```html
  <img
    src="https://via.placeholder.com/150"
    srcset="
      https://via.placeholder.com/300 1x,
      https://via.placeholder.com/600 2x
    "
    sizes="(max-width: 300px) 300w, (max-width: 400px) 320w, 50vw"
  />
  ```

---

## preview

<img src="./preview/image.png" width="480px" />

---

## examples

```html
<img
  src="https://images.pexels.com/photos/207962/pexels-photo-207962.jpeg"
  width="480px"
  alt="love tree"
/>
```

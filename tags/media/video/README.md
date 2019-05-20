## Video

| Property              | Description    |
| --------------------- | -------------- |
| Tag name              | video          |
| Required attributes   | src, controls  |
| Optional attributes   | global         |
| Has close tag?        | yes            |
| Is group tag?         | yes (optional) |
| Child tags            | source         |
| Element type          | inline         |
| Has default styles?   | yes            |
| Permitted parent tags | can be any     |

---

**description**

- used to create video player
- can be added multiple video sources using `source` tag, by doing this browser can easily pick up the working format file by default
- can be added `error` messages when the browser doesn't support the `video` tag
- comes with multiple attributes to control the player
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video

**Tag omissions**

```
none
```

**syntax**

- default

```html
<!-- default -->
<video controls src="myVideo.mp3"></video>
```

```html
<!-- default with error messages -->
<video controls src="myVideo.mp3">
  <p>
    Your browser doesn't support HTML5 audio.
  </p>
</video>
```

- adding multiple sources

```html
<!-- default -->
<video controls>
  <source src="myVideo.mp4" type="video/mp4" />
  <source src="myVideo.avi" type="video/avi" />
</video>
```

```html
<!-- default with error messages -->
<video controls>
  <source src="myVideo.mp4" type="video/mp4" />
  <source src="myVideo.avi" type="video/avi" />
  <p>
    Your browser doesn't support HTML5 video.
  </p>
</video>
```

**useful attributes**

| Property | values    | Description                                     |
| -------- | --------- | ----------------------------------------------- |
| controls | boolean   | used to toggle controls                         |
| autoplay | boolean   | used to do auto play the video                  |
| loop     | boolean   | used to loop the video                          |
| muted    | boolean   | used to mute the video                          |
| preload  | boolean   | used to preloading the video                    |
| poster   | image url | used to set first frame as a image in the video |

**NOTES**

- In some browsers (e.g. Chrome 70.0) **autoplay** is not working if no muted attribute is present.

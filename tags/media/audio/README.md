## Audio

| Property            | Description    |
| ------------------- | -------------- |
| Tag name            | audio          |
| Required attributes | src, controls  |
| Optional attributes | global         |
| Has close tag?      | yes            |
| Is group tag?       | yes (optional) |
| Child tags          | source         |
| Element type        | inline         |
| Has default styles? | yes            |

---

**description**

- used to create audio player
- can be added multiple audio sources using `source` tag, by doing this browser can easily pick up the working format file by default
- can be added `error` messages when the browser doesn't support the `audio` tag
- comes with multiple attributes to control the player
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio

**syntax**

- default

```html
<!-- default -->
<audio controls src="myAudio.mp3"></audio>
```

```html
<!-- default with error messages -->
<audio controls src="myAudio.mp3">
  <p>
    Your browser doesn't support HTML5 audio.
  </p>
</audio>
```

- adding multiple sources

```html
<!-- default -->
<audio controls>
  <source src="myAudio.mp3" type="audio/mpeg" />
  <source src="myAudio.ogg" type="audio/ogg" />
</audio>
```

```html
<!-- default with error messages -->
<audio controls>
  <source src="myAudio.mp3" type="audio/mpeg" />
  <source src="myAudio.ogg" type="audio/ogg" />
  <p>
    Your browser doesn't support HTML5 audio.
  </p>
</audio>
```

**useful attributes**

| Property | values  | Description                    |
| -------- | ------- | ------------------------------ |
| controls | boolean | used to toggle controls        |
| autoplay | boolean | used to do auto play the audio |
| loop     | boolean | used to loop the audio         |
| muted    | boolean | used to mute the audio         |
| preload  | boolean | used to preloading the audio   |

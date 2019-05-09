## Tag Name

| Property              | Description    |
| --------------------- | -------------- |
| Tag name              | audio          |
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

- used to create audio player
- can be added multiple audio sources using `source` tag, by doing this browser can easily pick up the working format file by default
- can be added `error` messages when the browser doesn't support the `audio` tag
- comes with multiple attributes to control the player
- for more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio

**Tag omissions**

```
none
```

**syntax**

- default

```html
<audio controls src="<%AUDIO_MP3_URL_GOES_HERE%>"></audio>
```

```html
<audio controls src="myAudio.mp3"></audio>
```

- adding multiple sources

```html
<audio controls>
  <source src="myAudio.mp3" type="audio/mpeg" />
  <source src="myAudio.ogg" type="audio/ogg" />
</audio>
```

- adding multiple sources with error message

```html
<audio controls>
  <source src="myAudio.mp3" type="audio/mpeg" />
  <source src="myAudio.ogg" type="audio/ogg" />
  <p>
    Your browser doesn't support HTML5 audio. Here is a
    <a href="myAudio.mp4">link to the audio</a> instead.
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

## examples

```html
<audio
  controls
  src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-6.mp3"
>
  <p>
    Your browser doesn't support HTML5 audio. Here is a
    <a href="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-6.mp3"
      >link to the audio</a
    >
    instead.
  </p>
</audio>
```

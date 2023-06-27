# Module 5: Images and Multimedia

In this module, we will explore the world of images and multimedia in HTML. We'll cover adding images using the `<img>` element, specifying image source and alternative text, image dimensions and styling, embedding videos using the `<video>` element, embedding audio files using the `<audio>` element, and setting fallback content for multimedia. Let's dive in!

### 5.1: Adding Images (`<img>`)
Images are an integral part of web design, and HTML provides the `<img>` element to display images on a webpage. Here's an example:

```html
<img src="image.jpg" alt="Description of the image">
```

In this example, the `src` attribute specifies the image source (URL or file path), and the `alt` attribute provides alternative text that is displayed if the image cannot be loaded or for accessibility purposes.

### 5.2: Specifying Image Source and Alternative Text
The `src` attribute of the `<img>` element is used to specify the source of the image. It can be a URL pointing to an image hosted on a server or a file path pointing to an image on your local system. Here's an example:

```html
<img src="image.jpg" alt="Description of the image">
```

The `alt` attribute provides a description of the image. It is important for accessibility, as it helps visually impaired users understand the content of the image or serves as a fallback if the image cannot be displayed.

### 5.3: Image Dimensions and Styling
You can control the dimensions and style of an image using CSS or HTML attributes. The `width` and `height` attributes define the dimensions of the image in pixels. Here's an example:

```html
<img src="image.jpg" alt="Description of the image" width="300" height="200">
```

Additionally, you can apply CSS styles to the `<img>` element to control its appearance, such as setting a maximum width, adding borders, or applying filters.

### 5.4: Embedding Videos (`<video>`)
HTML provides the `<video>` element to embed videos in web pages. You can specify the video source using the `src` attribute and include fallback content for unsupported browsers. Here's an example:

```html
<video src="video.mp4" controls>
    Your browser does not support the video tag.
</video>
```

In this example, the `src` attribute points to the video file, and the `controls` attribute displays the video controls (play, pause, volume, etc.). The text within the `<video>` element serves as fallback content for browsers that do not support the `<video>` element.

### 5.5: Embedding Audio Files (`<audio>`)
Similar to videos, HTML provides the `<audio>` element to embed audio files in web pages. You can specify the audio source using the `src` attribute and include fallback content. Here's an example:

```html
<audio src="audio.mp3" controls>
    Your browser does not support the audio tag.
</audio>
```

In this example, the `src` attribute points to the audio file, and the `controls` attribute displays the audio controls (play, pause, volume, etc.). The text within the `<audio>` element serves as fallback content for unsupported browsers.

### 5.6: Setting Fallback Content for Multimedia
It is important to provide fallback content for multimedia elements in case they cannot be displayed or played by the browser. The fallback content is displayed if the browser does not support the specific multimedia element. It can be text, an image, or a link to an alternative content. In the previous examples, the fallback content is included between the opening and closing tags of the multimedia elements.

### 5.7: Closing Thoughts
In Module 5, you've learned how to add images, specify image source and alternative text, control image dimensions and styling, embed videos and audio files, and set fallback content. Keep practicing these techniques to enhance the visual and multimedia aspects of your web pages. 

In the next module, we will explore lists in HTML.

<br>

<p align="left"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%204.md"><< Previous</a></p>
<p align="center"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Handout.md">Handout</p>
<p align="right"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%206.md">Next >></p>

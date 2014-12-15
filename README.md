## Interactive Panel for Indian Birds Voices
The *Interactive Panel for Indian Birds Voices* is a governement supported, real life 1m*2m panel, playing on request the voice of about 50 wild birds of North-Eastern India.

### Hardware settings

The hardware is made as below.

![IBIP](https://raw.githubusercontent.com/hugolpz/BirdsCallsPanel/master/System_p1.png)
![IBIP](https://raw.githubusercontent.com/hugolpz/BirdsCallsPanel/master/System_p3.png)

### Software settings

The current github repository contains the Single Page Application supporting the system. It's code is based on :

 - [Handlebars.js](http://handlebarsjs.com) to construct the page from json data,
 - [JQuery.js](jquery.com) for convenient interactivities such `on-click`, on `key-up` actions,
 - [Howler.js](https://github.com/goldfire/howler.js) to play audio files smoothly with fall back on html5 audio, and to allow synchroneous multiplays, more fun for kids.
 - [Keypress.js](http://dmauro.github.io/Keypress/) is need if there are more than ~45 keys needed.

While elegant, this single page application is only accessed by park's staff when turning the system on.

### Resources

* <a href="http://iviewsource.com/codingtutorials/introduction-to-javascript-templating-with-mustache-js/">Introduction to JavaScript Templating [video tutorial] with Mustache.js</a>
* <a href="http://iviewsource.com/codingtutorials/getting-started-with-javascript-object-notation-json-for-absolute-beginners/">A JSON Tutorial. Getting started with JSON using JavaScript and jQuery</a>

### License

 - [CC-BY-SA-NC (latest ed.)](https://creativecommons.org/licenses/by-sa/4.0/) -- Lopez Hugo, Boruah Soujanyaa
 - For commercial uses, please contact the authors.

<!--
NEXT post to write:
http://h5bp.github.io/
http://jsfiddle.net/YGwJ9/1/
-->

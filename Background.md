# Background for the Finish Framework

## Parts of the UI

Web/Application UI is divided into 3 main parts - look, feel, works.

How a UI looks is primarily the responsibility of the css code.

How a UI feels is primarily the responsibility of animations and transitions that are made up of both css and javascript.

How a UI works is the responsibility of the javascript code and framework.

## Theory Behind Finish

With this in mind Finish is designed to have some sane defaults (if at times opinionated) and integration for these three parts using Vue.js and Tailwindscss to accomplish them. However, you can use the Vue components independent of tailwindcss or the additional component classes Finish provides by injecting your own styles via the property. The same is true in reverse that a css component provided by Finish does not necessarily require its usage by a Finish Vue.js component. The same holds true with the provided animations and transitions. All of these components that Finish provides are hardly original to it and list inside where their inspiration comes from or any dependencies they have. What Finish does is glue them together or adjust them to allow for independent use.

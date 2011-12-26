# stream.js

stream.js is a port of the Node.js standard stream library for the browser.
The original code and tests are from Node.js, and have been modified to be browser compatible.

You can use Stream on **both sides** (server-side and client-side) if you use this.


## run the same code on both sides

You can use the Stream of Node.js on Browser.
And same code can be running on both sides :)

## how to use

```html
<script src="lib/event.js"></script>
<script src="stream.js"></script>
<script src="path/to/your/code.js"></script>
```

``stream.js`` dependes on ```[events.js](https://github.com/Jxck/events))```


## running test of this library

### browser

open ```test/index.html``` in your browser,
and see the console.
(it depends on [assert](https://github.com/Jxck/assert))

### node.js

```shell
> cd test
> ./runtest.sh
```

## license

MIT (same as Node.js)
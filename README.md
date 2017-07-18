Install
=======

```sh
npm install swi --save
```

Include
=======

```html
<script src='node_modules/swi/build/swi.js' type='text/javascript'></script>
```
...or use ES6 *import*

Use
===

```js
swi({
  // element to attach swipe to, document by default
  element: document.getElementById('my-container'),
  // on swipe left, optional
  left: function () {
    console.log('Left swipe!')
  },
  // on swipe right, optional
  right: function () {
    console.log('Right swipe!')
  },
  // on swipe up, optional
  up: function () {
    console.log('Up swipe!')
  },
  // on swipe down, optional
  down: function () {
    console.log('Down swipe!')
  }
});
```

Try it out
===========
See the Swi implementation at [Fustr.com](http://fustr.com)

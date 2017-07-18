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
swi.init({
  // element to attach swipe to, document by default
  element: document.getElementById('my-container'),
  left:  function () { console.log('Left swipe!');  }, // optional
  right: function () { console.log('Right swipe!'); }, // optional
  up:    function () { console.log('Up swipe!');    }, // optional
  down:  function () { console.log('Down swipe!');  }  // optional
});
```

Try it out
===========
See the Swi implementation at [Fustr.com](http://fustr.com)

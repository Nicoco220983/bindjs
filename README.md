# bindjs
Tiny but powerful double-binding javascript library using Object.observe

## How to use

### Browser

BindJs is based on Object.observe method, that should be available only on ES7.
For this reason, all browser do not support it yet.

For more information, click [here](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Object/observe).

### Example:

You can use BindJs by calling the global function **Bind** on a specified element of the dom.

```html
<pre>
  <html>
    <head>
      <script src="bind.js"></script>
    </head>
    <body>
      <div><input type=text ?val="myVar"></div>
      <div>?{myVar}</div>
      <script>
        Bind(document.body, {myVar:"This is my binded variable."})
      </script>
    </body>
  </html>
</pre>
```

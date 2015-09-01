# bindjs
Tiny but powerful double-binding javascript library using Object.observe

# How to use

```html
<pre>
  <html>
    <head>
      <script src="bind.js"></script>
    </head>
    <body>
      <p id="bindMe">?{myText}</p>
      <script>
        Bind(document.querySelector("#bindMe"), {myText:"This is my text."})
      </script>
    </body>
  </html>
</pre>
```

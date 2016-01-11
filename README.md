# Navbar - minimal navigation script
This is a script that most web developers need for a quick site navigation, built with Native Javascript and supported on all major browsers as well as legacy browsers starting with IE8.

# Demo
Download the package and check the demo folder, an online demo will be available later.

# Features
* opens submenus on `mouseenter`
* hides submenus on `mouseleave`
* cross-browser supported

# Usage
Link the required CSS in your document `&lt;head&gt;` tag
```html
<link href="../dist/navbar.css" rel="stylesheet">
```

Link the required JS in your document  `&lt;body&gt;` tag
```html
<script src="../dist/navbar.js"></script>
```

Initiate the function for your elements at the end of your `&lt;body&gt;` tag
```javascript
<script>
var myMenu = new Navbar('selector');
</script>
```

# License
MIT License

# useful.polyfills.js: Polyfill Library

A library of useful polyfills to ease working with HTML5 in legacy environments.

Try the <a href="http://www.woollymittens.nl/useful/default.php?url=polyfills">tests</a>.

## How to include the script

This include can be added to the header or placed inline before the script is invoked.

```html
<script src="./js/polyfills.min.js"></script>
```

The following private functions are run.

## How to control the script

### html5

```javascript
	polyfills.html5();
```

Add support for HTML5 elements in Internet Explorer 8 and lower.

### arrayIndexOf

```javascript
	polyfills.arrayIndexOf();
```

Adds support for array.indexOf.

### querySelectorAll

```javascript
	polyfills.querySelectorAll();
```

Adds support for document.querySelectorAll (1).

### addEventListener

```javascript
	polyfills.addEventListener();
```

Adds support for element.addEventListener, element.removeEventListener and element.dispatchEvent (2).

### consoleLog

```javascript
	polyfills.consoleLog();
```

Adds support for console.log.

### objectCreate

```javascript
	polyfills.objectCreate();
```

Adds support for object.create (3).

### stringTrim

```javascript
	polyfills.stringTrim();
```

Adds support for string.trim, string.ltrim, string.rtrim and string.fulltrim (4).

## Prerequisites

To concatenate and minify the script yourself, the following prerequisites are required:
+ https://github.com/WoollyMittens/useful-polyfills

## Sources

1. Connolley, Paul. "IE7 querySelectorAll polyfill", https://gist.github.com/connrs/2724353
2. Neal, Jonathan. "Polyfill the EventListener interface in IE8", https://gist.github.com/jonathantneal/3748027
3. Gasparini, Ryan. "HTML5 API Polyfills", https://gist.github.com/rxgx/1597825
4. Perelman, Eli. "String.prototype.trim polyfill for 140byt.es", https://gist.github.com/eliperelman/1035982

## License
This work is licensed under a Creative Commons Attribution 3.0 Unported License. The latest version of this and other scripts by the same author can be found at http://www.woollymittens.nl/

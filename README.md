# polyfills.js: Polyfill Library

*DEPRICATION WARNING: the functionality in this script has been superceeded / trivialised by updated web standards.*

A library of useful polyfills to ease working with HTML5 in legacy environments.

## How to include the script

This include can be added to the header or placed inline before the script is invoked.

```html
<script src="js/polyfills.js"></script>
```

Or use [Require.js](https://requirejs.org/).

```js
requirejs([
	'js/polyfills.js'
], function(polyfills) {
	...
});
```

Or use imported as a component in existing projects.

```js
@import {polyfills} from "js/polyfills.js');
```

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

### localStorage

```javascript
	polyfills.localStorage();
```

Adds support for localStorage.getItem, localStorage.key, localStorage.setItem, localStorage.length, localStorage.removeItem (5).

## Sources

1. Connolley, Paul. "IE7 querySelectorAll polyfill", https://gist.github.com/connrs/2724353
2. Neal, Jonathan. "Polyfill the EventListener interface in IE8", https://gist.github.com/jonathantneal/3748027
3. Gasparini, Ryan. "HTML5 API Polyfills", https://gist.github.com/rxgx/1597825
4. Perelman, Eli. "String.prototype.trim polyfill for 140byt.es", https://gist.github.com/eliperelman/1035982
5. Mozilla Developer Network. "DOM Storage guide", https://developer.mozilla.org/en/docs/Web/Guide/API/DOM/Storage

## License

This work is licensed under a [MIT License](https://opensource.org/licenses/MIT). The latest version of this and other scripts by the same author can be found on [Github](https://github.com/WoollyMittens).

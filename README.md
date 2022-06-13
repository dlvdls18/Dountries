# Dountries

![Dountries](dountries.png)

JSON and JavaScript Array of All Countries

# Installation

```html
<script src="https://cdn.jsdelivr.net/gh/dlvdls18/Dountries@main/src/dountries.js"></script>
```

or download the [JSON](https://cdn.jsdelivr.net/gh/dlvdls18/Dountries@main/src/dountries.json) file.

# Usage

`Dountries.js`

```js
// returns new array of countries
new Dountries();
```

`Dountries.json`

```js
async function Dountries() {
  var f = await fetch("path/to/dountries.json");
  var t = await f.text();
  return JSON.parse(t);
}
```

```js
(async function() {
  var c = await Dountries();
  // returns new array of countries
  console.log(c);
})();
```

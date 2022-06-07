# Dountries
JSON and JavaScript Array of All Countries

# Installation

## JavaScript


```html
<script src="https://cdn.jsdelivr.net/gh/dlvdls18/Dountries@blob/dountries.js"></script>
```

```js
console.log(new Dountries());
```

## JSON

```js
async getDountriesJSON() {
  var f = await fetch("https://cdn.jsdelivr.net/gh/dlvdls18/Dountries@blob/dountries.json");
  return await JSON.parse(f.text());
}
```

```js
console.log(getDountriesJSON());
```

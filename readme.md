## 💧 plop-date

<a href="https://npmjs.com/package/plop-date">
    <img alt="npm" src="https://img.shields.io/npm/v/plop-date.svg?style=flat-square">
</a>

<a href="https://npmjs.com/package/plop-date">
    <img alt="npm" src="https://img.shields.io/npm/dt/plop-date?style=flat-square">
</a>

_A [plop][plop] helper to grab the current date._

### 📦 Installation

This package is installable from [npm][npm].

```bash
npm install --save-dev plop-date
```

### 🥑 Usage

Before you can use the `plop-date`, you have to load it into the `plop` object.

```javascript
plop.load("plop-date")
```

Once loaded, you now have access the following helpers.

#### `date`

Creates a formatted date.

**helper**

```handlebars
{{date}}
```

**output**

```javascript
"2020-07-10"
```

#### `timestamp`

Creates a raw timestamp.

**helper**

```handlebars
{{timestamp}}
```

**output**

```javascript
"20241111223217"
```

### ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]  
🙋🏼‍♂️ use my [ama][ama] or [twitter][twitter] to ask any other questions

[plop]: https://plopjs.com
[npm]: https://npmjs.com
[bradgarropy]: https://bradgarropy.com
[issues]: https://github.com/bradgarropy/plop-helper-date/issues
[twitter]: https://twitter.com/bradgarropy
[ama]: https://github.com/bradgarropy/ama

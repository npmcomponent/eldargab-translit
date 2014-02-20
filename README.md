*This repository is a mirror of the [component](http://component.io) module [eldargab/translit](http://github.com/eldargab/translit). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eldargab-translit`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# translit

Text transliteration util.

## Installation

via component

```
component install eldargab/translit
```

via npm

```
npm install translit
```

## Example

```javascript
var translit = require('translit')({
  'И': 'I',
  'ж': 'zh',
  'е': 'e'
  'в': 'v',
  'c': 's',
  'к': 'k'
})
translit('Ижевск') //=> Izhevsk
```

Or vice versa

```javascript
var translit = require('translit')({
  'I': 'И',
  'zh': 'ж'
})
translit('Izh') //=> Иж
```

## Related

  * [translit-russian](https://github.com/eldargab/translit-russian) - Russian transliteration map

## License

MIT

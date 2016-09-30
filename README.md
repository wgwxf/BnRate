# bn-rate
---

React Rate Component

[![NPM version][npm-image]][npm-url]

[npm-image]: http://img.shields.io/npm/v/bn-rate.svg?style=flat-square
[npm-url]: http://npmjs.org/package/bn-rate

## Screenshots

<img src="https://img.alicdn.com/tps/TB1ijlpLVXXXXb8XpXXXXXXXXXX-466-172.png" width="288"/>


## Development

```
npm install
npm start
```

## Example

http://localhost:8000/examples/


## install


[![bn-rate](https://nodei.co/npm/bn-rate.png)](https://npmjs.org/package/bn-rate)


## Usage

```js
var Rate = require('bn-rate');
var React = require('react');
React.render(<Rate />, container);
```

## API

### props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 50px;">type</th>
        <th style="width: 50px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>count</td>
          <td>number</td>
          <td>5</td>
          <td>star numbers</td>
        </tr>
        <tr>
          <td>value</td>
          <td>number</td>
          <td></td>
          <td>controlled value</td>
        </tr>
        <tr>
          <td>defaultValue</td>
          <td>number</td>
          <td>0</td>
          <td>initial value</td>
        </tr>
        <tr>
          <td>allowHalf</td>
          <td>bool</td>
          <td>false</td>
          <td>support half star</td>
        </tr>
        <tr>
          <td>style</td>
          <td>object</td>
          <td>{}</td>
          <td></td>
        </tr>
        <tr>
          <td>onChange</td>
          <td>function(value: Number)</td>
          <td></td>
          <td>`onChange` will be triggered when click.</td>
        </tr>
        <tr>
          <td><font color="red">onHover<font/></td>
          <td>function(value: Number)</td>
          <td></td>
          <td>`onHover` will be triggered when hover.</td>
        </tr>
    </tbody>
</table>


## Test Case

```
npm test
npm run chrome-test
```

## Coverage

```
npm run coverage
```

open coverage/ dir

## License

bn-rate is released under the MIT license.

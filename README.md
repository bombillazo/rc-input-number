# rc-input-number

Input number control.

[![NPM version][npm-image]][npm-url]
[![npm download][download-image]][download-url]
[![build status][github-actions-image]][github-actions-url]
[![Codecov][codecov-image]][codecov-url]
[![bundle size][bundlephobia-image]][bundlephobia-url]
[![dumi][dumi-image]][dumi-url]

[npm-image]: http://img.shields.io/npm/v/rc-input-number.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rc-input-number
[travis-image]: https://img.shields.io/travis/react-component/input-number/master?style=flat-square
[travis-url]: https://travis-ci.com/react-component/input-number
[github-actions-image]: https://github.com/react-component/input-number/actions/workflows/react-component-ci.yml/badge.svg
[github-actions-url]: https://github.com/react-component/input-number/actions/workflows/react-component-ci.yml
[codecov-image]: https://img.shields.io/codecov/c/github/react-component/input-number/master.svg?style=flat-square
[codecov-url]: https://app.codecov.io/gh/react-component/input-number
[david-url]: https://david-dm.org/react-component/input-number
[david-image]: https://david-dm.org/react-component/input-number/status.svg?style=flat-square
[david-dev-url]: https://david-dm.org/react-component/input-number?type=dev
[david-dev-image]: https://david-dm.org/react-component/input-number/dev-status.svg?style=flat-square
[download-image]: https://img.shields.io/npm/dm/rc-input-number.svg?style=flat-square
[download-url]: https://npmjs.org/package/rc-input-number
[bundlephobia-url]: https://bundlephobia.com/package/rc-input-number
[bundlephobia-image]: https://badgen.net/bundlephobia/minzip/rc-input-number
[dumi-url]: https://github.com/umijs/dumi
[dumi-image]: https://img.shields.io/badge/docs%20by-dumi-blue?style=flat-square

## Screenshots

<img src="https://user-images.githubusercontent.com/507615/83162463-61414a80-a13c-11ea-9420-971f8697d490.png" width="288"/>

## Install

[![rc-input-number](https://nodei.co/npm/rc-input-number.png)](https://npmjs.org/package/rc-input-number)

## Usage

```js
import InputNumber from 'rc-input-number';

export default () => <InputNumber defaultValue={10} />;
```

## Development

```
npm install
npm start
```

## Example

http://127.0.0.1:8000/examples/

online example: https://input-number.vercel.app/

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
          <td>prefixCls</td>
          <td>string</td>
          <td>rc-input-number</td>
          <td>Specifies the class prefix</td>
        </tr>
        <tr>
          <td>min</td>
          <td>Number</td>
          <td></td>
          <td>Specifies the minimum value</td>
        </tr>
        <tr>
          <td>onClick</td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>placeholder</td>
          <td>string</td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>max</td>
          <td>Number</td>
          <td></td>
          <td>Specifies the maximum value</td>
        </tr>
        <tr>
          <td>step</td>
          <td>Number or String</td>
          <td>1</td>
          <td>Specifies the legal number intervals</td>
        </tr>
        <tr>
          <td>precision</td>
          <td>Number</td>
          <td></td>
          <td>Specifies the precision length of value</td>
        </tr>
        <tr>
          <td>disabled</td>
          <td>Boolean</td>
          <td>false</td>
          <td>Specifies that an InputNumber should be disabled</td>
        </tr>
        <tr>
          <td>required</td>
          <td>Boolean</td>
          <td>false</td>
          <td>Specifies that an InputNumber is required</td>
        </tr>
        <tr>
          <td>autoFocus</td>
          <td>Boolean</td>
          <td>false</td>
          <td>Specifies that an InputNumber should automatically get focus when the page loads</td>
        </tr>
        <tr>
          <td>readOnly</td>
          <td>Boolean</td>
          <td>false</td>
          <td>Specifies that an InputNumber is read only </td>
        </tr>
        <tr>
          <td>controls</td>
          <td>Boolean</td>
          <td>true</td>
          <td>Whether to enable the control buttons</td>
        </tr>
        <tr>
          <td>name</td>
          <td>String</td>
          <td></td>
          <td>Specifies the name of an InputNumber</td>
        </tr>
        <tr>
          <td>id</td>
          <td>String</td>
          <td></td>
          <td>Specifies the id of an InputNumber</td>
        </tr>
        <tr>
          <td>value</td>
          <td>Number</td>
          <td></td>
          <td>Specifies the value of an InputNumber</td>
        </tr>
        <tr>
          <td>defaultValue</td>
          <td>Number</td>
          <td></td>
          <td>Specifies the defaultValue of an InputNumber</td>
        </tr>
        <tr>
          <td>onChange</td>
          <td>Function</td>
          <td></td>
          <td>Called when value of an InputNumber changed</td>
        </tr>
        <tr>
            <td>onBlur</td>
            <td>Function</td>
            <td></td>
            <td>Called when user leaves an input field</td>
        </tr>
        <tr>
          <td>onPressEnter</td>
          <td>Function</td>
          <td></td>
          <td>The callback function that is triggered when Enter key is pressed.</td>
        </tr>
        <tr>
          <td>onFocus</td>
          <td>Function</td>
          <td></td>
          <td>Called when an element gets focus</td>
        </tr>
        <tr>
          <td>style</td>
          <td>Object</td>
          <td></td>
          <td>root style. such as {width:100}</td>
        </tr>
        <tr>
          <td>upHandler</td>
          <td>React.Node</td>
          <td></td>
          <td>custom the up step element</td>
        </tr>
        <tr>
          <td>downHandler</td>
          <td>React.Node</td>
          <td></td>
          <td>custom the down step element</td>
        </tr>
        <tr>
          <td>formatter</td>
          <td>(value: number|string): displayValue: string</td>
          <td></td>
          <td>Specifies the format of the value presented</td>
        </tr>
        <tr>
          <td>parser</td>
          <td>(displayValue: string) => value: number</td>
          <td>`input => input.replace(/[^\w\.-]*/g, '')`</td>
          <td>Specifies the value extracted from formatter</td>
        </tr>
        <tr>
          <td>pattern</td>
          <td>string</td>
          <td></td>
          <td>Specifies a regex pattern to be added to the input number element - useful for forcing iOS to open the number pad instead of the normal keyboard (supply a regex of "\d*" to do this) or form validation</td>
        </tr>
        <tr>
          <td>decimalSeparator</td>
          <td>string</td>
          <td></td>
          <td>Specifies the decimal separator</td>
        </tr>
        <tr>
          <td>inputMode</td>
          <td>string</td>
          <td></td>
          <td>Specifies the inputmode of input</td>
        </tr>
        <tr>
          <td>wheel</td>
          <td>Boolean</td>
          <td>true</td>
          <td>Allows changing value with mouse wheel</td>
        </tr>
    </tbody>
</table>

## Keyboard Navigation
* When you hit the <kbd>⬆</kbd> or <kbd>⬇</kbd> key, the input value will be increased or decreased by `step`
* With the <kbd>Shift</kbd> key (<kbd>Shift+⬆</kbd>, <kbd>Shift+⬇</kbd>), the input value will be changed by `10 * step`
* With the <kbd>Ctrl</kbd> or <kbd>⌘</kbd> key (<kbd>Ctrl+⬆</kbd> or <kbd>⌘+⬆</kbd> or <kbd>Ctrl+⬇</kbd> or <kbd>⌘+⬇</kbd> ), the input value will be changed by `0.1 * step`

## Mouse Wheel
* When you scroll up or down, the input value will be increased or decreased by `step`
* Scrolling with the <kbd>Shift</kbd> key, the input value will be changed by `10 * step`

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

rc-input-number is released under the MIT license.

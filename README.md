# GTIN [Global Trade Item Number] Generator

A small utility that generates random GTIN14 and Generates check digit for the input

## Installation

```sh
$ npm install gtin-generator --save
```

## API

```js
var gtin = require('gtin-generator')
```

### gtin.getGTIN()

Returns a random GTIN-14 with vaild check valid

### gtin.getGTIN(num)

Returns calculated check digit for the number provided. Throws error if the argument is not a valid number.


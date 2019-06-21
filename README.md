# Editorjs Converter

This converts editorjs json data into HTML and MD

# Installation

```
npm install editorjs-converter
```

# Usage

## HTML

### Example 1

```
const converter = require('editorjs-converter');
const data = {}
const convertedData = converter(data, "html");
console.log(convertedData)
```

### Example 2

```
const converter = require('editorjs-converter');
const data = {}
const convertedData = converter(data).toHTML();
console.log(convertedData)

```

## MarkDown

### Example 1

```
const converter = require('editorjs-converter');
const data = {}
const convertedData = converter(data, "md");
console.log(convertedData)
```

### Example 2

```
const converter = require('editorjs-converter');
const data = {}
const convertedData = converter(data).toMD();
console.log(convertedData)

```

# Author

[Oyetoke Toby](http://citguru.github.io) <oyetoketoby80@gmail.com>

Support me on: [Patreon](http://patreon.com/oyetoketoby)

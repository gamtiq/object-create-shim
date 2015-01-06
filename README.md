# object-create-shim

Simple shim for ECMAScript 5 `Object.create`

## Installation

Install [Component](https://github.com/componentjs/component):

    npm install -g component

Then:

    component install gamtiq/object-create-shim

## Usage

    var create = require("object-create-shim");
    ...
    var obj1 = Object.create(someParent1);
    var obj2 = create(someParent2);

## Licence

MIT


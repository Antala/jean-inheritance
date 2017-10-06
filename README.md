## Description

Provides functionality for inheriting constructor and prototype values and methods

## Code Example

```js
require(["path/to/Inheritance"], function(Inheritance){
    
});
```

## Installation

`npm install jean-inheritance --save --legacy-bundling`

## API Reference

### Inheritance.inheritConstructor(testator, instance, options) 

Inherits constructor values

**Parameters**

- **testator**: `function` - Testator constructor which must be called for inheritance

- **instance**: `Object` - this value of the inheritor

- **options**: `Any[] | Object` - Options, which will be passed to the testator

**Returns**:
- `Boolean` - True if constructor values are inherited, false otherwise


### inheritPrototype(inheritor, testator) 

Inherits prototype from testator to inheritor

**Parameters**

- **inheritor**: `function` - The method which will be inherited from testator

- **testator**: `function` - The method which pass its prototype to inheritor

**Returns**
- `Boolean` - True if prototype values are inherited, false otherwise

## Tests

- Open spec/spec-runner.html in browser to see the test cases.

## License

MIT
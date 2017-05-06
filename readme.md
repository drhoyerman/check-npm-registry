This is a package which can check the fastest npm registry.

## Usage

```js
import checkRegistry from 'check-npm-registry';

checkRegistry()
  .then(registry => console.log(registry));


// param: stirng or array

checkRegistry('your_registry_url')

checkRegistry([your_registry_url_array])

```
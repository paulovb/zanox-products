
zanox-products
=============

Simplified version of the API Zanox to provide its products. Version for NodeJS.

## Usage examples

Full example:

```javascript
var zanox = require('zanox-products');

zanox({keywords: 'search...'})
    .id(connectionID...)
    .searchType('phrase')
    .country('BR')
    .page(1)
    .limit(10)
    .done(function (err, products) {
	...
    });
```


## LICENSE

The MIT License (MIT)
Copyright (c) 2014 Paulo Vítor Bischof, Based on the "zanox-lookup" of Adam Rudd.

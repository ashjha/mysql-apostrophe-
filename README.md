# mysql-apostrophe 


## Example

``` js

var apostrophe = require("mysql-apostrophe");

var express = require('express');
var app = express();
var bodyParser = require('body-parser')

app.use(bodyParser.json());
app.use(bodyParser.urlencoded({extended:true}));

app.use(apostrophe); //must be after bodyparser


```

## Install

``` cli
npm i mysql-apostrophe
```

## License

MIT

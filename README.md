# WQueryBuilder [![Build Status](https://travis-ci.org/webbers/wquerybuilder.svg?branch=master)](https://travis-ci.org/webbers/wquerybuilder) [![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/renanborgez/wquerybuilder/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
A good alternative to create SQL strings using a browser, you can see a demo here: [DEMO](http://renanborges.com/wquerybuilder/demo/)


## Usage
```javascript
<script>
    // Calling query builder
    $(function () {
        var obj = { // Property names is your tables and in array yours columns
            Users: ["Id", "FullName", "Username", "Email", "Location", "Country", "ZIP", "Phone"],
            Products: ["Id", "Name", "Type", "Weight", "Size", "Factory", "Height", "Area"],
            Storage: ["ProductId", "Qtd"],
        };
        $("#querybuilder").wquerybuilder({ data: obj });
    });
  </script>
```
## Features

* Use [Jquery](https://github.com/jquery/jquery)
* Use [Squeljs](https://github.com/hiddentao/squel)
* Support MySql, Postgre, Oracle and MSSQL
* Chrome, Firefox and IE8+ Support
* Easy to configure

## Next features

* Bootstrap theme
* Support for Delete syntax

## Last updates

* 11/11/2014 - Removed Underscore.js depency


# Emulsion/Platform

This is the core repository for the CMS. The admin is fully translatable in English and French by default.

![](https://i.cloudup.com/WcLe-ORql4.thumb.png)

## Requirements

* PHP 5.4+
* Access to [Cartalyst Sentinel](https://cartalyst.com/manual/sentinel) package

## Getting started

### Install Platform

```
composer create-project emulsion/platform your-project-name --prefer-dist --stability=dev
```

### Configure your database settings

Configure your development settings in `config/development`.


### Create .env environment file

Create a `.env` file at the project root. It needs to contain the following key.

```
APP_ENV=development
```

### Run install command

Run the installation command to run the migrations and seeds. This will as well ask you information to create an admin account.
```
php artisan platform:install
```

### Enjoy

You can now login on `/backend` with your email and password asked during the install command.


## Documentation

You can read the documentation on its specific [github repository](https://github.com/nWidart-Modules/Documentation).


## Development


For manually adding the subtrees please refer to the [install as subtree](https://github.com/nWidart-Modules/Documentation/blob/master/Installation/module-installation-as-subtree.md) documentation.



## License (MIT)

Copyright (c) 2013 [Nicolas Widart](http://www.nicolaswidart.com) , n.widart@gmail.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# <PROJECT TITLE>

## Installation

The preferred installation method is via composer. You can add
the library as a dependency via:

```
composer require <AUTHOR>/<PROJECT NAME>
```

li₃ plugins must be registered within your application bootstrap phase 
as they use a different (faster) autoloader. 

```php
Libraries::add('<PROJECT NAME>')
```

The official manual has more information on 
[how to register the plugin](http://li3.me/docs/manual/installation/plugins.md) 
with the app or use alternative installation methods (i.e. via GIT).

## Usage
n/a

## Copyright & License

Copyright <YEAR> <AUTHOR>. All rights reserved. This library
is distributed under the terms of the BSD 3-Clause License. The
full license text can be found in the LICENSE.txt file.

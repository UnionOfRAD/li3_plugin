# <PROJECT TITLE>
## li₃ plugin

## Usage

## Installation

The preferred installation method is via composer. You can add
the library as a dependency via:

```
composer require <AUTHOR>/<PROJECT NAME>
```

li₃ libraries must be registered within your application bootstrap phase 
as they use a different (faster) autoloader. 

```php
Libraries::add('<PROJECT NAME>')
```

## Copyright & License

Copyright <YEAR> <AUTHOR>. All rights reserved. This library
is distributed under the terms of the BSD 3-Clause License. The
full license text can be found in the LICENSE.txt file.

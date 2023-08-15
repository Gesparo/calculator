# Why do you need this?

This package helps you to make simple arithmetic operations with OOP approach.

# Installation

```bash
composer require gesparo/calculator
```

# Usage
To create a new instance of Calculator class, use the following code:
```php
use Gesparo\Calculator\Calculator;

$calc = new Calculator();
```

Then you can make simple arithmetic operations:
```php
$calc->add(1, 2); // 3
$calc->subtract(1, 2); // -1
```
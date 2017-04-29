# test-highlighting-override

Testing code highlight override using .gitattributes.

This should work now.

It does.

## PHP Snippet known to break

```php
$foo = 123;
$bar = function($foo) {
  return $foo.$foo.(1+2);
}
$baz = array('one');
$baz['two'] = FALSE;
```

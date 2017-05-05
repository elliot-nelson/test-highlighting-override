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

## With php Tags

```php
<?php
	require_once "support/http.php";

	$url = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
	$parts = HTTP::ExtractURL($url);
	if ($parts["host"] === "www.youtube.com" && isset($parts["queryvars"]["v"]))
	{
		$videoid = $parts["queryvars"]["v"];
		if ($videoid === "dQw4w9WgXcQ")  echo "You're going to love this!";
	}
?>
```

# Zttp

Zttp is really simple Guzzle wrapper designed to provide a really pleasant development experience for most common use cases.

If you need more functionality, just use Guzzle :)

Real documentation is in the works, but for now [read the tests](https://github.com/kitetail/zttp/blob/master/tests/ZttpTest.php).

```php
$response = Zttp::withHeaders(['Fancy' => 'Pants'])->post($url, [
    'foo' => 'bar',
    'baz' => 'qux',
]);

$response->json();
// => [
//  'whatever' => 'was returned',
// ];
```


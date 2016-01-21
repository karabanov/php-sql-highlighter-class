Highlighter class - makes your SQL containing apps more beautiful.

As of the name - it is simple.

'foo' will be coloured red, but 'f.o.o' will be with gray dots.

LEFT and RIGHT are gray, no matter they could be used as functions - left(foobar, 3).

Sample usage:

```

<?
$hl = new Highlighter;
$sql = "SELECT 'foo' FROM dual";
echo $hl->highlight($sql);
?>
```
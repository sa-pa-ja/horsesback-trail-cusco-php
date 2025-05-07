# Basic syntax

## php **tags**

When PHP processes a file, it recognizes the opening and closing tags, `<?php` and `?php` to define the boundaries of PHP code execution.

PHP also includes the short tag `<?=`, which is shorthand for `<?php` echo.

**Example #1 opening and Closing tags**

```php
<?php
echo "If you want to serve PHP code in XHTML or XML documents, use these tags";
?>

// You can use the short echo tag to

<?=
"Print this string"
?>
```

> **Note**
> As short tags can be disabled it is recommended to only use the normal tags (`<?php?>` and `<?=?>`) to maximize compatibility.



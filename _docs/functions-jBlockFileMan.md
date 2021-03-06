---
title: "jBlockFileMan"
permalink: /functions/jblockfileman
excerpt: "jBlockFileMan."
last_modified_at: 2018-03-19T16:28:04-05:00
toc: false
---

Upload a file with specific type (`$_type`) from a specific path (`$_path`) and after a parsing returns a string.<br>
```java
void jBlockFile( String $_path, String $_type, Array $_parameters )
```

## Parameters
* **$_path**: The path of the file you want to open.
* **$_type**: The type of the file contents, could be html, pug, jade, twig, md.
* **$_parameters**: Is an array of content for pug and twig stuff.

## Return Values
Return a string.

## Examples
```php
<?php
$temp = jBlockFileMan("bundles/views/file1.txt", "md"); // string with some markdown
?>
```

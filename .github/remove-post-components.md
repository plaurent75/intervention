# remove-post-components

### Description
Remove WordPress support for post component/s.

### Usage
&#10003; Supports multiple instances.
```php
intervention('remove-post-components', $components(string|array));
```

### Defaults
$components: `author, excerpt, trackbacks, custom-fields, comments`

### Options
$components: `all, editor, author, excerpt, trackbacks, custom-fields, comments, slug, revisions, thumbnail`

### Examples
```php
intervention('remove-post-components');
// Removes default post components.

intervention('remove-post-components', 'author');
// Removes post component author.

intervention('remove-post-components', ['author', 'custom-fields']);
// Removes post components author and custom-fields.
```

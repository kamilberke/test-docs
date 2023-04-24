# Home

## Introduction

This is how to get started with the plugin.

```php
$users = new WP_Query(array(
    'post_type' => 'user',
    'posts_per_page' => -1
));
```
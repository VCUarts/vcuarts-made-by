# Benson

Simple Angular integration with the WP REST API. Takes an endpoint and binds it to scope so you can use mustache in your templates and the WordPress HTML editor.

## Description 

Benson accepts a local endpoint from your wordpress install, binds the result to scope and makes that available to your templates and the WordPress HTML editor.

Supports ACF.

## Installation 

1. Upload benson to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add an endpoint to a post or page

## Frequently Asked Questions 

### How do I sanitize html? 

use ng-bind-html like this
```
<div ng-bind-html="content"></div>
```

## Changelog 
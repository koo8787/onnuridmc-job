# onnuridmc-job

## User Assistants on Eclipse
Preferences > PHP > Editor > Templates
`New...`
* `last_query`
```php
echo "<pre>"; $$this->db->last_query(); echo "</pre>";
```
* `print_last_query`
```php
			echo "<pre>";
			var_dump( ${cursor} );
			echo "</pre>";
```

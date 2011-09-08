## Smarty CI Helper
Provides the ability to call CodeIgniter helper with Smarty syntax. 

## Example Usage
```html
<a href="{ci name='url' function='base_url'}">Site Base URL</a>
```
The above example will call the base_url() function from the URL helper of CodeIgniter, and thus produce result that look something like this

```html
<a href="http://domain.tld/">Site Base URL</a>
```
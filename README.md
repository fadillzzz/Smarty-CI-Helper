##Smarty CI Helper
Provides the ability to call CodeIgniter helper with Smarty syntax. 

##Installation
Place this file inside the smarty plugins directory.

##Example Usage
```html
{ci helper='helper_name' function='function_name' param1='function_param1' param2='function_param2'}
```

```html
<a href="{ci helper='url' function='base_url'}">Site Base URL</a>
```
The above example will call the base_url() function from the URL helper of CodeIgniter, and thus produce result that look something like this

```html
<a href="http://domain.tld/">Site Base URL</a>
```
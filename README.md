## Paste CloudFlare

This project is forked from the Paste project, which simply changes this line of code

```php
$_SERVER['REMOTE_ADDR']
```

to

```php
$_SERVER["HTTP_CF_CONNECTING_IP"]
```
Which grabs from cloudflare, do not use this fork if your not using cloudflare.
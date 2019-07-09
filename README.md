# nginx-junk-reducer
Block recurrent attackers with Nginx.

This file was originally made to reduce junk in our Laravel application access logs.


## Warning
This config file might not be compatible with your application. Read junk-reducer file before installing.

Do not use with applications below:
- Wordpress
- PhpMyAdmin
- ASP.NET


## Installation

1. Copy junk-reducer file in /etc/nginx/
2. Add in your server section:
```bash
server{
  ...
  ...
  ...
  include junk-reducer;
  
  ...
}
```
3. Reload Nginx

# seafile

## Email configuration

Check official documentation: https://manual.seafile.com/config/sending_email.html

To enable email sending, deploy and add the following lines to `seafile-data-vol/conf/seahub_settings.py` file:

```
EMAIL_USE_TLS = True
EMAIL_HOST = 'mail'  # smpt server
EMAIL_HOST_USER = 'smtp'  # username (and domain)
EMAIL_HOST_PASSWORD = 'password'  # password
EMAIL_PORT = 25
DEFAULT_FROM_EMAIL = 'seafile@domain'
SERVER_EMAIL = 'seafile@domain'
NOTIFY_ADMIN_AFTER_REGISTRATION = True
```

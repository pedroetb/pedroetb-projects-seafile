# seafile

## Email configuration

Check official documentation: <https://manual.seafile.com/config/sending_email>

To enable email sending, deploy and add the following lines to `seafile-mc-conf-vol/seahub_settings.py` file:

```python
EMAIL_USE_TLS = False
EMAIL_HOST = 'postfix'
EMAIL_HOST_USER = ''
EMAIL_HOST_PASSWORD = ''
EMAIL_PORT = 25
DEFAULT_FROM_EMAIL = 'seafile@change.me'
SERVER_EMAIL = 'seafile@change.me'
NOTIFY_ADMIN_AFTER_REGISTRATION = True
```

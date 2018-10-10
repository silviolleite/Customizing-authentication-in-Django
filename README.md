# Customizing-authentication-in-Django
Customizing authentication in Django to login with username or email.

1. Copy the backends.py to your Django app
2. Add this list in settings.py
```python
  AUTHENTICATION_BACKENDS = ['yourapp.backends.EmailOrUsernameModelBackend']
```
3. It's ready! Now you can authenticate in Django with username or email.

<!-- markdownlint-disable -->

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L0"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

# <kbd>module</kbd> `users`






---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L9"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>class</kbd> `Users`




<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L12"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `__init__`

```python
__init__(url: str)
```








---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L15"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `create`

```python
create(user: dict, token: str = '')
```

Registers new user account given email and password. New account will be uniquely identified by its email address. 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L131"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `disable`

```python
disable(user_id: str, user_token: str)
```

Disables an enabled user account for a given user ID. 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L115"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `enable`

```python
enable(user_id: str, user_token: str)
```

Enables a disabled user account for a given user ID. 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L46"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `get`

```python
get(user_id: str, token: str)
```

Gets a user information 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L62"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `get_all`

```python
get_all(query_params: dict, user_token: str)
```

Retrieves a list of users 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L33"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `login`

```python
login(user: dict)
```

Generates an access token when provided with proper credentials. 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L79"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `update`

```python
update(user: dict, user_token: str)
```

Updates info on currently logged in user. Info is updated using authorization user_token 

---

<a href="https://github.com/mainflux/sdk-py/blob/main/mainflux/users.py#L97"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>method</kbd> `update_password`

```python
update_password(old_secret: str, new_secret: str, user_token: str)
```

Changes user password 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._

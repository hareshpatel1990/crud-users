[![Build Status](https://img.shields.io/travis/FriendsOfCake/crud-users/master.svg?style=flat-square)](https://travis-ci.org/FriendsOfCake/crud-users)
[![Total Downloads](https://img.shields.io/packagist/dt/FriendsOfCake/crud-users.svg?style=flat-square)](https://packagist.org/packages/FriendsOfCake/crud-users)
[![Latest Stable Version](https://img.shields.io/packagist/v/FriendsOfCake/crud-users.svg?style=flat-square)](https://packagist.org/packages/FriendsOfCake/crud-users)

# Crud Users

## Features

- LoginAction (beforeLogin, afterLogin, beforeRender), use it:

```
$this->Crud->mapAction('login', 'CrudUsers.Login');
```

- LogoutAction (beforeLogout, afterLogout)

```
$this->Crud->mapAction('logout', 'CrudUsers.Logout');
```

- RegisterAction (beforeRegister, afterRegister)

```
$this->Crud->mapAction('register', 'CrudUsers.Register');
```

- ForgotPasswordAction (beforeForgotPassword, afterForgotPassword)

```
$this->Crud->mapAction('forgotPassword', 'CrudUsers.ForgotPassword');
```

- ResetPasswordAction (beforeRender, beforeFind, afterFind, verifyToken, beforeSave, afterSave, afterResetPassword)

```
$this->Crud->mapAction('resetPassword', 'CrudUsers.ResetPassword');
```

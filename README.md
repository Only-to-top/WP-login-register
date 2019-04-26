# WP-login-register

```php
<form class="loginform" name="loginform" id="autoriz" action="<?php echo get_settings('siteurl'); ?>/wp-login.php" method="post">
  <div class="input-group mb-4">
    <div class="input-group-prepend">
      <span class="input-group-text"><i class="fas fa-user-alt"></i></span>
    </div>
    <input type="text" name="log" class="form-control" placeholder="Имя пользователя" id="login" value="" required>
  </div>
  <div class="input-group mb-5">
    <div class="input-group-prepend">
      <span class="input-group-text"><i class="fas fa-key"></i></span>
    </div>
    <input type="password" class="form-control" placeholder="Пароль" name="pwd" value="" id="password" required>
  </div>
  <div class="text-center">
    <input type="submit" name="submit" value="Войти" id="enter" class="btn btn-default" />
  </div>
</form>
```

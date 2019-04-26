# WP-login

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



# WP-login-register

```php
<form id="registerform" action="<?php site_url('wp-login.php?action=register'); ?>" method="post">
  <div class="input-group mb-4">
      <div class="input-group-prepend">
          <span class="input-group-text"><i class="fas fa-user-alt"></i></span>
      </div>
      <input type="text" class="form-control" placeholder="Имя пользователя" name="user_login" id="user_login" value="" required>
  </div>
  <div class="input-group mb-4">
      <div class="input-group-prepend">
          <span class="input-group-text"><i class="fas fa-envelope"></i></span>
      </div>
      <input type="email" class="form-control" placeholder="Email" name="user_email" id="user_email" value="" required>
  </div>
  <!-- <div class="input-group mb-4">
      <div class="input-group-prepend">
          <span class="input-group-text"><i class="fas fa-key"></i></span>
      </div>
      <input type="text" class="form-control" placeholder="Пароль">
  </div>
  <div class="input-group mb-5 load-image">
      <div class="input-group-prepend">
          <span class="input-group-text"><i class="fas fa-image"></i></span>
      </div>
      <input type="text" class="form-control" placeholder="Загрузить фото">
      <input type="file" class="custom-file-input" id="customFileLangHTML">
  </div> -->
  <div class="text-center">
    <input type="submit" name="wp-submit" id="wp-submit" class="btn btn-default" value="Регистрация">
  </div>
</form>
```

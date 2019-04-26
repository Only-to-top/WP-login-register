# WP-login-register

```php
<?php
  global $user_ID, $user_identity;
  get_currentuserinfo();
  if (!$user_ID):
?>
 
<form class="loginform" name="loginform" id="autoriz" action="<?php echo get_settings('siteurl'); ?>/wp-login.php" method="post">
  <div><input type="text" name="log" placeholder="Логин" value="" id="login" /></div> 
  <div><input type="password" name="pwd" placeholder="Пароль" value="" id="password" /></div> 
  <div><input type="submit" name="submit" value="Войти" id="enter" /></div>
  <div><a href="<?php bloginfo('wpurl'); ?>/wp-login.php?action=lostpassword">Забыли пароль?</a></div>
  <div><a href="<?php bloginfo('wpurl'); ?>/wp-login.php?action=register">Регистрация</a></div>
</form> 

  <?php else: ?>
  <h5 class="smile">Добро пожаловать, <?php echo $user_identity; ?>.</h5>
  <div class="right" style="text-align:right"><?php wp_loginout(); ?></div>
<?php endif; ?>
```

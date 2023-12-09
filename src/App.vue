
<template>
  <header>
  
      <div class="row">
        <div class="col-8">
          <div class="header-img">
            <img
              alt="#"
              src="https://upharma.xyz/assets/login-banner-9610bf90.jpg"
              class="img-fluid"
              width="100%"
              height="100%"
            />
          </div>
        </div>
        <div class="col-4">
          <div class="auth-form-container">
            <div class="auth-form">
              <div class="auth-form__header">
                <h2 class="auth-form__header-title">
                  Chào mừng đến với QLTS!
                  <i class="fa-sharp fa-solid fa-hand-wave"></i>
                </h2>
                <p>Vui lòng đăng nhập để bắt đầu sử dụng.</p>
              </div>
              <div class="auth-form__">
                <div class="auth-form__">
                  <input type="text" class="auth-form__input" placeholder="Tài khoản" />
                </div>
                <div class="auth-form__">
                  <input type="password" class="auth-form__input" placeholder="Mật khẩu " />
                </div>
                <div class="auth-form__ch-sa">
                  <input type="checkbox" class="auth-form__checkbox" /> Lưu đăng nhập
                  <a href="#" class="auth-form__Forgotpassword">Quên mật khẩu</a>
                </div>
              </div>
              <button class="btn btn-primary">Đăng Nhập</button>
              <div class="auth-form__ft">
                <p class="auth-form__text">Bạn chưa có tài khoản?</p>
                <a href="#" class="auth-form__register">Đăng ký tài khoản</a>
              </div>
            </div>
          </div>
        </div>
      </div>
  </header>
</template>

<style>
@import './assets/css/style.css';
</style>

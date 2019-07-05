<template>
  <div class="main">
    <div class="title">登录</div>
    <div class="content">
      <div class="form-wrapper">
        <div class="area">
          <div class="inputArea" type="mobileOrEmail">
            <label class="label">输入注册手机号或邮箱</label>
            <div class="input"><input placeholder="" type="text" name="mobileOrEmail" value=""></div>
          </div>
          <div class="inputArea" type="password">
            <label class="label">输入密码</label><div class="input">
              <input placeholder="" type="password" name="password" value="">
              <div class="forgetPass">忘记密码？</div>
            </div>
          </div>
          <div id="geetestCaptcha"></div>
          <button class="sm-button submit sc-1n784rm-0 bcuuIb" type="black">立即登录</button>
        </div>
        <div class="sc-kGXeez dCuBRr">
          <div class="changeVerify">
            <span>手机号登录可使用 <span class="link">短信验证码</span></span>
          </div>
        </div>
        <div class="sc-kgoBCf MPxxh">
          <div class="wechat"></div>
          <div class="wework"></div>
          <div class="dingTalk"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
// export default {
//   data() {}
// };
</script>
<style scoped>
.main .title {
  position: relative;
  width: 264px;
  margin: 0 auto;
  margin-bottom: 30px;
  color: #41464b;
  font-family: serif;
  font-size: 24px;
  font-weight: 700;
  line-height: 30px;
          letter-spacing: 2px;
  text-align: center;

  -webkit-letter-spacing: 2px;
     -moz-letter-spacing: 2px;
      -ms-letter-spacing: 2px;
}
.content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display:         flex;
          justify-content: center;
  box-shadow: 0 2px 3px 0 rgba(213, 213, 213, .7);

  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
}
.form-wrapper {
  box-sizing: border-box;
  width: 520px;
  height: auto;
  padding: 60px 90px;
  background-color: #fff;
}
.inputArea {
  display: inline-block;
  width: 100%;
  margin-right: 0;
  margin-bottom: 16px;
  border-radius: 2px;
}
.inputArea .label {
  display: block;
  margin-bottom: 8px;
  color: #a5a5a5;
  font-size: 12px;
  line-height: 1;
  text-align: left;
}
.inputArea .input {
  position: relative;
  box-sizing: border-box;
  height: 40px;
  background: #fff;
  background-color: #fff;
  box-shadow: inset 0 1px 3px 0 #e5e5e5;
  border: 1px solid #e5e5e5;
  border-radius: 2px;
          transition: border-color .3s;

  -webkit-transition: border-color .3s;
}
.inputArea .input input {
  box-sizing: border-box;
  width: 100%;
  height: 38px;
  padding: 11px 18px;
  color: #41464b;
  font-size: 14px;
  vertical-align: top;
  background: transparent;
  border: none;
  border-radius: 2px;
}
.inputArea .input .forgetPass {
  position: absolute;
  top: -20px;
  right: 14px;
  right: 0;
  color: #6da0e3;
  font-size: 12px;
  line-height: 1;
  cursor: pointer;
}
.dCuBRr {
  position: relative;
  top: -63px;
  line-height: 24px;
}
.dCuBRr .changeVerify {
  float: right;
  text-align: right;
}
.dCuBRr span {
  color: #a5a5a5;
  font-size: 12px;
}
.dCuBRr .changeVerify .link {
  color: #666;
  cursor: pointer;
}
.main .submit {
  width: 100%;
  height: 40px;
  margin-top: 6px;
  font-size: 14px;
  font-weight: 500;
}
.eTMQwS .submit {
  margin-top: 40px !important;
}
.bcuuIb {
  display: inline-block;
  box-sizing: border-box;
  min-width: 100px;
  height: 34px;
  padding: 0 15px;
  color: #fff;
  font-size: 14px;
  font-weight: bold;
  line-height: 1.4;
  line-height: 32px;
  text-align: center;
          text-decoration: none;
  background-color: #fff;
  background-image: linear-gradient(#41464b, #2c3033);
  border-color: #41464b;
  border-style: solid;
  border-width: 1px;
  border-radius: 2px;
          transition: opacity .3s, border-color .3s;
  cursor: pointer;

  -webkit-text-decoration: none;
  -webkit-transition: opacity .3s, border-color .3s;
}
</style>

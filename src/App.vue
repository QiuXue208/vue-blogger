<template>
  <div id="app">
    <div class="layui-container">
      <form class="layui-form layui-form-pane" action="">
        <div class="layui-form-item">
          <label class="layui-form-label">用户名</label>
          <div class="layui-input-block">
            <input type="text" name="title" required  lay-verify="required" placeholder="请输入用户名" autocomplete="off" class="layui-input">
          </div>
        </div>
        <div class="layui-form-item">
          <label class="layui-form-label">密码</label>
          <div class="layui-input-block">
            <input type="text" name="title" required  lay-verify="required" placeholder="请输入密码" autocomplete="off" class="layui-input">
          </div>
        </div>
        <div class="layui-form-item">
          <label class="layui-form-label">验证码</label>
          <div class="layui-input-block">
            <input type="text" name="title" required  lay-verify="required" placeholder="请输入验证码" autocomplete="off" class="layui-input">
          </div>
        </div>
        <button type="button" class="layui-btn">立即登录</button>
        <a href="http://www.layui.com" class="forget">忘记密码？</a>
      </form>
    </div>
  </div>
</template>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
input {
  width: 270px;
}
.forget {
  margin-left: 20px;
  &:hover {
    color: #009688;
  }
}
</style>

<template>
  <main class="setting">
    <div class="cells">
      <router-link to="/phone" class="cell is-access">
        <div class="cell-bd">
          <div class="cell-title">手机号码</div>
        </div>
        <div class="cell-ft">用于找回密码</div>
      </router-link>
      <router-link to="/email" class="cell is-access">
        <div class="cell-bd">
          <div class="cell-title">邮箱地址</div>
        </div>
        <div class="cell-ft"></div>
      </router-link>
      <router-link to="/password" class="cell is-access">
        <div class="cell-bd">
          <div class="cell-title">修改密码</div>
        </div>
        <div class="cell-ft">用于账号登录</div>
      </router-link>
    </div>

    <div class="cells">
      <div class="cell is-access">
        <div class="cell-bd">
          <div class="cell-title">银行卡管理</div>
        </div>
        <div class="cell-ft">用于提款</div>
      </div>
    </div>

    <div class="cells is-show-divider">
      <!--<div class="cell">
        <div class="cell-bd">
          <div class="cell-title">夜间模式</div>
        </div>
        <div class="cell-ft">
          <input type="checkbox" class="form-switch">
        </div>
      </div>-->
      <div class="cell">
        <div class="cell-bd">
          <div class="cell-title">免转钱包</div>
        </div>
        <div class="cell-ft">
          切换场馆，自动到账
          <input type="checkbox" class="form-switch">
        </div>
      </div>
    </div>

    <div class="cells">
      <router-link to="/about" class="cell is-access">
        <div class="cell-bd">
          <div class="cell-title">关于我们</div>
        </div>
        <div class="cell-ft"></div>
      </router-link>
    </div>
  </main>
</template>

<script>
  export default {
    name: 'setting'
  }
</script>

<style lang="stylus" scoped>

  .cells
    border-radius 5px
    margin 15px 15px 0

  .form-switch
    margin-left 15px
</style>

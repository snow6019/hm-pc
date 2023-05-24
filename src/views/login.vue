<template>
  <div class="login-page">
    <el-card class="el-card">
      <template #header>黑马面经运营后台</template>
      <el-form>
        <el-form-item label="用户名：">
          <el-input placeholder="请输入用户名" />
        </el-form-item>
        <el-form-item label="密码：">
          <el-input placeholder="请输入密码：" />
        </el-form-item>
        <el-form-item>
          <el-button type="primary">登录</el-button>
          <el-button>重置</el-button>
        </el-form-item>
      </el-form>
    </el-card>
  </div>
</template>

<script>
export default {
  name: 'login-page'
}
</script>

<style lang="scss" scoped>
.el-card {
  width: 420px;
  margin: 0 auto;
  // 深度作用选择器   ::v-deep   /deep/
  ::v-deep .el-card__header {
    background: rgba(114,124,245,1);
    text-align: center;
    color: white;
  }
}
</style>

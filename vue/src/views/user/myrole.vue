<template>
  <div class="app-container">
    <div class="filter-container">
      <el-form>
        <el-form-item>
          <el-button type="success" icon="plus" v-if="hasPerm('user:add')" @click="showCreate">添加角色
          </el-button>
        </el-form-item>
      </el-form>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
</script>
<style scoped>
  .requiredPerm {
    color: #ff0e13;
  }
</style>

<template>
  <el-container style="height: 500px; border: 1px solid #eee">
    <el-container>
      <el-main>
        <div>
          コンテンツ
        </div>
      </el-main>
    </el-container>
  </el-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Game extends Vue {}

</script>

<style lang="scss" scoped>
.el-header {
  background-color: #B3C0D1;
  color: #333;
  line-height: 60px;
}

.el-aside {
  color: #333;
}
</style>

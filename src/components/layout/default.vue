<template>
  <div class="layout">
    <el-container>
      <el-header>
          <my-header />
      </el-header>
      <el-main>
          <my-main />
      </el-main>
    </el-container>
  </div>
</template>
<script>
import myHeader from '@/components/index/header.vue'
import myMain from '@/components/index/main.vue'
export default {
    components: {
        myHeader,
        myMain
    }
};
</script>

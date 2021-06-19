<script lang="ts">
import { defineComponent } from 'vue'
import { ElCard } from 'element-plus'

export default defineComponent({
  setup() {
    
  },
  components: {
    ElCard
  }
  
})
</script>

<template>
<el-card >
  <span>欢迎</span> 
  <span>Welcome</span> 
</el-card>
</template>

<style scoped>
.home {
  top: 30%;
}
.home-central {
  text-align: center;
}
</style>

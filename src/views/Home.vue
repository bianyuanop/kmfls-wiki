<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {
    
  },
  components: {
  }
  
})
</script>

<template>
<div class="home">
  <span class="title">kmfls</span>
  <span class="desc">where old memories belong.</span>
  <div class="btn">Click to start ►</div>
</div>
<img src="@/assets/img/home-background.jpg" alt="home-background" class="bg">
</template>

<style scoped>
.btn {
  border-radius: 18px;
  border-style: solid;
  border-width: 1px;

  display: flex;
  justify-content: center;
  align-items: center;

  padding-left: 5%;
  padding-right: 5%;
  margin-top: 10%;
}

.btn:hover {
  cursor: pointer;
  background: whitesmoke;
}

.home {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  padding: 5%;

  background: rgba(130, 133, 128, 0.658);
}
.home-central {
  text-align: center;
}
.title {
  font-family: 'Chalk';
  font-size: 100px;
}
.desc {
  margin-top: -15px;
  font-size: 15px;
}
img.bg {
  position: absolute;
  z-index: -1;
}
</style>

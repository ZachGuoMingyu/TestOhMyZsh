<template>
  <div class="main">
    <Header title="我的嘟嘟" />
      <div id="content">
        <Login />
      </div>
    <TabBar />
  </div>
</template>

<script>

import Header from '@/components/Header'
import TabBar from '@/components/TabBar'
import Login from '@/components/Login'

export default {
  name:'Mine',
  components:{
    Header,
    TabBar,
    Login
  },
  data() {
    return {
    };
  },
};
</script>
<style scoped>
</style>

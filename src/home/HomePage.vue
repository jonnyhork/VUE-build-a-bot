<template>
  <div class="home">
    <div>
      <img class="robot" src="../assets/robot-home.png" alt="">
    </div>
    <div class="get-started">
      <a @click.prevent='sayHi()' href="">Get started</a> Build Your First Robot
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
  methods: {
    sayHi() {
      console.log('Hey')
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  text-align: center;
}
.robot {
  height: 300px;
}
</style>

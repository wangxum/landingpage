<template>
    <div class="topbar">
        <a class="logo">
            <img src="../assets/logo.png" alt="">
        </a>
        <right-buttons></right-buttons>
    </div>
</template>
<script>
  import rightButtons from "./web/right-buttons.vue";
  export default {
    components:{
      rightButtons
    }
  };
</script>
<style lang="scss" scoped>

.topbar {
  width: 100%;
  height: 64px;
  display: flex;
  align-items: center;
  position: relative;
  a {
    transition: color 0.2s ease-out;
  }
}
.logo {
  img {
    height: 32px;
  }
}

</style>



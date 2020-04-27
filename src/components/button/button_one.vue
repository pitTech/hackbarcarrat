<template>
  <div>
       <b-button class="fontdetial" size="is-large" type="is-primary">เข้าสู่ระบบ</b-button>
  </div>
</template>

<script>
export default {
  name: 'button_one',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.fontdetial{
    width: 200px;
}
</style>

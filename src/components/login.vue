<template>
<div >
  <div class="section"> 
      <div class="bgscreen">
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
      <center>
          <H1 class="fontdetial">ระบบ Login เพื่อเข้าสูตร Barcarrat</H1>
          <br>            
          <b-input placeholder="ID" class="sizebutton mdiAccount"></b-input>
          <br> 
          <b-input type="password" class="sizebutton" placeholder="Password"></b-input>  
          <br>
        <buttonone />  
          <br> 
         <buttontwo  class="btntwoposition"/>      
      </center>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
        </div>
  </div>
</div>
</template>

<script>
import buttonone from './button/button_one.vue';
import buttontwo from './button/button_two.vue';

export default {
  name: 'Login',
  props: {
    msg: String
  },
  components:{
      buttonone,buttontwo
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.field{
    flex-direction:column;
}
.sizebutton{
    width: 300px;
}
.bgscreen{
    background-image: url("https://images.pexels.com/photos/1871508/pexels-photo-1871508.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260");
    height: 100%;
    background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.btntwoposition{
    margin-top: 10px;
}
.fontdetial{
    font-size: 50px;
    color:#000;
}
</style>

<template >
  <div>
     <b-navbar id="nav" toggleable type="dark"  sticky>
       <b-container>
           <b-navbar-brand >Biblioteca Digital</b-navbar-brand>



    <b-form inline id="form">
      <label class="name" for="name"></label>
      <b-input class="nome" id="nome" placeholder="nome" />&ensp;
      <label class="senha" for="senha"> </label>
      <b-input-group  class="senha">
        <b-input id="senha" placeholder="senha" />
      </b-input-group>&ensp;
      <b-form-checkbox class="mb-2 mr-sm-2 mb-sm-0">Remember me</b-form-checkbox>
      <b-button id="button" >Entrar</b-button>
    </b-form>

     
           <b-navbar-toggle target="nav_text_collapse"></b-navbar-toggle>
       </b-container>
   </b-navbar>

<b-container>
<img id="logo" src=".\assets\logo.png" width="500"  >
   
</b-container>
  </div>
</template>

<script>

</script>

<style>
#nav{
    background-color:dimgray;
}
#form{
    font-style: normal;
    color:ghostwhite;
}
#button{
    color:lightpink;
    background-color: white;
}
#logo{
    display: block;
    margin-left: auto;
    margin-right: auto;
             
  
}
</style>

<template>

<div> 
<b-navbar toggleable="md" type="dark" variant="dark" >
<b-navbar-brand href="#">Biblioteca Virtual</b-navbar-brand>

</b-navbar>

<b-container class ="container">
	<b-container class="wrapper">
		<b-form action="" method="post" name="Login_Form" class="form-signin">       
		    <h3 class="form-signin-heading">Login</h3>
			  
			  
			  <b-input type="text" class="form-control" name="Username" placeholder="Nome" required="" autofocus="" />
			  <b-input type="password" class="form-control" name="Password" placeholder="Senha" required=""/>     		  
			 
			  <b-button class="btn btn-lg btn-primary btn-block"  name="Submit" value="Login" type="Submit">Entrar</b-button>  			
		</b-form>			
	</b-container>
</b-container>
   
  </div>

 
</template>

<script>

</script>

<style>
        
        .wrapper {    
	margin-top: 180px;
	margin-bottom: 20px;
}

.form-signin {
  max-width: 420px;
  padding: 30px 38px 66px;
  margin: 0 auto;
  background-color: #eee;
  border: 3px dotted rgba(0,0,0,0.1);  
  }

.form-signin-heading {
  text-align:center;
  margin-bottom: 30px;
}

.form-control {
  position: relative;
  font-size: 16px;
  height: auto;
  padding: 10px;
}

input[type="text"] {
  margin-bottom: 0px;
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

input[type="password"] {
  margin-bottom: 20px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}


        
</style>

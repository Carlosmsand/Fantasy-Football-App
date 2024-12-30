<div class="header_container">
<h1>Homepage</h1>
</div>
<div class="login_box">
<h3>Login</h3>    
<form on:submit={handleSubmit} action="/login" method="POST">
    <div class="form-group">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required />
    </div>
    <div class="form-group">
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required />
    </div>  
    <button type="submit">Login</button>
</form>
</div>
<style>
    :global(body){
            background-image: url('https://image.spreadshirtmedia.com/image-server/v1/products/T993A1PA2168PT10X45Y36D1040766660W15555H13499/views/1,width=800,height=800,appearanceId=1,backgroundColor=F2F2F2/commish-ffl-logo-fantasy-football-league-mouse-pad.jpg');  
            background-size: cover;                      
            background-position: center;                  
            background-repeat: no-repeat;                 
            height: 100vh;                                
            margin: 0;       
    }
   .header_container{
display: flex;
justify-content: center;
}
.login_box{
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}
form {
       display: flex;
       flex-direction: column;    
       align-items: center;
   }

   .form-group {
       display: flex;           
       align-items: center;    
       margin-bottom: 10px;       
   }

</style>

<script>
import { goto } from '$app/navigation';

function handleSubmit() {
  goto('/Homepage'); 
}
</script>
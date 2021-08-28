<template>
    <div class="row justify-content-center " style="margin-top: 10vh;" >
        <div class="col-3 p-0 my-auto "  >
              <div class="flex-column  p-5 pb-2  shadow ">
                <div class=" row justify-content-center mb-5">
                    <img class="" src="../../assets/sign in/logo.png"/>
                    
                </div>
                <form>
                  <div class="form-group">                    
                    <div class="input-group mb-3">
                      <input type="text" class="form-control" placeholder="Professional email" aria-label="Recipient's username" aria-describedby="basic-addon2">
                      <div class="input-group-append">
                        <span class="input-group-text" id="basic-addon2">@esi-sba.dz</span>
                      </div>
                    </div>
                  </div>
                  <div class="form-group">                    
                    <input type="text" class="form-control" id="exampleInputPassword1" placeholder="First name">
                  </div>
                  <div class="form-group">                    
                    <input type="text" class="form-control" id="exampleInputPassword1" placeholder="Last name">
                  </div>
                  <div class="form-group">
                    <label for="sel1">Job:</label>
                    <select class="form-control uneditable-input" id="sel1">
                      <option class="uneditable-input">Professor</option>
                      <option class="uneditable-input">Administration</option>
                      <option class="uneditable-input">Maitnance</option>
                      <option class="uneditable-input">Agent</option>
                    </select>
                  </div>
                  <div class="row justify-content-center mb-4">
                    <button type="submit" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad " >Submit</button>
                  </div>
                  <div class="mb-1 text-center " style="font-size: small;">You already have an account?</div>
                  <div class="text-center "><a href="#" style="font-weight:bold;">Sign in!</a></div>
                </form>
                
                
    
         
              </div>
      </div>
     
  </div>
</template>

<script>
export default {
    name: 'DemandAccount'
}
</script>

<style>
      .btn-grad{
        background-image: linear-gradient(to right, #e97923 0%, #e97923 30%, #efa81d   100%)}
         .btn-grad {
            margin: 10px;
            padding: 15px 45px;
            text-align: center;
            text-transform: uppercase;
            transition: 0.5s;
            background-size: 200% auto;
            color: white;            
            box-shadow: 0 0 20px #eee;
            border-radius: 4px;
            display: block;
            border: 0px;
          }

          .btn-grad:hover {
            background-position: right center; /* change the direction of the change here */
            color: #fff;
            text-decoration: none;
          }
          a{
            text-decoration: underline;
            color: #e97923;
          }
          a:hover{
            color:#efa81d;
            text-decoration: underline;

          }
          textarea:focus,
input[type="text"]:focus,
input[type="password"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="date"]:focus,
input[type="month"]:focus,
input[type="time"]:focus,
input[type="week"]:focus,
input[type="number"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="color"]:focus,
.uneditable-input:focus {   
  border-color: #e97923;
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.025) inset, 0 0 10px #e97923;
  outline: 0 none;
}

      
</style>
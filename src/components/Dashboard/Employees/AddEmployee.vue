<template>
    <div class="jumbotron m-2">
      <a href="#">
        <div class="d-flex">
        <p>Employee list</p>
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-return-left" viewBox="0 0 16 16" style="margin-top: 5px;margin-left:5px">
          <path fill-rule="evenodd" d="M14.5 1.5a.5.5 0 0 1 .5.5v4.8a2.5 2.5 0 0 1-2.5 2.5H2.707l3.347 3.346a.5.5 0 0 1-.708.708l-4.2-4.2a.5.5 0 0 1 0-.708l4-4a.5.5 0 1 1 .708.708L2.707 8.3H12.5A1.5 1.5 0 0 0 14 6.8V2a.5.5 0 0 1 .5-.5z"/>
        </svg>
      </div>
    </a>
        <h1 class="display-4">Add New Employee</h1>
        <p class="lead">You can add a new employee in your employee list, just fill in the form below with the informations of the employee in concern!</p>
        <hr class="my-4">
        <div class="form-group">                    
            <input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="First Name">
            <input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="Last Name">
            <div class="input-group mb-4">
                <input type="text" class="form-control" placeholder="Professional email" aria-label="Recipient's username" aria-describedby="basic-addon2">
                <div class="input-group-append">
                  <span class="input-group-text" id="basic-addon2">@esi-sba.dz</span>
                </div>
              </div>
            <input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="Phone Number">
            <div class="form-group">
                <p class="lead" style="color: grey; font-weight: 300;">Birthday:</p>
                <input class="form-control" type="date" value="2011-08-19" id="example-date-input">
            </div>
            <div class="form-group mb-4">
                <p class="lead" style="color: grey; font-weight: 300;">Job</p>
                <select class="form-control uneditable-input" id="sel1">
                  <option class="uneditable-input">Professor</option>
                  <option class="uneditable-input">Administration</option>
                  <option class="uneditable-input">Maitnance</option>
                  <option class="uneditable-input">Agent</option>
                </select>
                </div>
            <input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="CCP Account">

          </div>
        <div class="row justify-content-start mb-4 mt-4">
            <button type="submit" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad " >Add Employee</button>
        </div>
      </div>
</template>

<script>
export default {
    name: 'AddEmployee',
    data() {
      
    },
}
</script>

<style>
.btn-grad{
        background-image: linear-gradient(to right, #2e5083 0%, #2e5083 30%, #0e1e58   100%)}
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
            color: #2e5083;
          }
          a:hover{
            color:#0e1e58;
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
  border-color: #2e5083;
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.025) inset, 0 0 10px #2e5083;
  outline: 0 none;
}
.bootstrap-select .bs-ok-default::after {
    width: 0.3em;
    height: 0.6em;
    border-width: 0 0.1em 0.1em 0;
    transform: rotate(45deg) translateY(0.5rem);
}

.btn.dropdown-toggle:focus {
    outline: none !important;
}       
</style>
<template>
    <div class="jumbotron m-2">
      <services-nav-bar></services-nav-bar>
      <a href="#">
      <div class="d-flex">
      <p>Donations list</p>
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-return-left" viewBox="0 0 16 16" style="margin-top: 5px;margin-left:5px">
        <path fill-rule="evenodd" d="M14.5 1.5a.5.5 0 0 1 .5.5v4.8a2.5 2.5 0 0 1-2.5 2.5H2.707l3.347 3.346a.5.5 0 0 1-.708.708l-4.2-4.2a.5.5 0 0 1 0-.708l4-4a.5.5 0 1 1 .708.708L2.707 8.3H12.5A1.5 1.5 0 0 0 14 6.8V2a.5.5 0 0 1 .5-.5z"/>
      </svg>
    </div>
  </a>
        <h1 class="display-4">Add New Donation</h1>
        <p class="lead">You can add a new donation for you employees, just fill in the form below!</p>
        <hr class="my-4">
        <div class="form-group">                    
            <input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="Name of Donation">

            <div class="row">
                <div class="col-3"><input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="Article number">
                </div>
                <div class="col-3"><input type="text" class="form-control mb-4" id="exampleInputPassword1" placeholder="chapter number">
                </div>
            </div>
            <textarea class="form-control mb-4 uneditable-input" id="exampleFormControlTextarea1" rows="3" placeholder="Description"></textarea>
            <p class="lead" style="color: grey; font-weight: 300;">Required Documents:</p>
            <select class="js-example-basic-multiple placeholder-single mb-4" name="states[]" multiple="multiple" style="width: 100%;">
              <option value="AL" class="uneditable-input">certificat de naissance</option>
              <option value="AL" class="uneditable-input">certificat de</option>
              <option value="WY" class="uneditable-input">3a9D</option>              
            </select>
            <div class="row mt-4">
              <div class="col-3">
                <div class="lead" style="color: grey; font-weight: 300;font-size: large;"> Didn't find the right document?</div>
              </div>
            <div class="col-3">
              <button type="submit" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad m-0"  style="font-size:small" data-toggle="modal" data-target="#exampleModalCenter">Add New document</button>
            </div>
            </div>
         
        <div class="row justify-content-start mb-4 mt-4">
            <button type="button" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad "  >Add Donation</button>
          </div>
    
        
        <!-- Modal -->
        <div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
          <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Add new document</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>
              <div class="modal-body">
                <input type="text" class="form-control mb-4" id="newDocument" placeholder="Name of new document">
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary p-1 pl-3 pr-3 btn-grad2" data-dismiss="modal" >CLOSE</button>
                <button type="button" class="btn btn-primary btn-grad p-1 pl-3 pr-3">Save changes</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
import ServicesNavBar from './ServicesNavBar.vue'
export default {
    name: 'AddDonation',
    components: {
        ServicesNavBar
    }
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

          .btn-grad2:hover {
            background-color: black; /* change the direction of the change here */
            color: #fff;
            text-decoration: none;
          }
         
         .btn-grad2 {
           background-color: grey;
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
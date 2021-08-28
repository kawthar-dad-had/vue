<template>
  <div>
    <div class="container m-0" >
       
        <ul class="nav nav-tabs">
          <li class="active "><a data-toggle="tab" href="#home" class="nav-item nav-link linka"  style="text-decoration: none;">Donations</a></li>
          <li><a data-toggle="tab" href="#menu1" class="nav-item nav-link linka"  style="text-decoration: none;">compensations</a></li>
          <li><a data-toggle="tab" href="#menu2" class="nav-item nav-link linka"  style="text-decoration: none;">offers</a></li>
          <li><a data-toggle="tab" href="#menu3" class="nav-item nav-link linka" style="text-decoration: none;">Debts</a></li>
        </ul>
      
        <div class="tab-content">
          <div id="home" class="tab-pane fade in active">
            <div class="row">
              <h3 class="p-5 pt-4 col-4">Donations</h3>
              <div class="col-8">
                <div class="row justify-content-end mb-4 mt-4 mr-2 pt-3">
                  <div class="search col-7 m-0 ml-2 "> <input type="text" class="search-input p-2 border m-0" placeholder="Search..." name=""> <a href="#" class="search-icon btn-grad " style="margin-top:-6px; margin-right: -1px;" > <i class="fa fa-search"></i> </a> </div>
                  <button type="submit" class="btn btn-primary btn btn-outline pt-2 pb-2 pr-5 pl-5 btn-grad col-4" style="font-size: small;">Add Donation
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus" viewBox="0 0 16 16">
                      <path d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"/>
                    </svg>
                  </button>
                </div>
            </div>
            </div>
                 <div class="row  shadow m-1 mb-4">
                   <div class="pr-5" style="display: block; background-color: #e97923; width: 2px;"></div>
                   <div class="col-8 p-4 pr-0">
                      <h4 class="ml-2">Wedding donation</h4>
                   </div>
                   <div class="col-3">
                    <div class="row justify-content-end">
                      <div class="col-3 mt-4 p-0"><a class="edit" title="Edit" data-toggle="tooltip" ><i class="material-icons linka" style="text-decoration: none; cursor: pointer;">&#xE254;</i></a></div>
                      <div class="col-3 mt-4 p-0"><a class="delete" title="Delete" data-toggle="tooltip"><i class="material-icons linka" style="text-decoration: none; cursor: pointer;" data-toggle="modal" data-target="#exampleModalCenter">&#xE872;</i></a></div>
                     </div>
                   </div>
                 </div>
                 <div class="row  shadow m-1 mb-4">
                  <div class="pr-5" style="display: block; background-color: #e97923; width: 2px;"></div>
                  <div class="col-8 p-4 pr-0">
                     <h4 class="ml-2">Wedding donation</h4>
                  </div>
                  <div class="col-3">
                   <div class="row justify-content-end">
                     <div class="col-3 mt-4 p-0"><a class="edit" title="Edit" data-toggle="tooltip" ><i class="material-icons linka" style="text-decoration: none; cursor: pointer;">&#xE254;</i></a></div>
                     <div class="col-3 mt-4 p-0"><a class="delete" title="Delete" data-toggle="tooltip"><i class="material-icons linka" style="text-decoration: none; cursor: pointer;" data-toggle="modal" data-target="#exampleModalCenter">&#xE872;</i></a></div>
                    </div>
                  </div>
                </div>
          </div>
         
          <div id="menu1" class="tab-pane fade">
            <div class="row">
              <h3 class="p-5 pt-4 col-4">Compensations</h3>
              <div class="col-8">
                <div class="row justify-content-end mb-4 mt-4 mr-2 pt-3">
                  <div class="search col-7 m-0 ml-2 "> <input type="text" class="search-input p-2 border m-0" placeholder="Search..." name=""> <a href="#" class="search-icon btn-grad " style="margin-top:-6px; margin-right: -1px;" > <i class="fa fa-search"></i> </a> </div>
                  <button type="submit" class="btn btn-primary btn btn-outline pt-2 pb-2 pr-5 pl-5 btn-grad col-4" style="font-size: small;">Add Compensation
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus" viewBox="0 0 16 16">
                      <path d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"/>
                    </svg>
                  </button>
                </div>
            </div>
            </div>
                   <div class="row  shadow m-1 mb-4">
                     <div class="pr-5" style="display: block; background-color: #e97923; width: 2px;"></div>
                     <div class="col-8 p-4 pr-0">
                        <h4 class="ml-2">Death compensation</h4>
                     </div>
                     <div class="col-3">
                      <div class="row justify-content-end">
                        <div class="col-3 mt-4 p-0"><a class="edit" title="Edit" data-toggle="tooltip" ><i class="material-icons linka" style="text-decoration: none; cursor: pointer;">&#xE254;</i></a></div>
                        <div class="col-3 mt-4 p-0"><a class="delete" title="Delete" data-toggle="tooltip"><i class="material-icons linka" style="text-decoration: none; cursor: pointer;" data-toggle="modal" data-target="#exampleModalCenter">&#xE872;</i></a></div>
                       </div>
                     </div>
                   </div>
                   <div class="row  shadow m-1 mb-4">
                    <div class="pr-5" style="display: block; background-color: #e97923; width: 2px;"></div>
                    <div class="col-8 p-4 pr-0">
                       <h4 class="ml-2">Accident compensation</h4>
                    </div>
                    <div class="col-3">
                     <div class="row justify-content-end">
                       <div class="col-3 mt-4 p-0"><a class="edit" title="Edit" data-toggle="tooltip" ><i class="material-icons linka" style="text-decoration: none; cursor: pointer;">&#xE254;</i></a></div>
                       <div class="col-3 mt-4 p-0"><a class="delete" title="Delete" data-toggle="tooltip"><i class="material-icons linka" style="text-decoration: none; cursor: pointer;" data-toggle="modal" data-target="#exampleModalCenter">&#xE872;</i></a></div>
                      </div>
                    </div>
                  
          </div>
          </div>
          <div id="menu2" class="tab-pane fade">
            <h3 class="p-5">Offers</h3>
          </div>
          <div id="menu3" class="tab-pane fade">
            <h3 class="p-5">Debts</h3>
          </div>
        </div>
      </div>
      
        <!-- Modal -->
        <div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
          <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Delete element?</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>
            
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary p-1 pl-3 pr-3 btn-grad" data-dismiss="modal" >keep</button>
                <button type="button" class="btn btn-primary btn-grad2 p-1 pl-3 pr-3">Delete</button>
              </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ServicesNavBar',    
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
          .linka{
            text-decoration: underline;
            color: #e97923;
          }
          .linka:hover{
            color:#efa81d;
            text-decoration: underline;

          }
          .search {
    width: 100%;
    margin-bottom: auto;
    margin-top: 20px;
    height: 50px;
    background-color: #fff;
    padding: 10px;
    border-radius: 5px
}

.search-input {
    color: white;
    border: 0;
    outline: 0;
    background: none;
    width: 0;
    margin-top: 5px;
    caret-color: transparent;
    line-height: 20px;
    transition: width 0.4s linear
}

.search .search-input {
    padding: 0 10px;
    width: 100%;
    caret-color: #536bf6;
    font-size: 19px;
    font-weight: 300;
    color: black;
    transition: width 0.4s linear
}

.search-icon {
    height: 34px;
    width: 34px;
    float: right;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    background-color: #536bf6;
    font-size: 10px;
    bottom: 30px;
    position: relative;
    border-radius: 5px
}

.search-icon:hover {
    color: #fff !important
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

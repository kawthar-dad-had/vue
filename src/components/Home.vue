<template>
  <div class="row">
    <div class="col-3 p-0 sidenav" >
      <div class="list-group" id="list-tab" role="tablist">
        <a class="list-group-item list-group-item-action active blue" id="list-home-list" data-toggle="list" href="#list-home" role="tab" aria-controls="home"><i class="fas fa-home pl-2 pr-3"></i> Home</a>
        <a class="list-group-item list-group-item-action blue" id="list-regulation-list" data-toggle="list" href="#list-regulation" role="tab" aria-controls="profile"><i class="fas fa-gavel pl-2 pr-3"></i>Workspace Regulations</a>
        <a class="list-group-item list-group-item-action blue" id="list-messages-list" data-toggle="list" href="#list-messages" role="tab" aria-controls="messages"><i class="fas fa-heart pl-2 pr-3"></i>Request a Donation</a>
        <a class="list-group-item list-group-item-action blue" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings"><i class="fas fa-hand-holding-usd pl-2 pr-3"></i>Request a Compensation</a>
        <a class="list-group-item list-group-item-action blue" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings"><i class="far fa-credit-card pl-2 pr-3"></i>Request a Debt</a>
        <a class="list-group-item list-group-item-action blue" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings"><i class="fas fa-gift pl-2 pr-3"></i>Enroll in an Offer</a>

      </div>
    </div>
    <div class="col-9">
      
      <div class="tab-content" id="nav-tabContent">
        <div class="tab-pane fade show active" id="list-home" role="tabpanel" aria-labelledby="list-home-list">hi</div>
        <div class="tab-pane fade" id="list-regulation" role="tabpanel" aria-labelledby="list-regulation-list">   <include src="./public/index.html"></include>        </div>
        <div class="tab-pane fade" id="list-messages" role="tabpanel" aria-labelledby="list-messages-list">...</div>
        <div class="tab-pane fade" id="list-settings" role="tabpanel" aria-labelledby="list-settings-list">...</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Home'
}
</script>

<style>

</style>template>

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
                color: #2e5083;
              }
              .linka:hover{
                color:#0e1e58;
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
        caret-color: #2e5083;
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
        background-color: #2e5083;
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
      border-color: #0e1e58;
      box-shadow: 0 2px 2px rgba(0, 0, 0, 0.025) inset, 0 0 10px #0e1e58;
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
    .avatar {
      vertical-align: middle;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      border: 1px;
      border-color: #0e1e58;
        
    } 
    .blue{
        background-color: #2e5083;
        color: white;
    }
    .blue:hover{
        background-color: #e97923;
        color: white;
    }
    .blue:active{
        background-color: #efa81d;
        color: white;
    }
    .blue:focus{
        background-color: #efa81d;
        color: white;
    }
    .list-group-item.active{
      background-color: #e97923;
        color: white;
        border: 0px;

    }
    .sidenav {
  height: 100%;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #2e5083;
  overflow-x: hidden;
  padding-top: 20px;
}

</style>

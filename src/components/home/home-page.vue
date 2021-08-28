<template>  
    <div>
        <nav style="background: #ffffff;" class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
              <div class="container-fluid">
                <button
                  class="navbar-toggler"
                  type="button"
                  data-bs-toggle="offcanvas"
                  data-bs-target="#sidebar"
                  aria-controls="offcanvasExample"
                >
                  <span class="navbar-toggler-icon" data-bs-target="#sidebar"></span>
                </button>
                <a class="navbar-brand" href="#">
                  <img src="logo long.png" width="120" height="auto">
                </a>
                <button
                  class="navbar-toggler"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#topNavBar"
                  aria-controls="topNavBar"
                  aria-expanded="false"
                  aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
                <div style="justify-content: flex-end;" class="collapse navbar-collapse" id="topNavBar">
                  <ul class="navbar-nav">
                    <li class="nav-item active">
                      <a  class="nav-link" href="#">Home <span class="sr-only"></span></a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">News</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">About us</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link " href="#">Contact us</a>
                    </li>
                  </ul>
                  <div class="dropdown ">
                    <button class="btn" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="padding: 0px;border: 0px;background-color: white;">
                  <a class="navbar-brand " href="#">
                    <img src="user (1).png"  >
                  </a>
                    </button>
                    <div class="dropdown-menu dropdown-menu-right" aria-labelledby="dropdownMenuButton">
                      <a class="dropdown-item" href="#">disconnect</a>
                    </div>
                  </div>
                </div>
              </div>
        </nav>
        <div class="row">
            <div class="col-md-3">
                <!-- top navigation bar -->
                <!-- offcanvas -->
                <div class="offcanvas offcanvas-start sidebar-nav bg-dark" tabindex="-1" id="sidebar" >
                    <div style="background: #2e5083 !important; padding-right: 0 !important; margin-right: 0px;" class="offcanvas-body p-0 ">
                        <div id="mySidebar" class="sidebar">
                            <div class="list-group" id="list-tab" role="tablist">
                                <a class="list-group-item list-group-item-action active blue" id="list-home-list" data-toggle="list" href="#list-home" role="tab" aria-controls="home"><i class="fas fa-home pl-2 pr-3"></i> Home</a>
                                <a class="list-group-item list-group-item-action blue" id="list-regulation-list" data-toggle="list" href="#list-regulation" role="tab" aria-controls="profile"><i class="fas fa-gavel pl-2 pr-3"></i>Workspace Regulations</a>
                                <a class="list-group-item list-group-item-action blue" id="list-messages-list" data-toggle="list" href="#list-messages" role="tab" aria-controls="messages"><i class="fas fa-heart pl-2 pr-3"></i>Request a Donation</a>
                                <a class="list-group-item list-group-item-action blue" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings"><i class="fas fa-hand-holding-usd pl-2 pr-3"></i>Request a Compensation</a>
                                <a class="list-group-item list-group-item-action blue" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings"><i class="far fa-credit-card pl-2 pr-3"></i>Request a Debt</a>
                                <a class="list-group-item list-group-item-action blue" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings"><i class="fas fa-gift pl-2 pr-3"></i>Enroll in an Offer</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-9 p-0">
                <!-- offcanvas -->
                <div class="row p-0">
                    <div class="col-md-12 p-0"  style="padding: 0px !important; " >
                        <div id="carouselExampleIndicators" class="carousel slide " data-ride="carousel">
                            <ol class="carousel-indicators">
                                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                            </ol>
                            <div class="carousel-inner " style="height: 250px;">
                                <div class="carousel-item active">
                                    <h4 class="heading" style="color: #ffffff; background: #e97923 ; position: absolute; top: 40%; text-align: start; margin-left: 20px; padding: 2px;">Summer holidays plan 2021!</h4>
                                    <img class="d-block w-100" src="image1.jpg" >
                                </div>
                                <div class="carousel-item">
                                    <img class="d-block w-100" src="image2.jpg" >
                                </div>
                                <div class="carousel-item">
                                 <img class="d-block w-100" src="image3.jpg" >
                                </div>
                            </div>
                            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </a>
                            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </a>
                 
                        </div>
                    </div>
                </div>
                <!--    dashboard all 
                <div class="container-fluid pt-5 justify-content-center">
                    <div class="col-md-12" >
                      <h3>Current Available Special Offers</h3>
                    </div>
                </div>  
                -->
                <div class="row justify-content-center mt-5 " style="margin:auto ;" >
                    <div class="row justify-content-center " style="margin-bottom: 50px;" >
                        <h2 >Current Available Special Offers</h2>
                        <div class="container">
                            <div class="row" style="margin: auto; max-width: 1000px;">
                                <div class="card m-3 shadow" style="width: 18rem;">
                                    <img src="summer.jpg" class="card-img-top ">
                                    <div class="card-body">
                                        <h5 class="card-title">Card title</h5>
                                        <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
                                        <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                                    </div>
                                </div>
                                <!--   Card 2 -->
                                <div class="card m-3 shadow" style="width: 18rem;">
                                    <img src="summer.jpg" class="card-img-top ">
                                    <div class="card-body">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                                        <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
                                        </div>
                                </div>
                                <!--   Card 3 -->
                                <div class="card m-3 shadow" style="width: 18rem;">
                                    <img src="summer.jpg" class="card-img-top ">
                                    <div class="card-body">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                                        <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
                                    </div>
                                </div>
                                <!--   Card 4 -->
                                <div class="card m-3 shadow" style="width: 18rem;">
                                    <img src="summer.jpg" class="card-img-top ">
                                    <div class="card-body">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                                        <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
                                    </div>
                                </div>
                                <!--   Card 5 -->
                                <div class="card m-3 shadow" style="width: 18rem;">
                                    <img src="summer.jpg" class="card-img-top ">
                                    <div class="card-body">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                                        <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
                                    </div>
                                </div>
                                <!--   Card 6 -->
                                <div class="card m-3 shadow" style="width: 18rem;">
                                    <img src="summer.jpg" class="card-img-top ">
                                    <div class="card-body">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                                        <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
    
<script> 
    export default {
        name: 'home',
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
    border: 0px
  }
  .row>* {
    padding-right: 0 !important;
    padding-left: 0 !important;
  }
  .card-title {
    color: #2e5083;
    font-weight: lighter !important;
    font-size: 1.09rem;
  }
  .card-text {
    color: #e97923;
    font-size: 0.95rem;
  }
  .btn {
    background: white;
    border-radius: 0.2rem;
    border-color: #2e5083;
    color: #2e5083;
    justify-content: end !important;
    font-size: 0.9rem;
    font-weight: 250 !important;
  }
  .btn:hover {
    background: #2e5083 !important;
    color: white !important;
  }
  .card {
    height: max-content !important;
  }
  .modal-header {
    border-bottom: none !important;
  }
  .modal-footer {
    border-top: none !important;
  }
  .modal-header {
    padding: 0 !important;
  }
  .modal-header .card-img-top {
    height: 120px !important;
    object-fit: cover;
  } 
</style>
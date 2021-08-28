<template>
    <div>
        <div class="jumbotron m-2">
            <a href="#">
                <div class="d-flex">
                    <p>services list</p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-return-left" viewBox="0 0 16 16" style="margin-top: 5px;margin-left:5px">
                        <path fill-rule="evenodd" d="M14.5 1.5a.5.5 0 0 1 .5.5v4.8a2.5 2.5 0 0 1-2.5 2.5H2.707l3.347 3.346a.5.5 0 0 1-.708.708l-4.2-4.2a.5.5 0 0 1 0-.708l4-4a.5.5 0 1 1 .708.708L2.707 8.3H12.5A1.5 1.5 0 0 0 14 6.8V2a.5.5 0 0 1 .5-.5z"/>
                    </svg>
                </div>
            </a>
            <h1 class="display-4">Offer Name</h1>
            <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis corporis laborum iure sit voluptas tempora expedita non eius amet rerum velit, quasi quas perferendis nesciunt pariatur beatae inventore similique ad!</p>
            <hr class="my-4">
            <div class="form-group">   
                <p class="lead" style="color: rgb(8, 8, 8); font-weight: 300;">Required Documents:</p>
                <div class="row mt-4">
                    <div class="col-3" id="borderDot" style="border: dashed #e97923 2px ; margin-left: 16px; margin-right: 40px"  >
                        <div class="lead file-name"  style="color: rgb(82, 80, 80);; font-weight: 300;font-size: large; padding: 4px;"> certificat de naissance</div>
                    </div>
                    <div class="col-3">
                        <button  onclick="defaultBtnActive()" id="custom-btn" value="red" type="button" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad m-0" style="font-size:small; " data-toggle="modal" data-target="#exampleModalCenter">Choose a file</button>
                        <input id="default-btn" type="file" hidden>
                    </div>
                </div>
                <div class="row mt-4">
                    <div class="col-3" id="borderDot2" style="border: dashed #e97923 2px ; margin-left: 16px; margin-right: 40px"  >
                        <div class="lead file-name2" style="color: rgb(82, 80, 80); font-weight: 300; padding: 4px;font-size: large;"> certificat de</div>
                    </div>
                    <div class="col-3">
                        <button onclick="defaultBtnActive2()" id="custom-btn2" type="button" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad m-0" style="font-size:small" data-toggle="modal" data-target="#exampleModalCenter">Choose a file</button>
                        <input id="default-btn2" type="file" hidden>
                    </div>
                </div>
                <div class="row mt-4">
                    <div class="col-3" id="borderDot3" style="border: dashed #e97923 2px ; margin-left: 16px; margin-right: 40px"  >
                        <div class="lead file-name3" style="color: rgb(82, 80, 80); font-weight: 300; padding: 4px; font-size: large;"> 3a9d</div>
                    </div>
                    <div class="col-3">
                        <button onclick="defaultBtnActive3()" id="custom-btn3" type="button" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad m-0" style="font-size:small" data-toggle="modal" data-target="#exampleModalCenter">Choose a file</button>
                        <input id="default-btn3" type="file" hidden >
                    </div>
                </div>
                <div class="row justify-content-start mb-4 mt-4">
                    <button type="button" class="btn btn-primary pt-2 pb-2 pr-5 pl-5 btn-grad "  >Add Offer</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    $(document).ready(function() {
      $('.js-example-basic-multiple').select2();
    });
    $(".js-example-placeholder-single").select2({
      placeholder: "Select a state",
      allowClear: true
    });

    const fileName = document.querySelector(".file-name");
    const defaultBtn = document.querySelector("#default-btn");
    const customBtn = document.querySelector("#custom-btn");
    const customBtn2 = document.querySelector("#custom-btn2");
    const fileName2 = document.querySelector(".file-name2");
    const defaultBtn2 = document.querySelector("#default-btn2");
    const customBtn3 = document.querySelector("#custom-btn3");
    const fileName3 = document.querySelector(".file-name3");
    const defaultBtn3 = document.querySelector("#default-btn3");
     
    let regExp = /[0-9a-zA-Z\^\&\'\@\{\}\[\]\,\$\=\!\-\#\(\)\.\%\+\~\_ ]+$/;
    function defaultBtnActive(){
          defaultBtn.click();
    }
    function defaultBtnActive2(){
          defaultBtn2.click();
    }
    function defaultBtnActive3(){
          defaultBtn3.click();
    }
    
    defaultBtn.addEventListener("change", function(){

           const file = this.files[0];
           if(file){
            
             const reader = new FileReader();
             reader.onload = function(){
               const result = reader.result;
               img.src = result;
               
               wrapper.classList.add("active");
             }
             
             reader.readAsDataURL(file);
           }
           if(this.value){
            let valueStore = this.value.match(regExp);
             fileName.textContent = valueStore;
             document.getElementById("borderDot").style.borderColor = "green";
            document.getElementById("custom-btn").style.background= "green";
            document.getElementById("custom-btn").innerText= "CHANGE   FILE ";
            
           }
           
    });

        
    defaultBtn2.addEventListener("change", function(){

            const file = this.files[0];
            if(file){
                const reader = new FileReader();
                reader.onload = function(){
                    const result = reader.result;
                        img.src = result;
                        wrapper.classList.add("active");
                }
    
                reader.readAsDataURL(file);
            }
            if(this.value){
              let valueStore = this.value.match(regExp);
              fileName2.textContent = valueStore;
              document.getElementById("borderDot2").style.borderColor = "green";
              document.getElementById("custom-btn2").style.background= "green";
              document.getElementById("custom-btn2").innerText= "CHANGE   FILE ";
            }
    });


    defaultBtn3.addEventListener("change", function(){
            const file = this.files[0];
            if(file){
               const reader = new FileReader();
                reader.onload = function(){
                const result = reader.result;
                 img.src = result;
                 wrapper.classList.add("active");
                }
                reader.readAsDataURL(file);
              }
            if(this.value){
                let valueStore = this.value.match(regExp);
                fileName3.textContent = valueStore;
                document.getElementById("borderDot3").style.borderColor = "green";
                document.getElementById("custom-btn3").style.background= "green";
                document.getElementById("custom-btn3").innerText= "CHANGE   FILE ";
            }
    });

         
    export default {
        name: 'upload',
    }
</script>

<style>
    .btn-grad{
          background-image: linear-gradient(to right, #e97923 0%, #e97923 30%, #efa81d   100%)
    }
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
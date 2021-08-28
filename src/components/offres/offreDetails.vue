<template>
    <div>
        <main>
            <div class="container">
                <div class="row">
                    <div class="col">
                        <div class="card  shadow" style="width: 100%;">
                            <img src="summer.jpg" class="card-img-top ">
                            <div class="card-body">
                                <div class="row pr-2 pl-2 ">
                                    <div>
                                        <div class="m-2  mb-0 ">
                                            <a href="#">
                                                <div class="d-flex">
                                                    <p>Offers list</p>
                                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-return-left" viewBox="0 0 16 16" style="margin-top: 5px;margin-left:5px">
                                                        <path fill-rule="evenodd" d="M14.5 1.5a.5.5 0 0 1 .5.5v4.8a2.5 2.5 0 0 1-2.5 2.5H2.707l3.347 3.346a.5.5 0 0 1-.708.708l-4.2-4.2a.5.5 0 0 1 0-.708l4-4a.5.5 0 1 1 .708.708L2.707 8.3H12.5A1.5 1.5 0 0 0 14 6.8V2a.5.5 0 0 1 .5-.5z"/>
                                                    </svg>
                                                </div>
                                            </a>
                                            <h3 class="mt-2" style="color: #2e5083;">Offer Name</h3>
                                        </div>
                                        <div class="m-2 ">
                                            <div>
                                                <h5 style="float: left; color: #2e5083;">Remaining places : &nbsp;</h5>
                                                <h5 style="color:  #212529;" class="job">3</h5>
                                            </div>
                                            <div>
                                                <h5 style="  float : left ;color: #2e5083  ">End date : &nbsp;
                                                </h5>
                                                <h5 style=" color: #212529;">20/09/2021 &nbsp;
                                                </h5>
                                            </div>
                                            <div>
                                                <h5 style="color: #2e5083 ">Description : &nbsp;
                                                </h5>
                                                <p class="mt-1">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                                Fuga id hic iure
                                                delectus
                                                minus ipsa soluta quos. Commodi quo eos ducimus aut, est, tempore
                                                quisquam sunt
                                                aspernatur harum quis pariatur. Lorem ipsum, dolor sit amet consectetur
                                                adipisicing elit.
                                                Repudiandae laborum
                                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repudiandae
                                                laborum
                                                adipisci voluptatum architecto possimus corporis vel impedit! Dolor
                                                similique
                                                explicabo dolores architecto nostrum quia mollitia, adipisci saepe ullam
                                                earum.
                                                Debitis. Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero
                                                nemo quam corporis
                                                alias sint aspernatur, quasi reprehenderit iusto, doloremque blanditiis
                                                in? Eligendi
                                                inventore dolore nemo quos ab quae dolores enim.</p>
                                            </div>
                                        </div>
                                        <div class="modal-footer ">
                                            <button type="button" class="btn btn1" data-bs-toggle="modal" data-bs-target="#exampleModal">Inlist now</button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Modal -->
            <div class="modal fade " id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content" style="background : #e9ecef">
                        <div class="row">
                            <div class="col-6" style="float: left !important;">
                                <a href="offers.html" id="list">
                                    <div class="d-flex p-4 pt-3">
                                        <p>Offers list</p>
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-return-left " viewBox="0 0 16 16" style="margin-top: 5px;margin-left:5px">
                                            <path fill-rule="evenodd" d="M14.5 1.5a.5.5 0 0 1 .5.5v4.8a2.5 2.5 0 0 1-2.5 2.5H2.707l3.347 3.346a.5.5 0 0 1-.708.708l-4.2-4.2a.5.5 0 0 1 0-.708l4-4a.5.5 0 1 1 .708.708L2.707 8.3H12.5A1.5 1.5 0 0 0 14 6.8V2a.5.5 0 0 1 .5-.5z" />
                                        </svg>
                                    </div>
                                </a>
                                <h3 class="modal-title ml-4 pt-0" style="color: #000000; padding-top: 0 !important;" id="exampleModalLabel">Offer Name</h3>
                            </div>
                            <div class="col-6" style="float: right !important;">
                                <a href="#" data-bs-dismiss="modal" aria-label="Close" style="float: right;">
                                    <img id="closeIcon" src="close .png">
                                </a>
                            </div>
                        </div>
                        <div class="modal-body">
                            <div class="m-2 mt-0 ">
                                <p class="pb-3" style="border-bottom: solid rgb(144, 144, 144) 1px;">
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta distinctio beatae
                                earum natus fuga voluptas! Omnis voluptatibus molestias quaerat esse impedit
                                accusantium earum, consequatur debitis sunt vel illum quisquam! Aperiam?
                                </p>
                                <p class="lead mt-3" style="color: rgb(8, 8, 8); font-weight: 300;">Required Documents:
                                </p>
                                <div class="form-group ">
                                    <!--  Documents -->
                                    <!---------- document 1 -------->
                                    <div class="row mt-4">
                                        <div class="col-5" id="borderDot" style="border: dashed #e97923 2px ; margin-left: 16px; margin-right: 40px">
                                            <div class="lead file-name" style="color: rgb(82, 80, 80); font-weight: 300;font-size: large; padding: 4px;"> certificat de naissance</div>
                                        </div>
                                        <div class="col-5">
                                            <button onclick="defaultBtnActive2()" id="custom-btn2" type="button" class="btn  pt-3 pb-3 pr-4 pl-4  btn-grad m-0" style="font-size:small" data-toggle="modal" data-target="#exampleModalCenter">Choose a file</button>
                                            <input id="default-btn" type="file" hidden>
                                        </div>
                                    </div>
                                    <div class="row mt-4">
                                        <div class="col-5" id="borderDot2" style="border: dashed #e97923 2px ; margin-left: 16px; margin-right: 40px">
                                            <div class="lead file-name2" style="color: rgb(82, 80, 80); font-weight: 300; padding: 4px;font-size: large;"> certificat de</div>
                                        </div>
                                        <div class="col-5">
                                            <button onclick="defaultBtnActive2()" id="custom-btn2" type="button" class="btn  pt-3 pb-3 pr-4 pl-4  btn-grad m-0" style="font-size:small" data-toggle="modal" data-target="#exampleModalCenter">Choose a file</button>
                                            <input id="default-btn2" type="file" hidden>
                                        </div>
                                    </div>
                                    <div class="row mt-4">
                                        <div class="col-5" id="borderDot3" style="border: dashed #e97923 2px ; margin-left: 16px; margin-right: 40px">
                                            <div class="lead file-name3" style="color: rgb(82, 80, 80); font-weight: 300; padding: 4px; font-size: large;"> 3a9d</div>
                                        </div>
                                        <div class="col-5">
                                            <button onclick="defaultBtnActive3()" id="custom-btn3" type="button" class="btn pt-3 pb-3 pr-4 pl-4 btn-grad m-0" style="font-size:small" data-toggle="modal" data-target="#exampleModalCenter">Choose a file</button>
                                            <input id="default-btn3" type="file" hidden>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </div>
                        <div class="modal-footer mt-0" style="margin: auto !important; max-width: 200px !important;">
                            <button type="button" class="btn  btn-grad  ">Add offer </button>
                        </div>
                    </div>
                </div>
            </div>
        </main>
    </div>
</template>

<script>
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
    function defaultBtnActive() {
            defaultBtn.click();
    }
    function defaultBtnActive2() {
            defaultBtn2.click();
    }
    function defaultBtnActive3() {
            defaultBtn3.click();
    }
    defaultBtn.addEventListener("change", function () {

            const file = this.files[0];
            if (file) {

                const reader = new FileReader();
                reader.onload = function () {
                    const result = reader.result;
                    img.src = result;

                    wrapper.classList.add("active");
                }

                reader.readAsDataURL(file);
            }
            if (this.value) {
                let valueStore = this.value.match(regExp);
                fileName.textContent = valueStore;
                document.getElementById("borderDot").style.borderColor = "green";
                document.getElementById("custom-btn").style.background = "green";
                document.getElementById("custom-btn").innerText = "CHANGE   FILE ";

            }

    });
    defaultBtn2.addEventListener("change", function () {

            const file = this.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function (){
                    const result = reader.result;
                    img.src = result;
                    wrapper.classList.add("active");
                }

                reader.readAsDataURL(file);
            }
            if (this.value) {
                let valueStore = this.value.match(regExp);
                fileName2.textContent = valueStore;
                document.getElementById("borderDot2").style.borderColor = "green";
                document.getElementById("custom-btn2").style.background = "green";
                document.getElementById("custom-btn2").innerText = "CHANGE   FILE ";
            }
    });
    defaultBtn3.addEventListener("change", function () {

            const file = this.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function () {
                    const result = reader.result;
                    img.src = result;
                    wrapper.classList.add("active");
                }

                reader.readAsDataURL(file);
            }
            if (this.value) {
                let valueStore = this.value.match(regExp);
                fileName3.textContent = valueStore;
                document.getElementById("borderDot3").style.borderColor = "green";
                document.getElementById("custom-btn3").style.background = "green";
                document.getElementById("custom-btn3").innerText = "CHANGE   FILE ";
            }
    });

    export default {
        name: 'offreDetails',
    }
</script>

<style>
    .card-img-top {
                height: 150px;
                object-fit: cover;
    }
    .btn1 {
                background: white;
                border-radius: 0.2rem;
                border-color: #2e5083;
                color: #2e5083;
                justify-content: end !important;
                font-size: 1rem;
                font-weight: 250 !important;
    }
    .btn1:hover {
                background: #2e5083 !important;
                color: white !important;
    }
    .modal-footer {
                border-top: none !important;
    }
    .modal-header {
                border-bottom: none;
    }
    .btn-grad {
                color: white;
                background: #e97923;
                font-weight: 200;
    }
    .btn-grad:hover {
                color: white;
                background: #d89716;
    }
    #list {
                text-decoration: underline;
                color: #e97923;
                padding-bottom: 0px !important;
    }
    #list:hover {
                color: #efa81d;
                text-decoration: underline;
    }
    #closeIcon {
                width: 20px;
                height: 20px;
                margin: 15px;
    }
    #closeIcon:hover {
                color: rgb(255, 255, 255);
    }
</style>
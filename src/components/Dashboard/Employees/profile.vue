<template>
    <div>
        <div class="container-fluid pt-5 pb-5 " style="background: #ffffff;">

            <div class="container shadow  " style="background: #ffffff; border: solid #ffffff 2px; border-radius: 8px; ">
                <div class="row  ">
                    <div class="col-md-5 mt-3 " style="text-align: center;">
                        <img src="khaled.jpg.png" alt="Avatar" class="avatar m-4">
                        <h4 style="font-weight: bold;">Khaled Farek</h4>
                        <h5 style="color: grey;" class="requestsType">Agent</h5>
                    </div>
                    <div class="col-md-7 mt-5 mb-5 ">
                        <div class="row m-2 ml-4 shadow" style="background: #ffffff; height: max-content; border-radius: 5px;">
                            <div class="col-6 pt-2 pt-2">
                                <h6 > Date de naissance :</h6>
                            </div>
                            <div class="col-6 pt-2 pt-2">
                                <h6 > 27/06/1999 </h6>
                            </div>
                        </div>
                        <div class="row m-2 ml-4 shadow" style="background: #ffffff; height: max-content; border-radius: 5px ;">
                            <div class="col-6 pt-2 pt-2">
                                <h6 > Professional email :</h6>
                            </div>
                            <div class="col-6 pt-2 pt-2 ">
                                <h6 > name.name@gmail.com </h6>
                            </div>
                        </div>
                        <div class="row m-2 ml-4 shadow" style="background: #ffffff; height: max-content; border-radius: 5px;">
                            <div class="col-6 pt-2 pt-2">
                                <h6 > CCP account :</h6>
                            </div>
                            <div class="col-6 pt-2 pt-2">
                                <h6 > 154755974002 </h6>
                            </div>
                        </div>
                        <div class="row m-2 ml-4 ">
                            <div class="col-10 shadow" style="background: #ffffff; height: max-content; border-radius: 5px;">

                                <h6 class="pt-2 pt-2" style="vertical-align: middle;float: left;">
                                    Password : </h6>

                                <div class="pt-2 pb-2" style="float: right;">

                                    <input style="border: none;" type="password" value="FakePSWFakePSW" id="myInput">
                                    <i class="far fa-eye" id="togglePassword" onclick="myFunction()"></i>
                                </div>
                            </div>
                            <div class="col-2 pt-2" style="float: right;">
                                <button type="button" class="btn btnEdit mr-0" data-bs-toggle="modal"
                                    data-bs-target="#exampleModal">Edit</button>
                            </div>
                        </div>
                        <div class="row mr-0 m-2 ">
                            <div class="modal-footer mr-0">
                                <button type="button" class="btn btnM ">Report mistake</button>
                                <button type="button" class="btn btnD mr-0">Done</button>
                            </div>

                        </div>
                    </div>
                </div>


                <!-- Modal -->
                <div class="modal fade " id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                    aria-hidden="true">
                    <div class="modal-dialog modal-sm">
                        <div class="modal-content ">
                            <div class="modal-header">

                                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                            </div>
                            <div class="modal-body">
                                <div class="col-auto">
                                    <label for="inputPassword2" class="visually-hidden">new password</label>
                                    <input type="password" class="form-control" id="inputPassword2"
                                        placeholder="new password">
                                </div>
                                <div class="col-auto mt-3">
                                    <label for="inputPassword2" class="visually-hidden">confirm password</label>
                                    <input type="password" class="form-control" id="inputPassword2"
                                        placeholder="confirm password">
                                </div>
                            </div>
                            <div class="modal-footer modal-footer1 mr-3">
                                <button type="button" class="btn btnD" data-bs-dismiss="modal">Save</button>
                                <button type="button" class="btn btnM">Cancel</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    function myFunction() {
        var x = document.getElementById("myInput");
        if (x.type === "password") {
                x.type = "text";
            } else {
                x.type = "password";
            }
    }
    export default {
        name: 'profile'
    }
</script>

<style>
    
    .avatar {
        vertical-align: middle;
        width: 150px;
        height: 150px;
        padding: 8px;
        border: 1px;
        border-radius: 50%;
        border-color: #0e1e58;
    }
    html,
    body {
        height: 100%;
        margin: 0px;
    }
    .container-fluid {
        height: 100% !important;
    }
    .btnD {
        color: #ffffff;
        background-image: linear-gradient(to right, #2e5083 0%, #2e5083 30%, #0e1e58 100%);
        border-radius: 3px;
        transition: 0.5s;
        font-size: 0.9rem;
        background-size: 200% auto;

    }
    .btnD:hover {
        background-position: right center;
        /* change the direction of the change here */
        color: #fff;
        text-decoration: none;
    }
    .btnEdit {
        color: #ffffff;
        background-image: linear-gradient(to right, #2e5083 0%, #2e5083 30%, #0e1e58 100%);
        border-radius: 3px;
        transition: 0.5s;
        font-size: 0.7rem;
        background-size: 200% auto;
        padding: 5px 20px;
        float: right;
    }
    .btnEdit:hover {
        background-position: right center;
        /* change the direction of the change here */
        color: #fff;
        text-decoration: none;
    }
    .btnM {
        color: #ffffff;
        background-image: linear-gradient(to right, #e97923 0%, #e97923 30%, #efa81d 100%);
       /* background-image: linear-gradient(to right, #FF6B6B 0%, #FF6B6B 30%, #B61919 100%);*/
        border-radius: 3px;
        transition: 0.5s;
        font-size: 0.9rem;
        background-size: 200% auto;
    }
    .btnM:hover {
        background-position: right center;
        /* change the direction of the change here */
        color: #fff;
        text-decoration: none;
    }
    .modal-header {
        border-bottom: none;
    }
    .modal-footer {
        border-top: none;
    }
    .modal-footer1 {
        border-top: none;
    }
    #togglePassword {
        cursor: pointer;
    }
</style>
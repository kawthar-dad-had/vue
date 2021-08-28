<template>
    <div>
        <header>
            <div class="container mb-5 " style="margin: auto; max-width: 1000px;">
                <div class="row mb-5">
                    <div class="col-8  pt-0 ">
                        <div style="padding-top: 10px;">
                            <h2 style="color: #e97923 ; ">Requests</h2>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <main>
            <div class="container " style="margin: auto; max-width: 1000px;">
                <div class="row   mb-5 ">
                    <div class="col-10">
                        <div class="card shadow" style="border-left: solid #e97923 50px;">
                            <div>
                                <img src="user(1).png" alt="Avatar" class="avatar m-4 " style="float: left;">
                                <div class="m-5" style="float: right;">
                                    <button type="button" class="btn moreBtn" style="color: white;" data-bs-toggle="modal" data-bs-target="#exampleModal">see more</button>
                                </div>
                                <div class="m-4 pt-2 ">
                                    <h3>Full Name</h3>
                                    <p style="color: grey;" class="requestsType">requests type</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row   mb-5 ">
                    <div class="col-10">
                        <div class="card shadow" style="border-left: solid #e97923 50px;">
                            <div>
                                <img src="user(1).png" alt="Avatar" class="avatar m-4" style="float: left;">
                                <div class="m-5" style="float: right;">
                                    <button type="button" class="btn moreBtn" style="color: white;" data-bs-toggle="modal" data-bs-target="#exampleModal">see more</button>
                                </div>
                                <div class="m-4 pt-2 ">
                                    <h3>Full Name</h3>
                                    <p style="color: grey;" class="requestsType">requests type</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row   mb-5 ">
                    <div class="col-10">
                        <div class="card shadow" style="border-left: solid #e97923 50px;">
                            <div>
                                <img src="user(1).png" alt="Avatar" class="avatar m-4" style="float: left;">
                                <div class="m-5" style="float: right;">
                                    <button type="button" class="btn moreBtn" style="color: white;" data-bs-toggle="modal" data-bs-target="#exampleModal">see more</button>
                                </div>
                                <div class="m-4 pt-2 ">
                                    <h3>Full Name</h3>
                                    <p style="color: grey;" class="requestsType">requests type</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Modal -->
                <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                    <div class="modal-dialog">
                        <div class="modal-content">
                            <div class="modal-header">
                                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                            </div>
                            <div class="modal-body mt-0">
                                <img src="user(1).png" alt="Avatar" class="avatar m-4 p-3" style="float: left;">
                                <div class="m-4 pt-2 ">
                                    <h3 style="color: #0e1e58;">Full Name</h3>
                                    <p class="requestsType" style="color: grey;">job</p>
                                </div>
                                <div class="m-4 pt-2 ">
                                    <h4 style="float: left; color: rgb(95, 91, 91);">Request : &nbsp;</h4>
                                    <h4 style="color:  #0e1e58;" class="job">Request type</h4>
                                    <h4 style=" color: rgb(95, 91, 91); margin-top: 20px; ">Documents : &nbsp;</h4>
                                    <div style="margin: auto; max-width: 350px;" class="mt-3 mb-3">
                                        <a href="naiss.jpg" data-lightbox="myFiles">
                                            <div class="m-2 " style="border: dashed grey 1px;float: left;">
                                                <img src="naiss.jpg" alt="Avatar" class="  file ">
                                            </div>
                                        </a>
                                        <a href="naiss.jpg" data-lightbox="myFiles">
                                            <div class="m-2 files" style="border: dashed grey 1px;float: left;">
                                                <img src="naiss.jpg" alt="Avatar" class=" file">
                                            </div>
                                        </a>
                                        <a href="file.png" data-lightbox="myFiles">
                                            <div class="m-2" style="border: dashed grey 1px;float: left;">
                                                <img src="file.png" alt="Avatar" class="  file">
                                            </div>
                                        </a>
                                        <!--
                                            <a href="naiss.jpg" data-lightbox = "myFiles">
                                                <div class="m-2 " style="border: dashed grey 1px;float: left;">
                                                    <img src="naiss.jpg" alt="Avatar" class="  file ">
                                                </div>
                                            </a>
                                            <a href="file.png" data-lightbox = "myFiles">
                                                <div class="m-2 files" style="border: dashed grey 1px;float: left;">
                                                    <img src="file.png" alt="Avatar" class="  file">
                                                </div>
                                            </a>
                                            <a href="file.png" data-lightbox = "myFiles">
                                                <div class="m-2 files" style="border: dashed grey 1px;float: left;">
                                                    <img src="file.png" alt="Avatar" class="  file">
                                                </div>
                                            </a>
                                        -->
                                    </div>

                                </div>
                            </div>
                            <div class="modal-footer">
                                <button style="background: #2e5083;color: white;" type="button" class="btn " data-bs-toggle="modal" data-bs-target="#staticBackdrop">Accept</button>
                                <!--   Accept -->
                                <div class="modal fade " id="staticBackdrop" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true" style="justify-self: center !important;">
                                    <div class="modal-dialog">
                                        <div class="modal-content" id="accept" style="background: white ; width: 80%;">
                                            <div class="modal-header">
                                                <h5 class="modal-title" id="title" style="color: rgb(0, 0, 0);margin: auto; max-width: 400px;">Are you sure you want to accept ?</h5>
                                                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                                            </div>
                                            <div class="modal-footer" style="margin: auto; max-width: 300px;">
                                                <button style="color: white; background: #2e5083; border-color: #2e5083;" type="button" class="btn " data-bs-dismiss="modal">Accept</button>
                                                <button type="button" class="btn btn-primary " style="color: white;background: #e97923; border-color: #e97923;">Cancel</button>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <!-- end  Accept -->
                                <button style="background: #e97923; color: white;" type="button" data-bs-toggle="modal" data-bs-target="#staticBackdrop1" class="btn ">Refuse</button>
                                <!-- Refuse Mdel -->
                                <div class="modal fade " id="staticBackdrop1" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true" style="justify-self: center !important;">
                                    <div class="modal-dialog">
                                        <div class="modal-content" id="refuse" style="background: white ; width: 80%;">
                                            <div class="modal-header">
                                                <h5 class="modal-title" id="title" style="color: rgb(0, 0, 0);margin: auto; max-width: 400px;">Are you sure you want to refuse ?</h5>
                                                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                                            </div>
                                            <div class="modal-footer" style="margin: auto; max-width: 300px;">
                                                <button style="color: white; background: #2e5083; border-color: #2e5083;" type="button" class="btn " data-bs-dismiss="modal">Refuse</button>
                                                <button type="button" class="btn btn-primary " style="color: white;background: #e97923; border-color: #e97923;">Cancel</button>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Refuse Mdel -->
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </main>
    </div>
</template>

<script>
    export default {
        name: 'request',
    }
</script>

<style>
    .avatar {
            vertical-align: middle;
            width: 80px;
            height: 80px;
            padding: 8px;
            border: 1px;
            border-color: #0e1e58;
    }
    .file {
            vertical-align: middle;
            width: 95px;
            height: 95px;

            border: 1px;
            border-color: #0e1e58;

    }
    .btn {

            font-size: 1.2rem;
    }
    .file:hover {
            filter: grayscale(100%);
            transform: scale(1.1);
    }
    .modal-header {
            border-bottom: none !important;
    }
    .modal-footer {

            border-top: none !important;
    }
    #staticBackdrop {
            
            background: rgb(32, 32, 32, 0.6);
    }
    #accept{
            transform: translate(10%,50%);
    }
    #staticBackdrop1 {

            background: rgb(32, 32, 32, 0.6);
    }
    #refuse{
            transform: translate(10%,50%);
    }
    .moreBtn {
            background: #e97923;
            font-size: 1rem;
            font-family: Arial, Helvetica, sans-serif;
    }
    .moreBtn:hover {
            background: #e7a625;
            color: white;

    }
</style>
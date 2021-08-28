<template>
    <div>
        <div class="container shadow mt-4 pl-5 pr-5 " >
            <div class="row mt-5 mb-5" style="text-align: center;">
               
                <h1>Contact Us</h1>
            </div>
            <div class="row mt-5 ">
                <div class="col">
                    <div class="mb-3 ">
                        <label for="formGroupExampleInput" class="form-label required">FIRST NAME&nbsp;</label>
                        <input type="text" class="form-control shadow" id="formGroupExampleInput" placeholder="first name">
                    </div>
    
                </div>
                <div class="col">
                    <div class="mb-3">
                        <label for="formGroupExampleInput" class="form-label required">FAMILY NAME&nbsp;</label>
                        <input type="text" class="form-control shadow" id="formGroupExampleInput" placeholder="family name">
                    </div>
                </div>
            </div>
            <div class="row ">
                <div class="mb-3">
                    <label for="exampleFormControlInput1" class="form-label required">Email address&nbsp;</label>
                    <input type="email" class="form-control shadow" id=" exampleFormControlInput1"
                        placeholder="name@example.com">
                </div>
    
                <div class="mb-3 ">
                    <label for="exampleFormControlTextarea1" class="form-label required">Message </label>
                    <textarea class="form-control shadow" id="exampleFormControlTextarea1" rows="3"></textarea>
                </div>
            </div>
            <div class="modal-footer m-4 mr-0 pr-0">
    
                <button style="float: right;" type="button" class="btn btnS ">Send Message</button>
    
    
            </div>
        </div>
    </div>
</template>

<script>
    export default {
       name: 'contact' 
    }
</script>

<style>
    .btnS {
        color: #ffffff;
        background-image: linear-gradient(to right, #2e5083 0%, #2e5083 30%, #0e1e58 100%);
        border-radius: 3px;
        transition: 0.5s;
        font-size: 0.9rem;
        background-size: 200% auto;
        width: max-content;
        padding: 10px 30px;

    }
    .btnS:hover {
        background-position: right center;
        /* change the direction of the change here */
        color: #fff;
        text-decoration: none;
    }
    .modal-footer {
        border-top: none;
    }
    .required:after {
        content: " *";
        color: red;
    }
</style>
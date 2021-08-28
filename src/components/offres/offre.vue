<template>
    <div>
        <header>
            <div class="container mb-3 ">
                <div class="row mb-5 " style="margin: auto; max-width: 1000px;">
                    <div class="col-8  pt-0 ">
                        <div style="padding-top: 10px;" class="ml-3 mt-2">
                            <h2 style="color: #2e5083 ; ">Offers</h2>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <main>
            <div class="container">
                <div class="row" style="margin: auto; max-width: 1000px;">
                    <!--   Card 1 -->
                    <div class="card m-3 shadow" style="width: 18rem;">
                        <img src="summer.jpg" class="card-img-top ">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text"> <img src="stopwatch.png"> 3 days remaining !</p>
                            <a href="offerDetails.html" class="btn mt-3 " style="float: right;">Apply now</a>
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
        </main>
    </div>
</template>

<script>
    export default {
        name: 'offre',

    }
</script>

<style>
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
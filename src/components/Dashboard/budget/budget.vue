<template>
    <div>   
        <header>
            <div class="container mb-5">
                <div class="row mb-5" >
                    <div class="col-8  pt-0 "> 
                        <div style="padding-top: 10px;" >
                            <h2  style="color: #2e5083 ; ">Budget</h2>
                        </div>
                    </div>
                </div>
                <div class="row pl-2 pr-2">
                    <div class="col-md-8 p-0">
                        <div class="card" >
                            <div class="card-body shadow "  >
                                <h5 class="card-title" style="padding: 5px;color:#2e5083 ;">Total Budget</h5>
                                <h2 style="padding-left: 10px;padding: 5px;color: #2e5083;">3548200,00DA</h2>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 p-0">
                        <div class="card" >
                            <div class="card-body shadow  "  >
                                <h5 class="card-title" style="padding: 5px; color:rgba(255, 99, 132, 0.8) ;">Spent Budget</h5>  
                                <h2 style="padding-left: 10px;padding: 5px;color: rgba(255, 99, 132, 0.8);">27000,00DA</h2>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </header>

        <main>
            <div class="container">
                <div class="row ">
                    <div class="col-md-8  " style="margin: auto; max-width: 750px;">
                        <div class="form-group mb-4 mt-0 " >
                            <select id="inputState" class="form-select shadow" style="padding: 20px;margin-bottom: 50px;font-size: 20px;">
                                <option selected>compensations spending</option>
                                <option class="uneditable-input">donation</option>
                                <option class="uneditable-input">donation</option>
                                <option class="uneditable-input">All spending</option>
                            </select>
                        </div>
                        <div class="card h-100 shadow">
                            <div class="card-body">
                                <canvas id="myChart" style="padding: 20px;"></canvas>
                            </div>
                        </div> 
                    </div>
                    <div class="col-md-4" >
                        <div class="card " style="margin-left: 0; margin-right: 0;margin-top: 40px;">
                            <div class="card-body shadow">
                                <canvas id="pieChart" ></canvas> 
                            </div>
                        </div>
                        <div class="card " style="margin-left: 0; margin-right: 0;margin-bottom: 40px;margin-top: 30px;">
                            <div class="card-body shadow">
                                <canvas id="barChart" ></canvas>
                            </div>
                        </div>
                    </div>
                </div> 
                <div class="row mb-5" >
                    <div class="col-8  pt-0 "> 
                        <div style="padding-top: 10px;" >
                            <h2  style="color: #2e5083 ; ">Details</h2>
                        </div>
                     </div>
                </div>
                <div class="row mb-5 ">
                    <div class="col-12">
                        <div class="card shadow" style="border-left: solid #2e5083 50px;" >
                            <div>
                                <img src="user(1).png" alt="Avatar" class="avatar m-4" style="float: left;">
                                <div class="m-4" style="float: right;">
                                    <h4>Money</h4>
                                    <h5>Date</h5>
                                </div>
                                <div class="m-4" >
                                    <h3 >Full Name</h3>
                                    <p>Agent</p>
                                </div>
                            </div>
                        </div>
                    </div>   
                </div>
                <div class="row mb-5 ">
                    <div class="col-12">
                        <div class="card shadow" style="border-left: solid #2e5083 50px;" >
                            <div >
                                <img src="user(1).png" alt="Avatar" class="avatar m-4" style="float: left;">
                                <div class="m-4" style="float: right;">
                                    <h4>Money</h4>
                                    <h5>Date</h5>
                                </div>
                                <div class="m-4" >
                                    <h3 >Full Name</h3>
                                    <p>Agent</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row mb-5 ">
                    <div class="col-12">
                        <div class="card shadow" style="border-left: solid #2e5083 50px;" >
                            <div >
                                <img src="user(1).png" alt="Avatar" class="avatar m-4" style="float: left;">
                                <div class="m-4" style="float: right;">
                                    <h4>Money</h4>
                                    <h5>Date</h5>
                                </div>
                                <div class="m-4" >
                                    <h3 >Full Name</h3>
                                    <p>Agent</p>

                                </div>
                            </div>
                        </div>
                     </div>
                </div>
             </div>
        </main> 
    </div>
</template>

<script>
    var ctx = document.getElementById('myChart').getContext('2d');
    var piec = document.getElementById('pieChart').getContext('2d');
    var barc = document.getElementById('barChart').getContext('2d');
    var myChart = new Chart(ctx, {
        type: 'line',
        data: {
            labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
            datasets: [{
                label: '# of Votes',
                
                data: [12, 19, 3, 5, 2, 3],
                backgroundColor: [
                    'rgba(255, 99, 132, 0.2)',
                    'rgba(54, 162, 235, 0.2)',
                    'rgba(255, 206, 86, 0.2)',
                    'rgba(75, 192, 192, 0.2)',
                    'rgba(153, 102, 255, 0.2)',
                    'rgba(255, 159, 64, 0.2)'
                ],
                borderColor: [
                    'rgba(255, 99, 132, 1)',
                    'rgba(54, 162, 235, 1)',
                    'rgba(255, 206, 86, 1)',
                    'rgba(75, 192, 192, 1)',
                    'rgba(153, 102, 255, 1)',
                    'rgba(255, 159, 64, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true
                }
            }
        }
    });
    var pieChart = new Chart(piec, {
        type: 'pie',
        data: {
            labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
            datasets: [{
                label: '# of Votes',
                data: [12, 19, 3, 5, 2, 3],
                backgroundColor: [
                'rgba(255, 99, 132, 0.5)',
                    'rgba(54, 162, 235, 0.5)',
                    'rgba(255, 206, 86, 0.5)',
                    'rgba(75, 192, 192, 0.5)',
                    'rgba(153, 102, 255, 0.5)',
                    'rgba(255, 159, 64, 0.5)'
                ],
                borderColor: [
                    'rgba(255, 99, 132, 1)',
                    'rgba(54, 162, 235, 1)',
                    'rgba(255, 206, 86, 1)',
                    'rgba(75, 192, 192, 1)',
                    'rgba(153, 102, 255, 1)',
                    'rgba(255, 159, 64, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true
                }
            }
        }
    });
    var barChart = new Chart(barc, {
        type: 'bar',
        data: {
            labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
            datasets: [{
                label: '# of Votes',
                axis: 'y',
                data: [12, 19, 3, 5, 2, 3],
                backgroundColor: [
                    'rgba(255, 99, 132, 0.5)',
                    'rgba(54, 162, 235, 0.5)',
                    'rgba(255, 206, 86, 0.5)',
                    'rgba(75, 192, 192, 0.5)',
                    'rgba(153, 102, 255, 0.5)',
                    'rgba(255, 159, 64, 0.5)'
                ],
                borderColor: [
                    'rgba(255, 99, 132, 1)',
                    'rgba(54, 162, 235, 1)',
                    'rgba(255, 206, 86, 1)',
                    'rgba(75, 192, 192, 1)',
                    'rgba(153, 102, 255, 1)',
                    'rgba(255, 159, 64, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            indexAxis: 'y',
        }
    });
    export default {
        name: 'budget',
    }
</script>

<style>
    .avatar {
        vertical-align: middle;
        width: 80px;
        height: 80px;
        border-radius: 50%;
        border: 1px;
        border-color: #0e1e58;
    } 
</style>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css" />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet" />
    <style>
        .container {
            width: 100%;
            height: 100%;
            /* background-color: #f9f9f9; */
            /* border: 1px solid #ddd; */
            border-radius: 8px;
            padding: 25px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-top: 25px;
        }

        .grid-container {
            display: grid;
            grid-template-columns: auto auto auto;
            /* background-color: #2196F3; */
            padding: 10px;
        }

        .grid-item {
            background-color: rgba(255, 255, 255, 0.8);
            border: 1px solid lightblue;
            padding: 5px;
            font-size: 15px;
            text-align: center;
            color: blue;
        }

        .custom-card {
            background-color: #e8f4ff;
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 50px;
            
        }

        .custom-card h5 {
            color: #d62828;
            font-weight: bold;
            font-size: 1.5rem;

            /* background-color: rgb(200, 255, 0); */
            /* border: opx solid black; */
            /* width: 10px; */
        }

        .time-text {
            color: #555;
            font-size: 18px;
        }
        .total-card{
       /* color: linear-gradient(skyblue,white); */
            border-right: 2px solid skyblue;
        }

        .custom-card .triangle {
            width: 0;
            height: 0;
            border-left: 40px solid transparent;
            border-right: 40px solid transparent;
            border-bottom: 70px solid #fca311;
            position: absolute;
            bottom: 10px;
            left: 12%;
            top: 35%;
            transform: translate(50%, 50%);
        }

        .custom-card .circle {
            width: 65px;
            height: 60px;
            background-color: #004080;
            color: white;
            font-size: 24px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            position: absolute;
            bottom: 30px;
            left: 17.3%;
            top: 41%;
            transform: translateX(-50%);
        }

        .custom-card .triangle1 {
            width: 100;
            height: 0;
            border-left: 40px solid transparent;
            border-right: 40px solid transparent;
            border-bottom: 70px solid #fca311;
            position: absolute;
            /* bottom: 10px; */
            left: 34%;
            top: 39%;
            transform: translate(50%, 0%);
        }

        .custom-card .circle1 {
            width: 65px;
            height: 60px;
            background-color: #004080;
            color: white;
            font-size: 24px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            position: absolute;
            bottom: 30px;
            left: 35%;
            top: 41%;
            transform: translate(50%);
        }

        .custom-card .triangle2 {
            width: 100;
            height: 0;
            border-left: 40px solid transparent;
            border-right: 40px solid transparent;
            border-bottom: 70px solid #fca311;
            position: absolute;
            /* bottom: 10px; */
            left: 34%;
            top: 64%;
            transform: translate(50%, 50%);
        }

        .custom-card .circle2 {
            width: 65px;
            height: 60px;
            background-color: #004080;
            color: white;
            font-size: 24px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            position: absolute;
            bottom: 30px;
            left: 35%;
            top: 66%;
            transform: translate(50%, 50%);
        }

        .custom-card .triangle3 {
            width: 100;
            height: 0;
            border-left: 40px solid transparent;
            border-right: 40px solid transparent;
            border-bottom: 70px solid #fca311;
            position: absolute;
            /* bottom: 10px; */
            left: 12%;
            top: 64%;
            transform: translate(50%, 50%);
        }

        .custom-card .circle3 {
            width: 65px;
            height: 60px;
            background-color: #004080;
            color: white;
            font-size: 24px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            position: absolute;
            left: 13%;
            top: 66%;
            transform: translate(50%, 50%);
        }
        .right h3{
         border-top-right-radius: 34px;
        }
        .content{
            text-align: justify;
        }
        
        /* ul {
      list-style: none; 
    } */

    /* ul li {
      position: relative;
      color: black; 
      margin-left: 20px;
      font-weight:bold;
    }

    ul li::before {
      content: "•"; 
      color: red; 
      position: absolute;
      left: -20px; 
      font-size: 1.2em; 
    } */
   
        

        .footer-navbar{
            /* background-color: #002366; */
            
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <div class="grid-container mt-5">
                    <div class="grid-item">Yesterday</div>
                    <div class="grid-item">Today</div>
                    <div class="grid-item">Select Date</div>
                </div>


                <div class="row g-4 mt-2 total-card">

                    <!-- Card 1 -->
                    <div class="col-md-6">
                        <div class="custom-card">
                            <h5>GD BAZAR 02AM</h5>
                            <div class="time-text">02:00 AM</div>
                            <div class="triangle"></div>
                            <div class="circle">61</div>
                        </div>
                    </div>

                    <!-- Card 2 -->
                    <div class="col-md-6">
                        <div class="custom-card">
                            <h5>DESAWAR</h5>
                            <div class="time-text">05:00 AM</div>
                            <div class="triangle1"></div>
                            <div class="circle1">47</div>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div class="col-md-6 pt-5">
                        <div class="custom-card">
                            <h5>GD BAZAR 10AM</h5>
                            <div class="time-text">10:00 AM</div>
                            <div class="triangle2"></div>
                            <div class="circle2">56</div>
                        </div>
                    </div>

                    <!-- Card 4 -->
                    <div class="col-md-6 pt-5">
                        <div class="custom-card">
                            <h5>GD BAZAR 11AM</h5>
                            <div class="time-text">11:00 AM</div>
                            <div class="triangle3"></div>
                            <div class="circle3">94</div>
                        </div>
                    </div>
                </div>
                

            </div>
            <div class="col-md-6 mt-5">
             <div class="right mt-5">
              <h3 class="text-center text-light bg-danger p-1">RULES</h3>
              </div>
              <div class="content">
                <ul>
                    <li>Jodi Rate - 10 ka 950</li>
                    <li> Harup Rate - 100 ka 950</li>
                    <li>  Minimum add money 300. INR 24X7 Available</li>
                    <li> Minimum Widthdrawal money. 300 INR 24X7 Available</li>
                </ul>
               
               <span class="text-danger"> Jodi Rules</span>
                - Example Apne Goldstar Game pe 10rs ka 59 Jodi Lagaya Aur result open hojata h *59* Toh Apke wallet mai instant 950 credit hojayega jo ap kabhi bhi withdrwal kar skte ho apne Bank account mai <br> <br>
                
               <span class="text-danger">Harup Rules</span>  - Harup hote h 0 se 9 tak aur yeh ander bahr dono side laga skte hai example apne Goldstar game pr 9B 100rs Ka harup lagaya aur Result aaya 59 to apko 950 milega aur agr ap 9AB 100 ka dono side lagate hai to apka total amount 200 banega or result aajata h 99 to apko 1900 instant apke wallet m credit hojayega</div>
            </div>

        </div>
        <footer>
            
            <nav class="navbar navbar-expand-lg  footer-navbar">
                <div class="container-fluid">
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav">
                            <li class="nav-item">
                                <a class="nav-link" aria-current="page" href="#">HOME</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">STATEMENT</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">RESULT & RULES</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">HELP</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">PROFILE</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">REFER & EARN</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">PRIVACY POLICY</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">TERMS & CONDITION</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </footer>

        
        <!-- Bootstrap JS -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>

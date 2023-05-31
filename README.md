<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="header">
        WEATHER APP
    </div>
    <div class="bar">
        <div class="search">
            SEARCH WEATHER
        </div>
        <div class="yw">
            YOUR WEATHER
        </div>
    </div>
    <div class="navbar">
        <input type="text" placeholder="Search for city..." class="bar" id="sb">
        <div class="circle"> <img src="search.png"class="searching"></div>
    </div>
       <div class="img">
            <img src="location.png" class="loc" loading="lazy">
            Grant Location Access
            <button GA>Grant Access</button>
        </div>
        <div>
             <img src="loading.gif" id="loader">
        </div>

        <!--Show user weather info-->
        <div class="user-info">

            <!--USER CITY AND COUNTRY-->
            <div class="name">
                <p data-CityName></p>
                <img data-Country>
            </div>

            <!--USER WEATHER DESC AND ICON-->
            <p data-WeatherDesc></p>
            <img data-WeatherIcon>

            <!--TEMPERATURE-->
            <p class="temperature"></p>
        </div>
        <div class="boxes">
            <div class="ws"><img src="wind.png">
            WINDSPEED
        <p data-Windspeed></p>
    </div>
            <div class="cloud"><img src="cloud.png">
            CLOUDS
        <p class="showcloud"></p>
    </div>
            <div class="humidity"><img src="humidity.png">
            HUMIDITY
        <p data-Humidity></p>
    </div>
        </div>
        <script src="index.js"></script>
</body>
</html>

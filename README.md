# WebDesignChallenge.github-io

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <title>Latitude: Data</title>

    <!-- bootstrap css -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  
    <link rel="stylesheet" href="primary.css" media="screen">

</head>

<body class="bg-light">
    <nav class="navbar navbar-expand-lg navbar-light bg-white py-0">

        <a class="navbar-brand bg-info text-white p-2" href="index.html">Latitude</a>

        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">

        <span class="navbar-toggler-icon"></span>

        </button>

        <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
            <ul class="navbar-nav">
                <li class="nav-item active dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Plots</a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                        <a class="dropdown-item" href="maxtemp.html">Max Temperature</a>
                        <a class="dropdown-item" href="humidity.html">Humidity</a>
                        <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                        <a class="dropdown-item" href="wind.html">Wind Speed</a>
                    </div>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="comparisons.html">Comparisons</a>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="data.html">Data</a>
                </li>
            </ul>

        </div>

    </nav>

     <!-- main content -->
     <div class="container">
        <div class="row">
            <div class="col-md-12 col-lg-7 mt-5">
                <div class="card">
                    <h4 class="card-header text-info">Summary: Latitude vs. All Things Basic Weather</h4>
                    <div class="card-body">
                        <img id="img-wrap" class="img-fluid img-center" src="Resources/assets/images/Fig1.png" Title="Temperature" width="700">
                        <p class="card-text font-weight-light">The purpose of this project was to analyze the impact on weather the closer and farther away one is located relative to to the equator.  The project was based on a project we completed in the GA Tech Data Science and Analytics Bootcamp.</p>
                        <p class="card-text font-weight-light"> A component of that project was to build an API to pull weather data from OpenWeatherMap for 500 randomly selected cities.  Although we completed the project with more current data, cohorts were provided a standard data set dated 01/05/17 for the putposes of this project.</p>
                        <p class="card-text font-weight-light"> </p>
                        <p class="card-text font-weight-light">A series of plots to showcase the relationships regarding several variables were generated using Matplotlib. These plots are an analysis of the relationship between weather and latitude including: Temperature (F) vs. Latitude, Humidity (%) vs. Latitude, Cloudiness (%) vs. Latitude, and Wind Speed (mph) vs. Latitude. Data and visualizations are are provided as part of the analysis, including explanations and descriptions.</p>
                        <br>
                    </div>
                </div>
            </div>

            <div class="col-md-12 col-lg-5 mt-5">
                <div class="card">
                    <h4 class="card-header text-info">Visualizations</h4>
                    <div class="card-body">

                        <div class="row pb-3">
                            <div class="col-md-6">
                                <a href="maxtemp.html"><img class="img-fluid img-center viz-box" src="Resources/assets/images/Fig1.png" title="Maximum Temperature" width="600"></a>
                            </div>
                            <div class="col-md-6">
                                <a href="humidity.html"><img class="img-fluid img-center viz-box" src="Resources/assets/images/Fig2.png" title="Humidity" width="600"></a>
                            </div>
                        </div>
                        <div class="row pb-3">
                            <div class="col-md-6">
                                <a href="cloudiness.html"><img class="img-fluid img-center viz-box" src="Resources/assets/images/Fig3.png" title="Cloudiness" width="600"></a>
                            </div>
                            <div class="col-md-6">
                                <a href="wind.html"><img class="img-fluid img-center viz-box" src="Resources/assets/images/Fig4.png" title="Wind Speed" width="600"></a>
                            </div>
                        </div>
                    </div>


                </div>

            </div>

        </div>

    </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>


</body>
<div class="footer">
    <footer>Designed by Markus Stephen Shipley</footer>
    <footer>Georgia Tech Data Science and Analytics Bootcamp</footer>
    <footer>Copyright 2022</footer>
</footer>
</div>
</html>

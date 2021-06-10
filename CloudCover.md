<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Cloud Cover</title>

  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  <!-- <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script> -->

</head>

<!-- <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script> -->

<body>
  <!-- start nav bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index.html">Latitude</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
            aria-haspopup="true" aria-expanded="false">Plots</a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="CloudCover.html">Cloud Cover</a>
            <a class="dropdown-item" href="Humidity.html">Humidity</a>
            <a class="dropdown-item" href="Temperature.html">Temperature</a>
            <a class="dropdown-item" href="WindSpeed.html">Wind Speed</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="Comparison.html">Comparison</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="Data.html">Data</a>
        </li>
      </ul>
    </div>
  </nav>
  <!-- end nav bar -->

  <div class="container-fluid" id="box">
    <!-- Summary -->
    <div class="row">
      <div class="col-md-8">
        <div class="container-fluid">
          <div class="row">
            <div class="col-md-12">
              <h1 class="text-center">Impact of Latitude on Cloud Cover</h1>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <hr>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <img src="Visualizations/LatitudeVsCloudCover.png" class=img-fluid alt="Latitude vs Cloud Cover" align="left">
                <p>The purpose of this study was to determine the impact of moving latitude toward the equator on a
                variety of weather factors. To perform this analysis, data was pulled from the Opewn Weather Map API to
                assemble a dataset
                on over 500 cities around the world.
                <br>
                <br>
                After assembling the dataset, Matplotlib was used to plot various weather metrics atainst latitude,
                including percent cloud cover, humidity, maximum temperature, and wind speed.
                This site contains both visualizations and source data created during the analysis process, as well as
                explanations and descriptions of any trends and correlations witnessed.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <br>
            </div>
          </div>
        </div>
      </div>

      <!-- thumbnails  -->
      <div class="col-md-4">
        <div class="container-fluid">
          <h3 class="text-center">Visualizations</h3>
          <div class="row">
            <div class="col-md-6">
              <div class="thumbnail">
                <a href="CloudCover.html">
                  <img src="Visualizations/LatitudeVsCloudCover.png" class="img-thumbnail">
                </a>
              </div>
            </div>
            <div class="col-md-6">
              <div class="thumbnail">
                <a href="Humidity.html">
                  <img src="Visualizations/LatitudeVsHumidity.png" class="img-thumbnail">
                </a>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <br>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div class="thumbnail">
                <a href="Temperature.html">
                  <img src="Visualizations/LatitudeVsMaxTemp.png" class="img-thumbnail">
                </a>
              </div>
            </div>
            <div class="col-md-6">
              <div class="thumbnail">
                <a href="WindSpeed.html">
                  <img src="Visualizations/LatitudeVsWindSpeed.png" class="img-thumbnail">
                </a>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <br>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Optional JavaScript -->
  <!-- jQuery first, then Popper.js, then Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
    integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
    integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
    crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
    integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
    crossorigin="anonymous"></script>
</body>
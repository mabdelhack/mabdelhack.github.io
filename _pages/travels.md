---
layout: page
permalink: /travel/
title: travel
description: Travel locations and photos
nav: true
---
<div class="projects">
<h2 class="category">map</h2>
<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 775px; height: 450px;"></div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
	{
		"id": "CZ",
		"showAsSelected": true
	},
	{
		"id": "DE",
		"showAsSelected": true
	},
	{
		"id": "RU",
		"showAsSelected": true
	},
	{
		"id": "TR",
		"showAsSelected": true
	},
	{
		"id": "CA",
		"showAsSelected": true
	},
	{
		"id": "US",
		"showAsSelected": true
	},
	{
		"id": "EG",
		"showAsSelected": true
	},
	{
		"id": "ZA",
		"showAsSelected": true
	},
	{
		"id": "TN",
		"showAsSelected": true
	},
	{
		"id": "CN",
		"showAsSelected": true
	},
	{
		"id": "HK",
		"showAsSelected": true
	},
	{
		"id": "JP",
		"showAsSelected": true
	},
	{
		"id": "KG",
		"showAsSelected": true
	},
	{
		"id": "MV",
		"showAsSelected": true
	},
	{
		"id": "QA",
		"showAsSelected": true
	},
	{
		"id": "SA",
		"showAsSelected": true
	},
	{
		"id": "KR",
		"showAsSelected": true
	},
	{
		"id": "TJ",
		"showAsSelected": true
	},
	{
		"id": "UZ",
		"showAsSelected": true
	},
	{
		"id": "VN",
		"showAsSelected": true
	},
	{
		"id": "AE",
		"showAsSelected": true
	},
	{
		"id": "MA",
		"showAsSelected": true
	}
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>



<h2 class="category">photos</h2>
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="6"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="7"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="8"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="9"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="10"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="11"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="12"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1P18L0gwuy-IGXkzp34rIa6rmN_25Jf_B">
      <div class="carousel-caption d-none d-md-block">
        <h5>Song Kul Lake, Kyrgyzstan</h5>
        <p></p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1mep5YGbkh1U_N8lQUnJUXQzNlIqjqEH4">
      <div class="carousel-caption d-none d-md-block">
        <h5>Song Kul Lake, Kyrgyzstan</h5>
        <p></p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1j_IQMViWfE18bQVDUwF_F1zkpgS9IRN8" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Song Kul Lake, Kyrgyzstan</h5>
        <p></p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1pizmH5qOSxf_g1-MW4msfV3YBIo2csI7" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Osh, Kyrgyzstan</h5>
        <p>Suleiman Too Mosque</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1ymjguLKjo-6vDzimzRejFjzAzofc5w6m" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Andijan, Uzbekistan</h5>
        <p>Local market</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1nXHFXf3O-95OuhV_iXHvYHLd8zQo3Evo" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Bukhara, Uzbekistan</h5>
        <p>A Madrasa</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1aFo-l60gGeKYyy2i2vOPRS4x9ODqc0q_" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Nagoro Village, Japan</h5>
        <p>This village has a population of one</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1L7eWFbW2h4-4uHNtq1nldW_9SYybl2KI" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Tula, Russia</h5>
        <p>Leo Tolstoi's house</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1DOdqma_S5w_nuXy0EWa4b_ctF8YptQn0" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Nizhny Novgorod, Russia</h5>
        <p>Alexander Nevsky Cathedral</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1n6P72JW4BmA2JhMtIUdlaXLjak-G6pd7" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Maafushi, Maldives</h5>
        <p></p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1LxYlWGipOYazqLIXQ2Vs8Jcm89t4fDMd" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Okinawa, Japan</h5>
        <p></p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1ajfu7tRMZXgz0IVrIyQ87ECek4027Cb-" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>St. Louis, US</h5>
        <p></p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drive.google.com/uc?export=view&id=1DPZvhxZxPYRwWHNNc8iWLuQDq09mwUhW" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>Cape Town, South Africa</h5>
        <p></p>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>
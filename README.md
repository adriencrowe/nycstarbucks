<style>
  body {
    margin: 0;
    padding: 0;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0 20px;
  }

  .map-container {
    display: flex;
    justify-content: center;
    width: calc(100% - 10px); /* subtracting 10px for 5px margins on either side */
    margin: 0 5px; /* setting 5px margins on either side */
  }

  .map-container iframe {
    width: 100%;
    height: 1200px;
    border: 0;
  }
</style>



<div class="container">
  <h1 align="center">Map of NYC Starbucks Locations</h1>
  <h2 align="center">I created this map for Annabelle to track her work with SEIU. Interact with the map here, and download a high-def image of the map using the image selector option in the display.</h2>
</div>

<div class="map-container">
  <iframe src="https://arcgis.com/apps/instant/basic/index.html?appid=0601617b03794f3289d97be15fad9d89&locale=en-us" frameborder="0" allowfullscreen>iFrames are not supported on this page.</iframe>
</div>

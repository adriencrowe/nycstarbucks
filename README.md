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
    width: 100%;
    box-sizing: border-box; /* Ensures padding doesn't add to total width */
  }
  
  /* Media query for screens smaller than 600px */
  @media (max-width: 600px) {
    .map-container {
      width: 100%;
      height: 100vh;
    }
  }
</style>

<div class="container">
  <h1 align="center">Map of NYC Starbucks Locations</h1>
  <h2 align="center">I created this map for Annabelle to track her work with SEIU. Interact with the map here, and download a high-def image of the map using the image selector option in the display.</h2>
  
  <div class="map-container">
    <iframe src="https://arcgis.com/apps/instant/basic/index.html?appid=0601617b03794f3289d97be15fad9d89&locale=en-us" width="3000" height="3000" frameborder="0" style="border:0" allowfullscreen>iFrames are not supported on this page.</iframe>
  </div>
</div>

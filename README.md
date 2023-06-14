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
    width: calc(100% - 10px); /* Use percentages for responsive width, with 5px margin on either side */
    margin: 0 5px;
  }

  .map-container iframe {
    width: 100%; /* iframe takes up the full width of the .map-container */
    height: auto; /* To maintain aspect ratio, you can set height to auto, or set to a certain vh value based on your design */
    border: 0;
  }

  @media only screen and (max-width: 600px) {
    /* For screens smaller than 600px, you might want to set different styles. This is just an example */
    .map-container {
      margin: 0; /* maybe remove margins on smaller screens */
    }
  }
</style>

<div class="container">
  <h1 align="center">Map of NYC Starbucks Locations</h1>
  <h2 align="center">I created this map for Annabelle to track her work with SEIU. Interact with the map here, and download a high-def image of the map using the image selector option in the display.</h2>
  accuracy
</div>

<div class="map-container">
  <iframe src="https://arcgis.com/apps/instant/basic/index.html?appid=0601617b03794f3289d97be15fad9d89&locale=en-us" frameborder="0" allowfullscreen>iFrames are not supported on this page.</iframe>
</div>

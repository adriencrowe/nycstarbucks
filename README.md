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

  .map-container {
    /* Additional styles for the map container */
    align-items: center;
    width: 3000px;
    height: 2000px; /* Adjust as needed */
  }

  iframe {
    /* Set the iframe to fill the map container */
    width: 100%;
    height: 100%;
  }

  /* Media queries for various iPhone screen sizes */

  /* iPhone SE (1st generation) */
  @media (max-width: 320px) {
    iframe {
      width: 310px;
      height: 248px;
    }
  }

  /* iPhone SE (2nd generation), iPhone 6/6s/7/8 */
  @media (min-width: 321px) and (max-width: 375px) {
    iframe {
      width: 365px;
      height: 292px;
    }
  }

  /* iPhone 6 Plus/6s Plus/7 Plus/8 Plus, iPhone X/XS/11 Pro/12 Pro */
  @media (min-width: 376px) and (max-width: 414px) {
    iframe {
      width: 404px;
      height: 323px
    }
  }

  /* iPhone XR/11/12, iPhone XS Max/11 Pro Max/12 Pro Max */
  @media (min-width: 415px) {
    iframe {
      width: 818px;
      max-width: 828px;
      height: 654px;
    }
  }
</style>

<div class="container">
  <h1 align="center">Map of NYC Starbucks Locations</h1>
  <h2 align="center">I created this map for Annabelle to track her work with SEIU. Interact with the map here, and download a high-def image of the map using the image selector option in the display.</h2>
</div>

<div class="map-container">
  <iframe src="https://arcgis.com/apps/instant/basic/index.html?appid=0601617b03794f3289d97be15fad9d89&locale=en-us" allowfullscreen>iFrames are not supported on this page.</iframe>
</div>


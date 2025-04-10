# Projects
Regarding Graphic Designer


For Logo Preview Direct With SVG Code

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Centered SVG</title>
  <style>
    /* Center the container in the viewport */
    html, body {
      height: 100%;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #000;
    }

    /* Container to hold the SVG */
    .svg-container {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: 100%;
    }

    /* SVG properties to keep the original size and be responsive */
    svg {
      width: auto;
      height: auto;
      max-width: 100%;
      max-height: 100%;
    }
  </style>
</head>
<body>
  <div class="svg-container">
    <!-- Your SVG code here (this is an example SVG) -->









  </div>
</body>
</html>

```

Or By the Image Preview


```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Centered SVG Image</title>
  <style>
    /* Center the container in the viewport */
    html, body {
      height: 100%;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #000;
    }

    /* Container for the image */
    .image-container {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: 100%;
    }

    /* Ensures the image stays responsive while keeping its aspect ratio */
    img {
      width: auto;
      height: auto;
      max-width: 100%;
      max-height: 100%;
    }
  </style>
</head>
<body>
  <div class="image-container">
    <!-- Use your SVG file in an <img> tag -->
    <img src="   " alt="SVG Image">
  </div>
</body>
</html>

```




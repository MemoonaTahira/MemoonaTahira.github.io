# Start quiz:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom Google Form</title>
  <script>
    // Example: Disable right-click context menu
    document.addEventListener('contextmenu', function(e) {
      e.preventDefault();  // Disable right-click
    });

    // Example: Disable copy, cut, and paste
    document.body.addEventListener('cut', function(e) {
      e.preventDefault(); // Disable cut
    });
    document.body.addEventListener('copy', function(e) {
      e.preventDefault(); // Disable copy
    });
    document.body.addEventListener('paste', function(e) {
      e.preventDefault(); // Disable paste
    });
  </script>
  <style>
    /* Example CSS styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f9f9f9;
    }
    h1 {
      text-align: center;
    }
    iframe {
      display: block;
      margin: 0 auto;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>  
  <!-- Embed Google Form Here -->
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdJpLvduIWq9x7CET0EphXEb7aD5_rOQ4wKOQFLPEblLcA8tQ/viewform?embedded=true" width="640" height="17687" frameborder="0" marginheight="0" marginwidth="0">

      Loading...
  </iframe>
  
</body>
</html>

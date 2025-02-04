<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hello Page</title>
  <style>
    /* Style for the body element */
    body {
      margin: 0;
      padding: 0;
      background-color: #FFC0CB; /* Pinkish background */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh; /* Full viewport height */
      opacity: 0; /* Start invisible */
      animation: fadeIn 2s forwards; /* Fade in over 2 seconds */
    }

    /* Style for the text */
    h1 {
      color: #333; /* Medium black text */
      font-size: 3em;
      font-family: Arial, sans-serif;
    }

    /* Keyframes for the fade-in effect */
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <h1>Hello</h1>
</body>
</html>

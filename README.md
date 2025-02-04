<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hello</title>
  <style>
    /* Basic reset and styling for a full-screen centered layout */
    body {
      margin: 0;
      padding: 0;
      background-color: #FFC0CB; /* Pinkish background */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      opacity: 0; /* Start invisible */
      animation: fadeIn 2s forwards; /* Fade in effect over 2 seconds */
    }

    /* Styling for the "Hello" text */
    h1 {
      color: #333; /* Medium black text */
      font-size: 3em;
      font-family: Arial, sans-serif;
    }

    /* Keyframes for the fade-in animation */
    @keyframes fadeIn {
      from { opacity: 0; }
      to   { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>Hello</h1>
</body>
</html>

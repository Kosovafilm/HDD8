# HDD8
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DCP List with Line Numbers</title>
  <style>
    body {
      counter-reset: line-number;
    }

    li::before {
      content: counter(line-number);
      counter-increment: line-number;
      margin-right: 0.5em;
      font-weight: bold;
    }
  </style>
</head>
<body>

<h2>DCP List with Line Numbers</h2>
<ul>
  <li>HDD8</li>
  <li>Burrneshat DCP</li>
  <li>I treturi DCP</li>
  <li>Illyricum DCP</li>
  <li>My Lake DCP</li>
  <li>Year of The Monkey DCP</li>
</ul>

</body>
</html>

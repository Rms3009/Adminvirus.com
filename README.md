<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Malware Comparison</title>
  <style>
    body {
      margin: 0;
      padding: 20px;
      background: #0f1115;
      font-family: 'Segoe UI', sans-serif;
      color: #ffffff;
    }

    h1 {
      text-align: center;
      color: cyan;
      font-size: 1.8em;
    }

    p {
      text-align: center;
      color: #ccc;
      margin-bottom: 30px;
    }

    .section {
      background: #1c1f26;
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.1);
    }

    .section h2 {
      display: flex;
      align-items: center;
      font-size: 1.4em;
      margin-bottom: 10px;
    }

    .section h2::before {
      content: '';
      display: inline-block;
      margin-right: 10px;
      width: 24px;
      height: 24px;
      background-size: contain;
    }

    .normal h2::before {
      background-image: url('https://cdn-icons-png.flaticon.com/512/565/565547.png');
    }

    .admin h2::before {
      background-image: url('https://cdn-icons-png.flaticon.com/512/595/595067.png');
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 8px;
      color: #a8dadc;
    }

    @media (min-width: 768px) {
      .wrapper {
        display: flex;
        gap: 20px;
        justify-content: center;
      }

      .section {
        flex: 1;
      }
    }
  </style>
</head>
<body>

  <h1>What Happens if You Run Malware as Normal vs Administrator?</h1>
  <p>Running Malware as administrator behaves very differently depending on your permission level. Here’s a visual breakdown:</p>

  <div class="wrapper">
    <div class="section normal">
      <h2>Normal User</h2>
      <ul>
        <li>Limited file access</li>
        <li>Cannot change system settings</li>
        <li>Can’t install services</li>
        <li>Malware is easier to contain and remove</li>
        <li>Can't destroy Windows</li>
      </ul>
    </div>

    <div class="section admin">
      <h2>Administrator</h2>
      <ul>
        <li>Full access to system files</li>
        <li>Can disable antivirus & firewall</li>
        <li>Can install rootkits and services</li>
        <li>Can delete or corrupt OS files</li>
        <li>Harder to detect and remove</li>
      </ul>
    </div>
  </div>

</body>
</html>


<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Virus as normal vs administrator </title>
  

</head>
<body>
<!-- partial:index.partial.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Malware Permissions Comparison</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #1f1f1f, #2c3e50);
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 10px;
      color: #00ffff;
    }

    p {
      font-size: 16px;
      max-width: 600px;
      margin: 0 auto 30px;
      color: #ccc;
    }

    .panel-container {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    @media (min-width: 700px) {
      .panel-container {
        flex-direction: row;
        justify-content: center;
      }
    }

    .panel {
      background-color: #292929;
      border-radius: 10px;
      padding: 20px;
      flex: 1;
      min-width: 250px;
      box-shadow: 0 0 10px rgba(0,255,255,0.2);
      transition: transform 0.3s;
    }

    .panel:hover {
      transform: scale(1.03);
    }

    .panel h2 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    .icon {
      font-size: 36px;
      margin-bottom: 10px;
    }

    ul {
      text-align: left;
      list-style: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
      position: relative;
      padding-left: 20px;
    }

    li::before {
      content: "•";
      position: absolute;
      left: 0;
      color: #00ffff;
    }

    .info-box {
      background: #1a1a1a;
      padding: 20px;
      margin-top: 30px;
      border-left: 4px solid #00ffff;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }

    .btn {
      background-color: #00ffff;
      border: none;
      padding: 10px 20px;
      color: #000;
      margin-top: 20px;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }

    .btn:hover {
      background-color: #00dddd;
    }
  </style>
</head>
<body>
  <h1>What Happens if You Run Malware as Normal vs Administrator?</h1>
  <p>Running Malware as administrator behaves very differently depending on your permission level. Here’s a visual breakdown:</p>

  <div class="panel-container">
    <div class="panel">
      <div class="icon">🔒</div>
      <h2>Normal User</h2>
      <ul>
        <li>Limited file access</li>
        <li>Cannot change system settings</li>
        <li>Can’t install services</li>
        <li>Malware is easier to contain and remove</li>
        <li>Can't destroy window</li>
      </ul>
    </div>

    <div class="panel">
      <div class="icon">⚠️</div>
      <h2>Administrator</h2>
      <ul>
        <li>Full access to system files</li>
        <li>Can disable antivirus</li>
        <li>Can install rootkits</li>
        <li>Much harder to detect and remove</li>
        <li>Destroy the window</li>
      </ul>
    </div>
  </div>

  <div class="info-box">
    <strong>Did you know?</strong> Running unknown programs as administrator gives malware full control of your system. Always think before clicking "Run as Admin"!. If you run any virus as administrator and if you have best premium antivirus make sure run antivirus as administrator. Thank you for reading and stay safe and secure 
    <br><br>
    <button class="btn" onclick="alert('Tip: Use a Standard account for daily use to stay safe.')">Stay Safe Tips</button>
  </div>
</body>
</html>
<!-- partial -->
  
</body>
</html>

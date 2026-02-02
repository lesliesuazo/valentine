# valentine
💌
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Will You Be My Valentine?</title>
  <style>
    body {
      background: #fff1f6;
      font-family: 'Comic Sans MS', 'Arial Rounded MT Bold', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      max-width: 350px;
    }

    img {
      width: 180px;
      margin-bottom: 15px;
    }

    h1 {
      color: #ff4d6d;
    }

    button {
      font-size: 18px;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 12px;
      border: none;
      cursor: pointer;
    }

    .yes {
      background: #ff4d6d;
      color: white;
    }

    .no {
      background: #ddd;
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="https://your-image-link-here.png" alt="Cute Valentine Raccoon">
    <h1>Will you be my Valentine? 💖</h1>

    <button class="yes" onclick="yes()">YES 💘</button>
    <button class="no" onclick="no()">no 🥺</button>
  </div>

  <script>
    function yes() {
      document.body.innerHTML = `
        <h1 style="color:#ff4d6d">YAY 💞</h1>
        <p>best decision ever.</p>
        <p>i love you 🦝💘</p>
      `;
    }

    function no() {
      alert("that button was for decoration 😌 try again");
    }
  </script>

</body>
</html>

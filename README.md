# Valentine
<!DOCTYPE html>
<html>
<head>
  <title>Be My Valentine ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      background: pink;
      padding-top: 80px;
    }

    h1 {
      color: red;
      font-size: 35px;
    }

    h2 {
      font-size: 22px;
    }

    button {
      padding: 15px 30px;
      font-size: 18px;
      margin: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    #yes {
      background-color: red;
      color: white;
    }

    #no {
      background-color: black;
      color: white;
    }

    #msg {
      font-size: 22px;
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>

<body>

<h1>Hello Joan ❤️</h1>
<h2>Will you be my Valentine?</h2>

<button id="yes" onclick="yesClick()">YES</button>
<button id="no" onclick="noClick()">NO</button>

<p id="msg"></p>

<script>
function yesClick() {
  document.getElementById("msg").innerHTML = "Yaaay! I knew you would say YES 😍💘";
}

function noClick() {
  document.getElementById("msg").innerHTML = "🚫 Access Denied: Only YES is allowed 😎";
}
</script>

</body>
</html>

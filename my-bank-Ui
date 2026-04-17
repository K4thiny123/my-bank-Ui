<!DOCTYPE html>
<html>
<head>
  <title>My Bank Demo</title>
  <style>
    body {
      font-family: Arial;
      background: #0f172a;
      color: white;
      text-align: center;
    }
    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 15px;
      width: 300px;
      margin: 50px auto;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }
    button {
      padding: 10px;
      border: none;
      background: #22c55e;
      color: white;
      border-radius: 10px;
      cursor: pointer;
    }
  </style>
</head>
<body>

<div class="card">
  <h2>My Bank</h2>
  <p>Balance:</p>
  <h1 id="balance">₱10,000</h1>
  <button onclick="addMoney()">Deposit ₱500</button>
</div>

<script>
  let balance = 10000;

  function addMoney() {
    balance += 500;
    document.getElementById("balance").innerText = "₱" + balance;
  }
</script>

</body>
</html>

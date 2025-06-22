<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>تسجيل دخول</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');
    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(120deg, #89f7fe, #66a6ff);
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    .login-box {
      background-color: #ffffffcc;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      text-align: center;
      width: 300px;
    }
    h2 {
      margin-bottom: 20px;
      color: #34495e;
    }
    input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    button {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 12px;
      width: 100%;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #2980b9;
    }
    .message {
      margin-top: 15px;
      color: #e74c3c;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h2>تسجيل دخول</h2>
    <input type="text" id="username" placeholder="اسم المستخدم">
    <input type="password" id="password" placeholder="كلمة السر">
    <button onclick="login()">دخول</button>
    <div class="message" id="loginMessage"></div>
  </div>  <script>
    function login() {
      const username = document.getElementById("username").value.trim();
      const password = document.getElementById("password").value.trim();
      const message = document.getElementById("loginMessage");

      if (username === "Sayed" && password === "01201427081") {
        message.style.color = '#27ae60';
        message.innerText = "تم الدخول كأدمن. جاري التحويل...";
        setTimeout(() => {
          window.location.href = "admin_dashboard.html";
        }, 1500);
      } else {
        message.innerText = "اسم المستخدم أو كلمة السر غير صحيحة.";
      }
    }
  </script></body>
</html>

<!DOCTYPE html>
index.html
style.css
script.js
<html>
  <head>
    <title>ราคาทองคำวันนี้</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        text-align: center;
        margin-top: 50px;
      }
      button {
        font-size: 18px;
        padding: 10px 20px;
        background-color: gold;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
      button:hover {
        background-color: orange;
      }
      #price {
        margin-top: 20px;
        font-size: 24px;
        color: darkgoldenrod;
      }
    </style>
  </head>
  <body>
    <h1>ราคาทองคำวันนี้</h1>
    <button onclick="showPrice()">กดดูราคาทอง</button>
    <p id="price">ยังไม่ได้โหลดราคา</p>

    <script src="script.js"></script>
  </body>
</html>

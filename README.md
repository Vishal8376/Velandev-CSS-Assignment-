# Velandev-CSS-Assignment-
index.html
```
<html>
<head>
  <meta charset="UTF-8">
  <title>CSS Tooltip</title>
  <style>
    body {
        margin: 0;
        height: 96.5vh;
        display:flex;
        border: 10px solid #333;
        padding: 5px;
        justify-content: center;
        align-items: center;
        background: linear-gradient(blue,green);
    }
    .tooltip {
      position: relative;
      display: inline-block;
      cursor: pointer;
      border: 3px solid black;
      padding: 5px;
      border-radius: 10px;
      font-size: 100px;
    }
    .tooltip .tooltip-text {
      visibility: hidden;
      width: 160px;
      background-color: #333;
      color: #fff;
      font-size: medium;
      text-align: center;
      padding: 8px;
      border-radius: 6px;
      position: absolute;
      opacity: 0;
      transition: opacity 1s;
    }
    .tooltip:hover .tooltip-text {
      visibility: visible;
      opacity: 1;
    }
  </style>
</head>
<body>
  <div class="tooltip">
    Hover your mouse over me
    <div class="tooltip-text">This is a tooltip message</div>
  </div>
</body>
</html>
```

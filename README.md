<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>漢頓</title>
    <h1>我的網頁</h1>
    <style>
        .background {
            width: 300px;
            height: 300px;
            background-color: lightblue;
            position: relative; 
            z-index: 1;
        }
        .top-layer {
            width: 150px;
            height: 150px;
            background-color: #93cad0;
            position: absolute; 
            top: 50px;
            left: 50px;
            z-index: 10; 
        }
        body {
            background-color: #c2e0e7;
            color: #333;
            font-family: Arial, sans-serif;
            }
        dialog{
            border: none;
            box-shadow: 0 2px 6px #ccc;
            border-radius: 10px;
            }

        .Dimgray-text{color:rgb(105,105,105)}
    </style>
</head>
<body>
    <h1>漢頓的海底世界！</h1>
    <p>相信不少人都曾看過這隻可愛生物，但你知道他叫什麽嗎？</p>
    <img src="https://pgw.udn.com.tw/gw/photo.php?u=https://uc.udn.com.tw/photo/2024/03/14/0/29192888.png&x=0&y=0&sw=0&sh=0&exp=3600" alt="我是誰？" >
    
    <button popovertarget="popup">
        <em>解答</em>
    </button>
    <div id="popup" popover>
        漢頓</div>
    
    <a href="https://example.com" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">解答
    </a>
    
</body>
</html>

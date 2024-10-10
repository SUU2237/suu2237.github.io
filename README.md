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
    <img src="https://i.ibb.co/THHVTVs/IMG-4284.png" alt="我是誰？" width="300" height="400" >
    
    <button onclick="alert('漢頓')" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">解答</button>
    <div class="top-layer">漢頓</div>
    
    <a href="https://example.com" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">解答
    </a>
    
</body>
</html>

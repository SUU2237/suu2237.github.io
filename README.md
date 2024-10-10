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
        .modal-content {
            background-color: #fefefe;
            margin: 15% auto; /* 中心對齊 */
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 400px;
            border-radius: 5px;
        }
        body {
            background-color: #c2e0e7;
            color: #333;
            font-family: Arial, sans-serif;
            }

        .Dimgray-text{color:rgb(105,105,105)}
    </style>
</head>
<body>
    <h1>漢頓的海底世界</h1>
    <p>相信不少人都曾看過這隻可愛生物，但你知道他叫什麽嗎？</p>
    <img src="https://i.ibb.co/THHVTVs/IMG-4284.png" alt="我是誰？" width="320" height="370"  >
    
    <button onclick="alert('漢頓')" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">解答</button>


    
    <button id="openModalBtn">點擊彈出視窗</button>

    <!-- 彈出視窗 -->
    <div id="myModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2>這是自定義彈出視窗</h2>
            <p>你可以在這裡添加自定義的內容。</p>
        </div>
    </div>


    
    <a href="https://example.com" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">解答
    </a>
    
</body>
</html>

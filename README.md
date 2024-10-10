<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>漢頓</title>
    <h1>漢頓的海底世界</h1>
    <style>
        
        .modal {
            display: none; /* 初始隱藏 */
            position: fixed; /* 固定位置 */
            z-index: 1; /* 保證位於頂層 */
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5); /* 半透明背景 */
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
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }

        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
        body {
            background-color: #c2e0e7;
            color: #333;
            font-family: Arial, sans-serif;
            }

        
    </style>
</head>
<body>
    <p>相信不少人都曾看過這隻可愛生物，但你知道他叫什麽嗎？</p>
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.sanrio.com%2Fcollections%2Fhangyodon%2Fna-072823&psig=AOvVaw0EwujzmdUJ-Oh7xyQWEZKM&ust=1728638385782000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCJD8ivO9g4kDFQAAAAAdAAAAABAE" alt="我是誰？"   >
    
    <button id="openModalBtn" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">解答</button>

    <!-- 彈出視窗 -->
    <div id="myModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2>漢頓！</h2>
            <a href="https://i.ibb.co/THHVTVs/IMG-4284.png" target="_blank" style="padding: 10px 20px; background-color: #93cad0; color: white; text-align: center; text-decoration: none; display: inline-   block; border-radius: 4px;">點我看簡介
    </a>
        </div>
    </div>

    <script>
        // 獲取彈窗元素
        var modal = document.getElementById("myModal");

        // 獲取開啟彈窗的按鈕
        var btn = document.getElementById("openModalBtn");

        // 獲取關閉按鈕
        var span = document.getElementsByClassName("close")[0];

        // 當點擊按鈕時，打開彈窗
        btn.onclick = function() {
            modal.style.display = "block";
        }

        // 當點擊關閉按鈕時，關閉彈窗
        span.onclick = function() {
            modal.style.display = "none";
        }

        // 當點擊彈窗外部時，也關閉彈窗
        window.onclick = function(event) {
            if (event.target == modal) {
                modal.style.display = "none";
            }
        }
        
    </script>
    
    
    
</body>
</html>

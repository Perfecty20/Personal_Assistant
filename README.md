<!-- 添加这一行启用HTML5验证 -->

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>页面跳转</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            height: 100vh;
        }

        #topSection {
            background-color: #FFD700; /* Yellow color for top section */
            flex: 0.15;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        #middleSection {
            background: linear-gradient(to right, #E8E8E8, #FFFFFF); /* Slightly darker white gradient for middle section */
            flex: 0.65;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        #middleSection button {
            background-color: #FFFFFF; /* White color for buttons */
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 8px;
            box-shadow: 2px 2px 4px #000000; /* Black shadow effect */
            transition: background 0.3s ease; /* Smooth transition effect */
            outline: none;
        }

        #middleSection button:hover {
            background-color: #F0F0F0; /* Lighter white color on hover */
        }

        #bottomSection {
            background-color: #2F2F2F; /* Dark gray color for bottom section */
            flex: 0.20;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    </style>
</head>
<body>

    <div id="topSection">
        <h1>欢迎来到fl.y私人小助手~</h1>
    </div>

    <div id="middleSection">
        <button onclick="redirectToPage1()">文件小助手</button>
        <button onclick="redirectToPage2()">图片小助手</button>
    </div>

    <div id="bottomSection">
        <!-- Content for the bottom section if needed -->
    </div>

    <script>
        function redirectToPage1() {
            window.location.href = 'https://udify.app/chat/E1By7KPCpd89GaMC';
        }

        function redirectToPage2() {
            window.location.href = 'https://huggingface.co/spaces/LinkSoul/Chinese-LLaVa';
        }
    </script>

</body>
</html>

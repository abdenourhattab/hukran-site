<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شكر لأصدقائي</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #333;
        }

        .thanks {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
            margin-bottom: 20px;
        }

        button {
            background-color: #ff5555;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #ff3333;
        }

        #explosion {
            display: none;
            margin-top: 20px;
            font-size: 30px;
            color: red;
            font-weight: bold;
        }

        #loveMessage {
            display: none;
            margin-top: 20px;
            font-size: 24px;
            color: #555;
        }
    </style>
</head>
<body>

<h1>أود أن أشكر أصدقائي الرائعين</h1>

<div class="thanks">
    <p>شكرًا لكم جميعًا على دعمكم المستمر وكونكم أصدقاء رائعين. أنتم الأفضل!</p>
</div>

<button onclick="explode()">اضغط هنا</button>

<div id="explosion">💥💥💥 BOOM! 💥💥💥</div>
<div id="loveMessage">أحبكم جميعًا! ❤️</div>

<script>
    function explode() {
        // إظهار القنبلة المتفجرة
        document.getElementById('explosion').style.display = 'block';
        
        // إظهار رسالة الحب بعد 2 ثانية
        setTimeout(function() {
            document.getElementById('loveMessage').style.display = 'block';
        }, 2000);
    }
</script>

</body>
</html>

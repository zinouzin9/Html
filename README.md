<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تطبيقي البسيط</title>
    <style>
        body {
            font-family: 'Tahoma', Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 300px;
            width: 100%;
        }
        h1 {
            color: #333;
            font-size: 22px;
            margin-bottom: 10px;
        }
        p {
            color: #666;
            font-size: 14px;
            margin-bottom: 20px;
        }
        .btn {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>مرحباً بك!</h1>
        <p>هذا قالب HTML بسيط وجاهز للتشغيل داخل تطبيقك.</p>
        <button class="btn" onclick="showAlert()">اضغط هنا</button>
    </div>

    <script>
        function showAlert() {
            alert("مرحباً بك، الكود يعمل بنجاح داخل التطبيق!");
        }
    </script>

</body>
</html>

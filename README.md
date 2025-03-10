<!DOCTYPE html><html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نتيجة الطالب</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: white;
        }
        .container {
            margin: 50px auto;
            width: 80%;
        }
        .result-box {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: right;
        }
        .result-box h2 {
            color: #333;
        }
        .subject {
            background-color: #ddd;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
        }
        .back-btn {
            background-color: blue;
            color: white;
            padding: 10px 20px;
            margin-top: 20px;
            border: none;
            cursor: pointer;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="result-box">
            <h2>نتيجة امتحانات الدور الأول 2024/2025</h2>
            <div class="subject">رياضيات (1) - أ</div>
            <div class="subject">ميكانيكا (1) - أ</div>
            <div class="subject">فيزياء (1) - أ</div>
            <div class="subject">رسم هندسي وإسقاط (1) - غ</div>
            <div class="subject">مقدمة الحاسبات والبرمجة - ل</div>
            <div class="subject">لغة إنجليزية فنية (1) - ج</div>
        </div>
        <button class="back-btn" onclick="goBack()">العودة إلى الصفحة الرئيسية</button>
    </div><script>
    function goBack() {
        window.location.href = "index.html";
    }
</script>

</body>
</html># -

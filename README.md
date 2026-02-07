<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ڈاؤن لوڈ پیج</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .main-card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            width: 350px;
        }

        h2 { color: #333; margin-bottom: 20px; }

        /* بٹن کا ڈیزائن */
        .btn {
            display: block;
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: 0.3s;
        }

        /* ڈاؤن لوڈ بٹن (سبز) */
        .download-btn {
            background-color: #28a745;
            color: white;
        }
        .download-btn:hover { background-color: #218838; }

        /* معلومات کا بٹن (نیلا) */
        .info-btn {
            background-color

<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>मेरी पहली वेबसाइट</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            background: #f5f7fa;
        }

        header {
            background: #2563eb;
            color: white;
            padding: 40px 20px;
        }

        h1 {
            font-size: 40px;
        }

        .content {
            padding: 40px 20px;
        }

        button {
            background: #2563eb;
            color: white;
            border: none;
            padding: 14px 25px;
            font-size: 18px;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background: #1d4ed8;
        }

        footer {
            margin-top: 50px;
            padding: 20px;
            background: #111827;
            color: white;
        }
    </style>
</head>

<body>

    <header>
        <h1>नमस्ते! 👋</h1>
        <p>मेरी पहली वेबसाइट में आपका स्वागत है</p>
    </header>

    <div class="content">

        <h2>मेरी वेबसाइट</h2>

        <p>
            यह वेबसाइट मैंने GitHub की मदद से बनाई है।
        </p>

        <button onclick="showMessage()">
            यहाँ दबाएँ
        </button>

    </div>

    <footer>
        © 2026 मेरी वेबसाइट
    </footer>

    <script>
        function showMessage() {
            alert("नमस्ते! मेरी वेबसाइट पर आपका स्वागत है 😊");
        }
    </script>

</body>
</html>

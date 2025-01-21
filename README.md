# support-page-
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>アプリサポート</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1 {
            color: #007AFF;
        }
        form {
            max-width: 600px;
            margin-top: 20px;
        }
        label {
            display: block;
            margin-top: 15px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007AFF;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #005BB5;
        }
        .footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>アプリサポート</h1>
    <p>ご質問やご意見がございましたら、以下のフォームからお問い合わせください。</p>
    <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
        <label for="name">名前:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">メールアドレス:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">メッセージ:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">送信</button>
    </form>

    <div class="footer">
        <p>© 2025 あなたの会社名. All rights reserved.</p>
    </div>
</body>
</html>

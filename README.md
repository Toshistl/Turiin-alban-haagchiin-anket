<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Төрийн албан хаагчийн анкет</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h2 {
            text-align: center;
        }
        form {
            max-width: 600px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background: #f9f9f9;
        }
        label {
            font-weight: bold;
        }
        input, textarea, select {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            width: 100%;
            padding: 10px;
            background: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

    <h2>Төрийн албан хаагчийн анкет</h2>

    <form action="submit_form.php" method="POST">
        <label for="last_name">Овог:</label>
        <input type="text" id="last_name" name="last_name" required>

        <label for="first_name">Нэр:</label>
        <input type="text" id="first_name" name="first_name" required>

        <label for="register">Регистрийн дугаар:</label>
        <input type="text" id="register" name="register" required>

        <label for="birth_date">Төрсөн огноо:</label>
        <input type="date" id="birth_date" name="birth_date" required>

        <label for="gender">Хүйс:</label>
        <select id="gender" name="gender" required>
            <option value="male">Эрэгтэй</option>
            <option value="female">Эмэгтэй</option>
        </select>

        <label for="address">Оршин суугаа хаяг:</label>
        <textarea id="address" name="address" rows="3" required></textarea>

        <label for="phone">Утасны дугаар:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="email">Цахим шуудан:</label>
        <input type="email" id="email" name="email" required>

        <label for="education">Боловсрол:</label>
        <textarea id="education" name="education" rows="3" required></textarea>

        <label for="experience">Ажлын туршлага:</label>
        <textarea id="experience" name="experience" rows="4" required></textarea>

        <label for="skills">Мэргэжлийн ур чадвар:</label>
        <textarea id="skills" name="skills" rows="3" required></textarea>

        <button type="submit">Хадгалах</button>
    </form>

</body>
</html>

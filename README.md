<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Төрийн албан хаагчийн анкет</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h2>Төрийн албан хаагчийн анкет</h2>
        <form>
            <label for="photo">Цээж зураг (3x4 см):</label>
            <input type="file" id="photo" name="photo" accept="image/*">

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

            <label for="marital_status">Гэрлэлтийн байдал:</label>
            <select id="marital_status" name="marital_status" required>
                <option value="married">Гэрлэсэн</option>
                <option value="single">Гэрлээгүй</option>
            </select>

            <label for="education">Боловсрол:</label>
            <textarea id="education" name="education" rows="3" required></textarea>

            <label for="experience">Ажлын туршлага:</label>
            <textarea id="experience" name="experience" rows="4" required></textarea>

            <label for="skills">Мэргэжлийн ур чадвар:</label>
            <textarea id="skills" name="skills" rows="3" required></textarea>

            <label for="foreign_languages">Гадаад хэлний мэдлэг:</label>
            <textarea id="foreign_languages" name="foreign_languages" rows="3" required></textarea>

            <label for="computer_skills">Компьютерийн ур чадвар:</label>
            <textarea id="computer_skills" name="computer_skills" rows="3" required></textarea>

            <label for="military_service">Цэргийн алба хаасан эсэх:</label>
            <select id="military_service" name="military_service" required>
                <option value="yes">Тийм</option>
                <option value="no">Үгүй</option>
            </select>

            <label for="awards">Шагнал урамшуулал:</label>
            <textarea id="awards" name="awards" rows="3" required></textarea>

            <label for="trainings">Мэргэшүүлэх сургалт:</label>
            <textarea id="trainings" name="trainings" rows="3" required></textarea>

            <button type="submit">Хадгалах</button>
        </form>
    </div>
</body>
</html>


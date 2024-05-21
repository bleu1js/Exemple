<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعي الشخصي</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>موقعي الشخصي</h1>
            <nav>
                <ul>
                    <li><a href="#home">الرئيسية</a></li>
                    <li><a href="#about">عنّي</a></li>
                    <li><a href="#services">الخدمات</a></li>
                    <li><a href="#blog">المدونة</a></li>
                    <li><a href="#contact">اتصل بنا</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="container">
            <h2>مرحبًا بكم في موقعي الشخصي</h2>
            <p>هذا هو النص التوضيحي الذي يمكنك تخصيصه.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>عنّي</h2>
            <p>نص عن سيرتك الذاتية.</p>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>الخدمات</h2>
            <p>تفاصيل عن الخدمات التي تقدمها.</p>
        </div>
    </section>

    <section id="blog">
        <div class="container">
            <h2>المدونة</h2>
            <p>أحدث المقالات والأخبار.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>اتصل بنا</h2>
            <form action="#" method="post">
                <label for="name">الاسم:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">البريد الإلكتروني:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">الرسالة:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">إرسال</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 موقعي الشخصي. جميع الحقوق محفوظة.</p>
        </div>
    </footer>
    <style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: #333;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #77cc6d 3px solid;
}

header a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
}

header ul {
    padding: 0;
    list-style: none;
}

header li {
    float: left;
    display: inline;
    padding: 0 20px 0 20px;
}

header #branding {
    float: left;
}

header #branding h1 {
    margin: 0;
}

header nav {
    float: right;
    margin-top: 10px;
}

header .highlight, header .current a {
    color: #77cc6d;
    font-weight: bold;
}

header a:hover {
    color: #77cc6d;
    font-weight: bold;
}

#showcase {
    min-height: 400px;
    background: url('showcase.jpg') no-repeat 0 -400px;
    text-align: center;
    color: #fff;
}

#showcase h1 {
    margin-top: 100px;
    font-size: 55px;
    margin-bottom: 10px;
}

#showcase p {
    font-size: 20px;
}

section {
    padding: 20px 0 20px 0;
}

#main-col {
    float: left;
    width: 70%;
}

#sidebar {
    float: right;
    width: 30%;
    background: #333;
    color: #fff;
    padding: 10px;
    box-sizing: border-box;
}

#sidebar h3 {
    text-align: center;
}

#contact form {
    display: flex;
    flex-direction: column;
}

#contact label {
    margin-bottom: 5px;
}

#contact input, #contact textarea {
    margin-bottom: 10px;
    padding: 10px;
    font-size: 16px;
}

#contact button {
    padding: 10px;
    background: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
    margin-top: 20px;
    clear: both;
}
</style>
</body>
</html>

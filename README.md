[index.html](https://github.com/user-attachments/files/24355731/index.html)
<!DOCTYPE html>
.<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>أقرب مراكز مهمة</title>

<style>
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        min-height: 100vh;
        background: linear-gradient(135deg, #e8f5e9, #c8e6c9);
        font-family: "Segoe UI", Tahoma, sans-serif;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 40px 20px;
    }

    h1 {
        color: #1b5e20;
        margin-bottom: 35px;
        font-size: 28px;
    }

    .container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        gap: 25px;
        width: 100%;
        max-width: 800px;
    }

    a.card {
        background: white;
        border-radius: 18px;
        padding: 30px 20px;
        text-decoration: none;
        box-shadow: 0 12px 24px rgba(0,0,0,0.12);
        transition: transform .25s ease, box-shadow .25s ease;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    a.card:hover {
        transform: translateY(-6px);
        box-shadow: 0 18px 32px rgba(0,0,0,0.18);
    }

    .icon {
        font-size: 42px;
        margin-bottom: 15px;
    }

    .title {
        font-size: 22px;
        font-weight: 600;
        color: #2e7d32;
        margin-bottom: 20px;
        text-align: center;
    }

    .btn {
        margin-top: auto;
        padding: 12px 32px;
        background: #2e7d32;
        color: #fff;
        border-radius: 999px;
        font-size: 15px;
    }

    .btn:hover {
        background: #1b5e20;
    }
</style>
</head>
<body>

<h1>أقرب مراكز مهمة من موقعك</h1>

<div class="container">

    <a class="card"
       href="https://maps.app.goo.gl/cB1a9wBeTcaA3Tzg7?g_st=ic"
       target="_blank">
        <div class="icon">🕌</div>
        <div class="title">أقرب جامع</div>
        <div class="btn">فتح الموقع</div>
    </a>

    <a class="card"
       href="https://maps.app.goo.gl/oqRr84z3Z4zdJxUN6?g_st=ic"
       target="_blank">
        <div class="icon">🏥</div>
        <div class="title">أقرب مركز صحي</div>
        <div class="btn">فتح الموقع</div>
    </a>

</div>

</body>
</html>

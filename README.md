<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .main-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 50px;
        background-color: #222;
        color: #ffffff;
        height: 80px;                
    }
    .main-footer {
        background-color: #222;
        color: #ccc;
        padding: 40px 50px;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        gap: 30px;
    }
    .footer-section {
        flex: 1;
        min-width: 200px;
    }
    body {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
        margin: 0;
    }
    main {
        flex: 1;
    }
</style>
<header class="main-header">
    <div>
        <nav>
            <button class="but" id="page-1">Главная</button>
            <button class="but" id="page-2">Корзина</button>
            <button class="but" id="page-3">Акции</button>
            <button class="but" id="page-4">Профиль</button>
        </nav>
    <div>
</header>
<body>
    <main>
        <div></div>
    </main>
</body>
<footer class="main-footer">
    <h>Контактные данные</h>
</footer>
</html>

<script>
    document.querySelectorAll('button[data-group]')
</script>

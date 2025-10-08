<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sage Rassia Форум</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #1e1e1e;
        color: #f0f0f0;
    }
    header {
        background-color: #2c2c2c;
        padding: 15px;
        text-align: center;
        font-size: 24px;
        font-weight: bold;
        color: #ff4d4d;
    }
    nav {
        background-color: #333;
        display: flex;
        justify-content: center;
        padding: 10px;
    }
    nav a {
        color: #f0f0f0;
        text-decoration: none;
        margin: 0 15px;
        font-weight: bold;
    }
    nav a:hover {
        color: #ff4d4d;
    }
    .container {
        max-width: 900px;
        margin: 20px auto;
        padding: 0 15px;
    }
    .category, .topic, .admin-panel {
        background-color: #2c2c2c;
        padding: 15px;
        margin-bottom: 15px;
        border-radius: 8px;
    }
    .category h2, .topic h2, .admin-panel h2 {
        margin-top: 0;
        color: #ff4d4d;
    }
    .topic p {
        margin: 10px 0;
        background-color: #1a1a1a;
        padding: 10px;
        border-radius: 5px;
    }
    .admin-panel ul {
        list-style: none;
        padding: 0;
    }
    .admin-panel li {
        background-color: #1a1a1a;
        margin: 5px 0;
        padding: 10px;
        border-radius: 5px;
    }
    input, textarea, button {
        width: 100%;
        padding: 8px;
        margin: 5px 0;
        border-radius: 5px;
        border: none;
        font-size: 14px;
    }
    button {
        background-color: #ff4d4d;
        color: #fff;
        cursor: pointer;
        font-weight: bold;
    }
    button:hover {
        background-color: #e60000;
    }
</style>
</head>
<body>

<header>Sage Rassia Форум</header>

<nav>
    <a href="#categories">Категории</a>
    <a href="#topics">Темы</a>
    <a href="#admin">Администрация</a>
</nav>

<div class="container">

    <!-- Категории -->
    <div id="categories" class="category">
        <h2>Категории форума</h2>
        <ul>
            <li>Общие темы</li>
            <li>Новости</li>
            <li>Администрация</li>
            <li>Гайды и инструкции</li>
        </ul>
    </div>

    <!-- Темы -->
    <div id="topics" class="topic">
        <h2>Тема: Правила форума</h2>
        <p>Пожалуйста, соблюдайте правила форума и уважайте других игроков.</p>
        <p>Администраторы следят за порядком и могут выдать наказание за нарушение.</p>
        <textarea id="comment" placeholder="Написать комментарий..."></textarea>
        <button onclick="addComment()">Добавить комментарий</button>
        <div id="comments"></div>
    </div>

    <!-- Панель администратора -->
    <div id="admin" class="admin-panel">
        <h2>Панель администрации</h2>
        <ul>
            <li>Главный администратор: полный доступ</li>
            <li>Администратор 1
	    

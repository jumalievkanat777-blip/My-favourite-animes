# My-favourite-animes

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пример сайта</title>
    <style>
        /* CSS код сюда пишем внутри <style> */
        body {
            font-family: Arial, sans-serif;
            background: #2a2a2a;
            text-align: center;
            padding: 50px;
        }

        .btn {
            background: #4caf50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            transition: 0.3s;
            cursor: pointer;
            font-size: 16px;
            margin: 20px 0;
        }
        .btn:hover {
            background: #388e3c;
        }

        .movie {
            background: #ffffff;
            display: inline-block;
            width: 200px;
            margin: 10px;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .movie img {
            width: 100%;
            border-radius: 5px;
        }

        .movie h3 {
            margin: 10px 0 5px 0;
        }

        .movie p {
            font-size: 14px;
            color: #555;
        }
        .author {
            position: fixed;
            bottom: 10px;
            left: 10px;
            color: #888;
            font-size: 14px;
            font-family: Arial, sans-serif;
            opacity: 0.8;
        }
    </style>
</head>
<body>

<h1>Лучшие аниме</h1>

<div class="movie">
    <img src="JOJO.jpg" alt="Фильм 1">
    <h3>Невероятные приключения ДжоДжо</h3>
    <p>Про то как род Джостаров попадают в невероятные приключения</p>
    <button class="btn">Смотреть</button>
</div>

<div class="movie">
    <img src="BAKI.jpg" alt="Фильм 2">
    <h3>Боец Баки</h3>
    <p>Про то как Баки хочет победить своего отца Юдзиро</p>
    <button class="btn">Смотреть</button>
</div>
<p class="author">DioJKanat</p>
</body>
</html>

# leoslim123.github.io
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Автомобили в Наличии</title>
<style>
  body { font-family: Arial, sans-serif; line-height: 1.6; }
  .container { width: 80%; margin: auto; overflow: hidden; }
  header { background: #50b3a2; color: white; padding-top: 30px; min-height: 70px; border-bottom: #e8491d 3px solid; }
  header a { color: #ffffff; text-decoration: none; text-transform: uppercase; font-size: 16px; }
  header ul { padding: 0; list-style: none; }
  header li { display: inline; margin: 0 20px; }
  header #branding { float: left; }
  header #branding h1 { margin: 0; }
  header nav { float: right; margin-top: 10px; }
  header .highlight, header .current a { color: #e8491d; font-weight: bold; }
  header a:hover { color: #ffffff; font-weight: bold; }
  .showcase { min-height: 400px; background: url('car-showcase.jpg') no-repeat 0 -400px; text-align: center; color: #ffffff; }
  .showcase h1 { margin-top: 100px; font-size: 55px; margin-bottom: 10px; }
  .showcase p { font-size: 20px; }
  .car { margin: 20px 0; padding: 20px; background: #f4f4f4; }
  .car img { width: 100%; height: auto; }
  footer { background: #333333; color: white; text-align: center; padding: 10px; margin-top: 20px; }
</style>
</head>
<body>
  <header>
    <div class="container">
      <div id="branding">
        <h1><span class="highlight">Авто</span> Маркет</h1>
      </div>
      <nav>
        <ul>
          <li class="current"><a href="index.html">Главная</a></li>
          <li><a href="about.html">О Нас</a></li>
          <li><a href="services.html">Услуги</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="showcase">
    <div class="container">
      <h1>Найдите Ваш Идеальный Автомобиль</h1>
      <p>Лучшие предложения и эксклюзивные скидки только у нас!</p>
    </div>
  </section>

  <div class="container">
    <div class="car">
      <h2>BMW X6</h2>
      <img src="https://hdpic.club/photo/uploads/posts/2023-12/1701575692_hdpic-club-p-chernaya-bmv-x6-60.jpg" alt="BMW X6">
      <p>Этот роскошный кроссовер сочетает в себе стиль, мощность и комфорт.</p>
    </div>
    <div class="car">
      <h2>Mercedes-Benz G-Class</h2>
      <img src="https://sportishka.com/uploads/posts/2023-12/1701940330_sportishka-com-p-mersedes-dzhi-vkontakte-15.jpg" alt="Mercedes-Benz G-Class">
      <p>Иконический внедорожник, который не уступает по проходимости и статусу.</p>
    </div>
    <div class="car">
      <h2>Audi A8</h2>
      <img src="https://avatars.dzeninfra.ru/get-zen_doc/3940836/pub_60524a403eb679416854a721_60524c1057266c7ccd0cdf7a/scale_1200" alt="Audi A8">
      <p>Флагманский седан, предлагающий непревзойденный уровень роскоши и инноваций.</p>
    </div>
    <!-- Добавьте больше автомобилей по аналогии -->
  </div>

  <footer>
    <p>Авто Маркет &copy; 2024</p>
  </footer>
</body>
</html>

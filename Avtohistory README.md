<!doctype html>
<html lang="ru">
  <head>
 <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
 <script src="https://kit.fontawesome.com/09a8b1129e.js" crossorigin="anonymous"></script> 
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<style>

body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  width: 1200px;
}

.navbar {
  overflow: hidden;
  background-color: rgb(9, 138, 143); 
}

.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 12px 14px;
  text-decoration: none;
}

.subnav {
  float: left;
  overflow: hidden;
}

.subnav .subnavbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: rgb(15, 9, 9);
  padding: 12px 14px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.navbar a:hover, .subnav:hover .subnavbtn {
  background-color: rgb(156, 247, 201);
}

.subnav-content {
  display: none;
  position: absolute;
  left: 0;
  background-color: rgb(154, 197, 233);
  width: 100%;
  z-index: 1;
}

.subnav-content a {
  float: left;
  color: white;
  text-decoration: none;
}

.subnav-content a:hover {
  background-color: #eee;
  color: black;
}

.subnav:hover .subnav-content {
  display: block;
}
/*Поля ввода полной ширины*/
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

/*Стиль для всех кнопок*/
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

/*Дополнительные стили для кнопки "Отмена"*/
.cancelbtn {
  padding: 14px 20px;
  background-color: #36bef4;
}

.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

.container {
  padding: 16px;
}

/*Модальный (фон)*/
.modal {
  display: none; 
  position: fixed; 
  z-index: 1; 
  top: 0;
  width: 100%; 
  height: 100%; 
  overflow: auto;
  background-color: #474e5d;
  padding-top: 50px;
}

/*Модальное содержание*/
.modal-content {
  background-color: #fefefe;
  margin: 5% auto 15% auto;
  border: 1px solid #888;
  width: 80%;
}


hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}
 
/*Кнопка закрытия*/
.close {
  position: absolute;
  right: 35px;
  top: 15px;
  font-size: 40px;
  font-weight: bold;
  color: #f1f1f1;
}

.close:hover,
.close:focus {
  color: #73a9fa;
  cursor: pointer;
}


.clearfix::after {
  content: "";
  clear: both;
  display: table;
}


@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
     width: 100%;
  }

  
/*Сайт центр*/
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 4px -10px;
}

.row {
    margin: 8px-10px;
    padding: 40px;
}

.row, 
.row >.column {
  padding: 20px;
}

.column {
  float:none;
  width: 50%;
}

.row::after {
  content: "";
  display: table;
  clear: both;
}
/*Содержание*/
.content {
  background-color: rgb(211, 217, 245);
  padding: 5px;
  margin: 0;
}

@media screen and (max-width: 1000px) {
  .column {
    width: 50%;
  }
}
@media screen and (max-width: 1000px) {
  .column {
    width: 50%;
  }
}
</style>
</head>
   <title>Зигзаг удачи</title>
<body>
  <div class="navbar">
    <a href="">Главная</a>
    <div class="subnav">
      <button class="subnavbtn">О Нас <i class="fa fa-caret-down"></i></button>
      <div class="subnav-content">
        <a href="">Компания</a>
        <a href="">Команда</a>
        <a href="">Карьера</a>
      </div>
    </div> 
    <div class="subnav">
      <button class="subnavbtn">Услуги <i class="fa fa-caret-down"></i></button>
      <div class="subnav-content">
        <a href="">Вызов</a>
        <a href="">Доставка</a>
        <a href="">Пакет</a>
        <a href="">Курьер</a>
      </div>
    </div> 
    <div class="subnav">
      <button class="subnavbtn">Партнеры <i class="fa fa-caret-down"></i></button>
      <div class="subnav-content">
        <a href="">Ссылка 1</a>
        <a href="">Ссылка 2</a>
        <a href="">Ссылка 3</a>
        <a href="">Ссылка 4</a>
      </div>
    </div>
    <a href="">Контакты</a>
  </div>
  
  <div style="padding:0 16px"></div>
  

<img src="./img/ADLu.gif" alt="Марка" width="1200px" height="300px" style="background-color: aqua; border: 2px dotted; left: 50px;">
<hr>
/*Сетка галереи портфолио*/
<div class="row">
  <div class="column">
    <div class="content">
      <img src="./img/adam_opel_2.jpg" alt="Человек" style="width:100%">
      <h3>Немного истории..></h3>
      <p>В лесах на юге Германии вдоль берегов Рейна находится холмистая местность, называемая Оппель или Оббель. 
Адам Опель родился 9 мая 1937 года в небольшом городке Рюссельсхайме недалеко от Франкфурта-на-Майне в семье кузнеца. Он был старшим сыном в семье и его карьера началась учеником кузнеца в мастерской отца. Однако с получением аттестата зрелости Адам Опель ушел из семьи и уехал из страны, чтобы найти новое ремесло. Адам отправился во Францию, где тот познакомился с последним чудом техники — швейной машинкой.
Вернувшись домой в 1862 году, Адам Опель приспособил швейную машинку для производства шляп и основал компанию Opel, на которой наладил производство станков для выпуска головных уборов. Эта компания стала крупнейшим производителем шляп в Германии. 21 января Адам Опель организовал фирму по выпуску швейных машинок. Знал бы уважаемый немецкий господин, что помнить его будут совсем по другой причине, наверняка сильно удивился бы. Когда в 1863 году Адам Опель открывал фабрику по производству швейных машин, он и подумать не мог, что его сыновья займутся выпуском автомобилей, а в его честь назовут имиджевый компакт. Автор выяснил, достоин ли «Опель-Адам» имени прославленного предка.
    </p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="./img/chven.jpg" alt="Реклама" style="width:540px">
      <h3>Основа процветания семейства Опель — швейные машинки...></h3>
      <p>Последние десятилетия позапрошлого века компания встретила в процветающем виде. Достаточно, наверное, сказать, что предприятие Адама считалось ведущим в Германии производителем швейных машинок и велосипедов.Раскрученный бизнес по выпуску швейных машинок приносил существенную прибыль, ведь не было в Германии домохозяйки, не мечтавшей об оверлоке с монограммой AD — Adam Opel. Понятно, что и деньги в контору текли рекой.</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="./img/1868_pervyy_zavod_opel_2.jpg" alt="Завод" style="width:100%">
      <h3>1868 Первый завод Opel</h3>
      <p>В 1911 году семью Опель ждет серьезный удар – пожар на завод в Рюссельсхайме, который уничтожил практически все оборудование. Но нет худа без добра: после ремонта цехов в них были закуплены новейшие станки, что позволило увеличить производительность труда. Попутно компания отказалась от непрофильного бизнеса, доставшегося сыновьям Адама Опеля в наследство, – выпуск швейных машинок был прекращен. Сконцентрировавшись на производстве автомобилей, уже к 1913 году Opel становится самым крупным автопроизводителем в Германии. Но сыновья Адама Опеля не останавливаются на достигнутом: в 1924 году они получают кредит в один миллион золотых марок и тратят эту колоссальную сумму на модернизацию производственных мощностей. </p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="./img/1912_velosipedy_opel_6.jpg" alt="Велосипед" style="width:100%">
      <h3>Модели велосипедов</h3>
      <p>К тому времени Opel давно превратился в крупнейшего автопроизводителя Германии, а о не слишком рентабельном выпуске велосипедов уже никто и не вспоминал. Сегодня даже странно представить, что в первой четверти 20 века именно Opel вполне официально считался крупнейшим в мире велопроизводителем.Пять сыновей Адама с детства помогали отцу на фабрике, а в свободное время развлекались, катаясь вокруг дома на велосипедах. Именно они популяризовали велоспорт в Германии и вскоре стали первыми чемпионами. Опели первыми предложили использовать в колёсах велосипедов новые шины с наполнением воздухом конструкции англичанина по фамилии Данлоп в 1890 г.</p>
    </div>
  </div>
<div class="column">
    <div class="content">
    <img src="./img/mach.jpg" alt="Автомобиль" style="width:100%">
      <h3>Laubfrosch</h3>
      <p>Первой крупносерийной машиной Opel стала модель 4/12 Laubfrosch, выпущенная в 1924 году. Автомобиль имел 4-х цилиндровый двигатель, объемом 1,0 л, мощностью 14 л. с., а его максимальная скорость составляла 60 км/ч. Интересно, что с этой машиной связано судебное разбирательство Opel с компанией Citroen. Андре Ситроен решил, что Opel похож на его Citroen 5CV и подал в суд на немецкую компанию, требуя выплату за лицензию. Однако дело до выплат не дошло, поскольку у 4/12 Laubfrosch было довольно много технических отличий. Автомобиль выпускался до 1931 года. Всего было выпущено около 119 000 экземпляров. Впервые в истории фирмы производство одной модели превысило 100 000 единиц.
</p>
    </div>
  </div>
<div class="column">
    <div class="content">
    <img src="./img/Insignia-2008.png" alt="Машина" style="width:100%">
      <h3>Новая эра</h3>
      <p>Уже в 2018 году, благодаря оптимизации производства Opel впервые за долгие годы показывает операционную прибыль сначала в квартальных отчетах, а затем и по итогам года. Opel постепенно берет курс на электрофикацию своих моделей, планируя уже через 5 лет предложить любую из своих моделей как в традиционном варианте, так и в вариантах с гибридной силовой установкой или полностью на электортяге.А вообще, в Opel обещают запускать по одной новой модели каждый год. Самой ближайшей премьерой станет построенный на модульной платформе CMP компактный хетч Opel Corsa, который впервые в истории марки будет иметь полностью электрическую версию Corsa-e. Что касается внедорожников, то к уже существующим двум моделям был добавлен ещё один вариант — Frontera Sport Soft Top с мягкой складывающейся задней частью крыши. 
      </p>
    </div>
  </div> 
</div>
<div class="content">
  <img src="./img/opelik.jpg" alt="Авто" style="width: 1200px;">
  <h3>Нет предела совершенству...></h3>
  <p>Концепт Opel Monza имеет скульптурный кузов, который больше походит на Shooting Brake, чем на классическое купе, где доминирует поразительная деталь дизайна – огромные двери в стиле Gullwing. Другие примечательные детали – перед колесными арками воздухозаборники в форме бумеранга, дополняющие хром на передней решетке.</p>
  <p>Обещанный недавно шоу-кар Opel Monza Concept оказался помесью купе с универсалом, снабжённой широченными дверями типа «крылья чайки». Под столь эффектной обёрткой скрываются не менее эффектные технологии. Так, немцы полностью пересмотрели концепцию подачи информации водителю и пассажирам. Вся передняя панель Монцы, от двери до двери, представляет собой единую проекционную поверхность. За ней скрыты 18 светодиодных проекторов. Их работу можно менять, добиваясь желаемой комбинации данных, в зависимости от вкусов обитателей салона или настроения водителя.</p>
</div>

<button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Зарегистрироваться</button>

<div id="id01" class="modal">
  <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Закрыть Modal">&times;</span>
  <form class="modal-content" action="/action_page.php">
    <div class="container">
      <h1>Зарегистрироваться</h1>
      <p>Заполните эту форму, чтобы создать свою учетную запись</p>
      <hr>
      <label for="email"><b>Email</b></label>
      <input type="text" placeholder=" Ведите Email" name="email" required>

      <label for="psw"><b>Пароль</b></label>
      <input type="password" placeholder=" Ведите пароль" name="psw" required>

      <label for="psw-repeat"><b>Повторите пароль</b></label>
      <input type="password" placeholder="Повторите пароль" name="psw-repeat" required>
      
      <label>
        <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Запомнить меня
      </label>

      <p>Создавая учетную запись, вы соглашаетесь с нашим <a href="" style="color:dodgerblue">Условием и конфиденциальностью</a></p>

      <div class="clearfix">
        <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Отменить</button>
        <button type="submit" class="signupbtn">Вход</button>
      </div>
    </div>
  </form>
</div>

<script>

var modal = document.getElementById('id01');


window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>

  </body>
</html>

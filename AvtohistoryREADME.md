# 0970_S
0970_Avtohistory
<!doctype html>
<html lang="ru">
  <head>
<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #91dde7;
  padding: 20px;
  font-family: Arial;
}

/* Сайт по центру */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 10px -16px;
}

/* Добавляем отступ между каждым столбцом */
.row,
.row > .column {
  padding: 8px;
}


.column {
  float: left;
  width: 33.33%;
  display: none; 
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Содержание */
.content {
  background-color: white;
  padding: 10px;
}

/* Класс "show" добавим к отфильтрованным элементам */
.show {
  display: block;
}

/* Стиль кнопок */
.btn {
  border:2px rgb(8, 104, 56) solid;
  outline: none;
  padding: 12px 16px;
  background-color: rgb(156, 155, 238);
  cursor: pointer;
  width: 200px;
}

.btn:hover {
  background-color: rgb(236, 110, 173);
}

.btn.active {
  background-color: #666;
  color: white;
}

  body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

/* Поля ввода полной ширины */
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

/* Установим стиль для всех кнопок */
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

/* Дополнительные стили для кнопки Отмена */
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}

.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

.container {
  padding: 16px;
}

/* Модальный (фон) */
.modal {
  display: none; 
  position: fixed; 
  z-index: 1; 
  left: 0;
  top: 0;
  width: 100%; 
  height: 100%; 
  overflow: auto; 
  background-color: #474e5d;
  padding-top: 50px;
}

/* Модальное содержание/бокс */
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
 
/* Кнопка закрытия (x) */
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
  color: #f44336;
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
}

</style>
</head>
<body>


<div class="main">

<img src="./img/118360789.gif" alt="Авто" style="width: 1000px; height: 350px;">


<h2>История успеха. От швейной машинки до совершенства!</h2>

<div id="myBtnContainer">
  <button class="btn active" onclick="filterSelection('all')"> Показать все</button>
  <button class="btn" onclick="filterSelection('nature')"> Адам Опель</button>
  <button class="btn" onclick="filterSelection('cars')"> Машины</button>
  <button class="btn" onclick="filterSelection('people')"> Достижения</button><div id="myBtnContainer">
   </div>

<div class="row">
  <div class="column nature">
    <div class="content">
      <img src="./img/adam_opel_2.jpg" alt="Горы" style="width:100%">
      <h4>Адам</h4>
      <p>Адам Опель родился 9 мая 1937 года в небольшом городке Рюссельсхайме недалеко от Франкфурта-на-Майне в семье кузнеца. Адам отправился во Францию, где тот познакомился с последним чудом техники — швейной машинкой.</p>
    </div>
  </div>
  <div class="column nature">
    <div class="content">
    <img src="./img/chven.jpg" alt="Огни" style="width:300px; height: 250px;">
      <h4>Реклама швейной машинки</h4>
      <p>Не было в Германии домохозяйки, не мечтавшей об оверлоке с монограммой AD — Adam Opel.</p>
    </div>
  </div>
  <div class="column nature">
    <div class="content">
    <img src="./img/1868_pervyy_zavod_opel_2.jpg" alt="Лес" style="width:100%">
      <h4>Первый завод</h4>
      <p>Компания отказалась от непрофильного бизнеса, доставшегося сыновьям Адама Опеля в наследство, – выпуск швейных машинок был прекращен. </p>
    </div>
  </div>
  <div class="column cars">
    <div class="content">
      <img src="./img/загрузка (7).jfif" alt="Car" style="width:100%">
      <h4>Производство</h4>
      <p>Попутно компания отказалась от непрофильного бизнеса, доставшегося сыновьям Адама Опеля в наследство, – выпуск швейных машинок был прекращен. Сконцентрировавшись на производстве автомобилей, уже к 1913 году Opel становится самым крупным автопроизводителем в Германии.</p>
    </div>
  </div>
  <div class="column cars">
    <div class="content">
    <img src="./img/mach.jpg" alt="Car" style="width:100%">
      <h4>Ретро</h4>
      <p>Первой крупносерийной машиной Opel стала модель 4/12 Laubfrosch, выпущенная в 1924 году. Автомобиль имел 4-х цилиндровый двигатель, объемом 1,0 л, мощностью 14 л. с., а его максимальная скорость составляла 60 км/ч.</p>
    </div>
  </div>
  <div class="column cars">
    <div class="content">
    <img src="./img/Insignia-2008.png" alt="Car" style="width:100%">
      <h4>Инсигния</h4>
      <p>Уже в 2018 году, благодаря оптимизации производства Opel впервые за долгие годы показывает операционную прибыль сначала в квартальных отчетах, а затем и по итогам года. А вообще, в Opel обещают запускать по одной новой модели каждый год.</p>
    </div>
  </div>
<div class="column people">
    <div class="content">
      <img src="./img/opelik.jpg" alt="Car" style="width:100%">
      <h4>Монца</h4>
      <p>Концепт Opel Monza имеет скульптурный кузов, который больше походит на Shooting Brake, чем на классическое купе, где доминирует поразительная деталь дизайна – огромные двери в стиле Gullwing. </p>
    </div>
  </div>
  <div class="column people">
    <div class="content">
    <img src="./img/загрузка (6).jfif" alt="Car" style="width:100%">
      <h4>Гонки</h4>
      <p>Участвуя в многочисленных гонках Опель завоевал множество побед...Одно время европейский филиал General Motors, куда, помимо Opel, вошел и английский бренд Vauxhall занимали второе место на континенте.</p>
    </div>
  </div>
  <div class="column people">
    <div class="content">
    <img src="./img/510bc6e4b721428155000005.jpg" alt="Car" style="width:100%">
      <h4>Я доволен!</h4>
      <p>Президент концерна в восторге!</p>
    </div>
  </div>
</div>
</div>
</div>
<button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Регистрация</button>

<div id="id01" class="modal">
  <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Закрыть Modal">&times;</span>
  <form class="modal-content" action="../action_page.php">
    <div class="container">
      <h1>Вход</h1>
      <p>Пожалуйста, заполните эту форму, чтобы создать учетную запись.</p>
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

      <p>Создавая учетную запись, вы соглашаетесь с нашим <a href="#" style="color:dodgerblue">Условием и конфиденциальностью</a>.</p>

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

<script>
  filterSelection("all")
  function filterSelection(c) {
    var x, i;
    x = document.getElementsByClassName("column");
    if (c == "all") c = "";
    for (i = 0; i < x.length; i++) {
      w3RemoveClass(x[i], "show");
      if (x[i].className.indexOf(c) > -1) w3AddClass(x[i], "show");
    }
  }
  
  function w3AddClass(element, name) {
    var i, arr1, arr2;
    arr1 = element.className.split(" ");
    arr2 = name.split(" ");
    for (i = 0; i < arr2.length; i++) {
      if (arr1.indexOf(arr2[i]) == -1) {element.className += " " + arr2[i];}
    }
  }
  
  function w3RemoveClass(element, name) {
    var i, arr1, arr2;
    arr1 = element.className.split(" ");
    arr2 = name.split(" ");
    for (i = 0; i < arr2.length; i++) {
      while (arr1.indexOf(arr2[i]) > -1) {
        arr1.splice(arr1.indexOf(arr2[i]), 1);     
      }
    }
    element.className = arr1.join(" ");
  }
  
  
  // Добавляем активный класс к текущей кнопке
  var btnContainer = document.getElementById("myBtnContainer");
  var btns = btnContainer.getElementsByClassName("btn");
  for (var i = 0; i < btns.length; i++) {
    btns[i].addEventListener("click", function(){
      var current = document.getElementsByClassName("active");
      current[0].className = current[0].className.replace(" active", "");
      this.className += " active";
    });
  }
  </script>
  

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ" crossorigin="anonymous"></script>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js" integrity="sha384-W8fXfP3gkOKtndU4JGtKDvXbO53Wy8SZCQHczT5FMiiqmQfUpWbYdTil/SxwZgAN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.min.js" integrity="sha384-skAcpIdS7UcVUC05LJ9Dxay8AXcDYfBJqt1CJ85S/CFujBsIzCIv+l9liuYLaMQ/" crossorigin="anonymous"></script>

  </body>
</html>

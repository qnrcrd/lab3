<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Безруков Никита Валерьевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>HTML</b> —  стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.</p>
<p><b>CSS</b> — формальный язык описания внешнего вида документа, написанного с использованием языка разметки. Также может применяться к любым XML-документам, например, к SVG или XUL.</p>

<h1 style="text-align: center">Задачи</h1>
<ol>
  <li>Создать все виды заголовков с текстом "Hello world" c классом "heading"</li>
  <li>Каждому заголовку также дать id </li>
  <li>Задать всем заголовкам цвет текста на красный</li>
  <li>Второму заголовку синий </li>
  <li>Третьему заголовку поменять задний фон на чёрный </li>
  <li>Четвертому заголовку сделать border и округлить углы у</li>
  <li>Пятому заголовку создать :hover эффект (любой) </li>
  <li>Создатm 6 input с разными типами </li>
  <li>Создать нумерованный список из 4 элементов с текстом </li>
  <li>Создать маркированный список из 4 элементов с текстом “Маркированный” и квадратным маркером</li>
  <li>Создатm веб-страницу с зеленым фоном и белым текстом из 30 слов</li>
  <li>Создать 6 блоков с нумерацией и такими параметрами (ширина 100px и высота 100px, зеленого цвета, внешним отступом 10px). Их родительским элементом должен быть container</li>
  <li>Поставить все блоки по центру страницы</li>
  <li>Добавить тэг <iframe> на вашу страницу</li>
  <li>Сделать простую форму регистрации на сайте (Только верстка)</li>
  <li>Сделать таблицу на странице</li>
  <li>Создать стиль для заголовка h1 с красным цветом текста</li>
  <li>Установить шрифт Arial для всех параграфов на странице</li>
  <li>Добаить тень на блок div с помощью свойства box-shadow</li>
  <li>Установить фоновый цвет #f0f0f0 для всего документа</li>
  <li>Создать анимацию, которая будет мигать красным цветом</li>
  <li>Установить отступы внутри блока div с помощью свойства padding</li>
  <li>Создать стиль для ссылок, которые будут менять цвет при наведении на них курсора</li>
  <li>Добавить границу вокруг изображения с помощью свойства border</li>
  <li>Создать стиль для списка ul с маркерами в виде квадратов</li>
  <li>Установить ширину и высоту блока div с помощью свойств width и height</li>
  <li>Создать стиль для таблицы, который будет делать каждую вторую строку серой</li>
  <li>Добавьить эффект перехода при наведении на кнопку с помощью свойства transition</li>
  <li>Установить фоновое изображение для элемента с помощью свойства background-image</li>
  <li>Создать стиль для формы с полями для ввода текста и кнопкой отправки</li>
  <li>Добавить рамку вокруг текстового поля с помощью свойства outline</li>
  <li>Установить выравнивание текста по центру в блоке div с помощью свойства text-align</li>
  <li>Создать стиль для выпадающего меню с помощью псевдоэлемента :hover</li>
  <li>Добавить тень на текст с помощью свойства text-shadow</li>
  <li>Создать стиль для анимации появления элемента на странице с помощью свойства opacity</li>
  <li>Установить шрифт размером 18 пикселей для всех заголовков на странице</li>
</ol>

<h1 style="text-align: center">Решения Задач</h1>

<h2 style="text-align: center">Файл Заданий 1-10 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1-10</title>
    <link rel="stylesheet" href="styles/st1.css">
</head>
<body>
    <h1 class="heading" id="head1">Hello world</h1>
    <h2 class="heading" id="head2" style="color: blue;">Hello world</h2>
    <h3 class="heading" id="head3" style="background-color: black;">Hello world</h3>
    <h4 class="heading" id="head4" style="border: 3px solid black; border-radius: 10px; ">Hello world</h4>
    <h5 class="heading" id="head5" hover="background-color:green">Hello world</h5>
    <h6 class="heading" id="head6">Hello world</h6>

    <!--TASK 8-->
    <p style="font-size: large;">ЗАДАНИЕ 8</p>
    <input type="password"></input>
    <input type="text"></input>
    <input type="radio"></input>
    <input type="checkbox"></input>
    <input type="button" value="button"></input>
    <input type="file"></input>

    <!--TASK 9-->
    <p style="font-size: large;">ЗАДАНИЕ 9</p>
    <ol>
        <li>я</li>
        <li>нумерованный</li>
        <li>список</li>
    </ol>
    
    <!--TASK 10-->
    <p style="font-size: large;">ЗАДАНИЕ 10</p>
    <ul style="list-style-type:square ;">
        <li>я</li>
        <li>маркерованный</li>
        <li>список</li>    
    </ul>
</body>
</html>
```
<h2 style="text-align: center">использованный файл st1.css</h2>

```css
.heading
{
    color: red;
}

#head5:hover
{
    background-color: blueviolet;
}
```

<h2 style="text-align: center">Файл Задания 11 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>11</title>
</head>
<body style="background-color: green;">
    <p style="color: white; font-size:large; font-weight:bold">— Знаете, для чего в самолётах нужны кислородные маски?</p>
    <p style="color: white; font-size:large; font-weight:bold">— Чтобы дышать.</p>
    <p style="color: white; font-size:large; font-weight:bold">— Кислород опьяняет. В катастрофических ситуациях люди впадают в панику и бешено глотают воздух, и вдруг эйфория, покой, и ты смиряешься с судьбой.</p>
</body>
</html>
```

<h2 style="text-align: center">Файл Заданий 12-13 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>12-13</title>
    <link rel="stylesheet" href="styles/st12.css">
</head>
<body>
    <div class="container">
        <ol>
            <li>
                <div class="block">block 1</div>
            </li>
            <li>
                <div class="block">block 2</div>
            </li>
            <li>
                <div class="block">block 3</div>
            </li>
            <li>
                <div class="block">block 4</div>
            </li>
            <li>
                <div class="block">block 5</div>
            </li>
            <li>
                <div class="block">block 6</div>
            </li>
        </ol>
    </div>
</body>
</html>
```
<h2 style="text-align: center">использованный файл st12.css</h2>

```css
.container /*13*/
{
    display: flex;
    justify-content: center;
    align-items: center;
}

.block
{
    width:100px;
    height: 100px;
    background-color: green;
    margin:10px;
}
```

<h2 style="text-align: center">Файл Задания 14 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>14</title>
</head>
<body>
    <iframe src="https://en.wikipedia.org/wiki/In_the_End" title="Lyrics" width="500" height="500"></iframe>
</body>
</html>
```

<h2 style="text-align: center">Файл Задания 15 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles/st15.css">
</head>
<body>
    <div class="container">
        <form class="form">
            <h2>REGISTRATION</h2>
            <input type="text" placeholder="Name">
            <input type="text" placeholder="Email">
            <input type="text" placeholder="Password">
            <button type="submit">Register</button>
        </form>
    </div>
</body>
</html>
```
<h2 style="text-align: center">использованный файл st15.css</h2>

```css
.container
{
    display: flex;
    justify-content: center;
    align-items: center;
}

.form
{
    width:300px;
    padding:20px;
    border: 1px solid  white;
    border-radius: 5px;
}

.form input
{
    width:100%;
    padding:10px;
    margin-bottom: 10px;
}

.form button
{
    width:100%;
    padding:10px;
    border: none;
    background-color: violet;
    color:white;
    border-radius: 5px;
    cursor:pointer;
}
```

<h2 style="text-align: center">Файл Заданий 16-26 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>16-26</title>
    <link rel="stylesheet" href="styles/st16_26.css">
</head>
<body style="background-color: #f0f0f0;"><!--20-->
    <table>
    <tr>
        <td>имя</td>
        <td>курс</td>
        <td>год рождения</td>
    </tr>
    <tr>
        <td>Виктор</td>
        <td>2</td>
        <td>2003</td>
    </tr>
    <tr>
        <td>Алексей</td>
        <td>1</td>
        <td>2004</td>
    </tr>
    <tr>
        <td>Ростислав</td>
        <td>4</td>
        <td>2001</td>
    </tr>
    </table>

    <!--TASK 17-->
    <h4>ЗАДАНИЕ 17</h4>
    <h1>HEADER 1</h1>
    
    <!--TASK 18-->
    <h4>ЗАДАНИЕ 18</h4>
    <p>arial paragraph</p>

    <!--TASK 19-->
    <h4>ЗАДАНИЕ 19</h4>
    <div class="shadow">SHADOW</div>

    <!--TASK 20-->
    <h4>ЗАДАНИЕ 20</h4>
    <h3 class="redblink">я мигаю!</h3>

    <!--TASK 22-->
    <h4>ЗАДАНИЕ 22</h4>
    <div class="padded">PADDING</div>

    <!--TASK 23-->
    <h4>ЗАДАНИЕ 23</h4>
    <a href="https://www.youtube.com/watch?v=AGS8nS-aWvU">funny</a>


    <!--TASK 24-->
    <h4>ЗАДАНИЕ 24</h4>
    <img class="imgborder" src="me.png" alt="funny" width="200" height="200">

    <!--TASK 25-->
    <h4>ЗАДАНИЕ 25</h4>
    <ul class="ulich">
        <li>я</li>
        <li>маркерованный</li>
        <li>список</li>    
    </ul>

    <!--TASK 26-->
    <h4>ЗАДАНИЕ 26</h4>
    <div class="tsk26">TASK 26</div>
</body>
</html>
```
<h2 style="text-align: center">использованный файл st16_26.css</h2>

```css
h1 /*17*/
{
    color: red;
}

th, td{
    border: 0.2em solid black;
    border-radius: 10%;
    border-style: solid;
    border-color: rgb(226, 43, 165);
    background-color:rgb(22, 238, 184);
}

p /* 18 */
{
    font-family: Arial;
}

.shadow /*19*/
{
    width: 100px;
    height: 100px;
    background-color: rgb(240, 150, 150);
    box-shadow: 5px 5px 10px;
}

.redblink /*21*/
{
    animation: blink 1s infinite;
}

@keyframes blink
{
    0%{color: red;}
    50%{color: transparent;}
    100%{color: red;}
}

.padded /*22*/
{
    padding: 60px 20px 10px 50px; /* up, right, down, left */
    /*padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 20px;
    padding-left: 40px;*/
    background-color: rgb(120, 209, 209);
    width: 100px;
    height: 100px;
}

a:hover /*23*/
{
    color: aqua;
}

.imgborder /*24*/
{
    border: thick solid black;
}

.ulich /*25*/
{
    list-style-type: square;
    color: blueviolet;
    font-size: 20px;
}

.tsk26 /*26*/
{
    color: aliceblue;
    background-color: rgb(84, 54, 192);
    width: 100px;
    height: 100px;
}
```

<h2 style="text-align: center">Файл Заданий 27-28 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>27-28</title>
</head>
<body>
    <table>
        <tr>
            <td>имя</td>
            <td>курс</td>
            <td>год рождения</td>
        </tr>
        <tr>
            <td>Виктор</td>
            <td>2</td>
            <td>2003</td>
        </tr>
        <tr>
            <td>Алексей</td>
            <td>1</td>
            <td>2004</td>
        </tr>
        <tr>
            <td>Ростислав</td>
            <td>4</td>
            <td>2001</td>
        </tr>
        </table>
    <br/>
    
    <!--TASK 28-->
    <h4>ЗАДАНИЕ 28</h4>
    <button type="button">im a button</button>
    <br/>
    
    <style>
        tr:nth-child(even) 
        {
            background-color: lightgrey;
        }
        th,td
        {
            border-style: solid;
            border-color: rgb(43, 189, 226);
        }
        button
        {
            background-color: blue;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover
        {
            background-color: red;
        }
    </style>
</body>
</html>
```

<h2 style="text-align: center">Файл Задания 29 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>29</title>
</head>
<body>
    <button class="imgbtn"type="button" onclick="location.href='https://google.com';"></button>
    <style>
        .imgbtn
        {
            width: 100px;
            height: 100px;
            border: none;
            background-image: url('gena.jpg');
            background-size: cover;
        }
        .imgbtn:hover
        {
            cursor: pointer;
        }

    </style>
</body>
</html>
```

<h2 style="text-align: center">Файл Заданий 30-31 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>30</title>
    <link rel="stylesheet" href="styles/st30-31.css">
</head>
<body>
    <form>
        <label for="name">name:</label>
        <input type="text" id="name" name="name" placeholder="enter your name">
    
        <label for="email">email:</label>
        <input type="text" id="email" name="email" placeholder="enter your email">
    
        <button type="submit">send</button>
    </form>
</body>
</html>
```
<h2 style="text-align: center">использованный файл st30_31.css</h2>

```css
body 
{
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f4f4f4;
}

  form 
  {
    background-color: #fff;
    padding: 30px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 350px;
  }

  label 
  {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
  }

  input[type="text"] 
  {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #c4c4c4;
    border-radius: 3px;
    box-sizing: border-box;
    outline: 2px solid #4CAF50;/*31*/
  }

  button[type="submit"] 
  {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 3px;
    cursor: pointer;
    width: 100%;
    font-size: 16px;
  }

  button[type="submit"]:hover 
  {
    background-color: #45a049;
  }
```
<h2 style="text-align: center">Файл Задания 32 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="tsk32">32</div>
    <style>
        .tsk32 
        {
            color:azure;
            width: 50px;
            height: 50px;
            background-color: rgb(255, 0, 0);
            text-align: center;/*32*/
        }
    </style>
</body>
</html>
```

<h2 style="text-align: center">Файл Заданий 33-36 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>33-36</title>
    <link rel="stylesheet" href="styles/st33-36.css">
</head>
<body>
    <div class="dropdown">
        <button class="dropdown_btn">select</button>
        <div class="dropdown_cont">
          <a href="https://www.youtube.com/watch?v=jDuLh0YylsE">blizzard</a>
          <a href="https://www.youtube.com/watch?v=JflsBihO_MQ">divide</a>
          <a href="https://www.youtube.com/watch?v=PC4G_8_Mkr0">new wave hookers</a>
        </div>
      </div>
      <br><br><br>
      
      <!--task 35-->
      <h4>ЗАДАНИЕ 35</h4>
      <div class="task_35">
        <p>You won!</p>
      </div>
      <button onclick="document.querySelector('.task_35').classList.add('show');">show secret</button>

      <!--task 36-->
      <h4>ЗАДАНИЕ 36</h4>
      <h1>все</h1>
      <h2>заголовки</h2>
      <h3>имеют</h3>
      <h4>шрифт</h4>
      <h5>размером</h5>
      <h6>18 пикселей</h6>
</body>
</html>
```
<h2 style="text-align: center">использованный файл st33_36.css</h2>

```css
.dropdown 
{
    position: relative;
    display: inline-block;
    text-shadow: 1px 1px 1px rgb(61, 61, 61);/*34*/
  }
  
  .dropdown_btn 
  {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  .dropdown_cont 
  {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }
  
  .dropdown_cont a 
  {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }
  
  .dropdown_cont a:hover 
  {
    background-color: #f1f1f1;
  }
  
  .dropdown:hover .dropdown_cont
  {
    display: block;
  }

  /*35*/
  .task_35
  {
    opacity: 0;
    transition: opacity 0.5s ease-in-out;
  }

  .task_35.show
  {
    opacity: 1;
  }

  /*36*/
  h1,h2,h3,h4,h5,h6
  {
    font-size: 18px;
  }
```
<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, были приобретены навыки работы с языками CSS и HTML, а также были созданы 11 страниц по 36 заданиям с использованием HTML и CSS</p>



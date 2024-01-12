<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №9</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">PHP — интерпретируемый скриптовый язык программирования общего назначения. Название представляет собой рекурсивный акроним PHP: Hypertext Preprocessor (PHP: предварительный обработчик гипертекста), но изначально оно расшифровывалось как Personal Home Page Tools (Инструменты для создания персональных веб-страниц).</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify"> <br>
<h2 align="center">Цели и задачи</h2>
Задачи:
1.	По заходу на страницу выведите сколько дней осталось до нового года.<br>
2.	Дан инпут и кнопка. В этот инпут вводится год. По нажатию на кнопку выведите на экран, високосный он или нет.<br>
3.	Дан инпут и кнопка. В этот инпут вводится дата в формате '01.12.1990'. По нажатию на кнопку выведите на экран день недели, соответствующий этой дате, например, 'воскресенье'.<br>
4.	По заходу на страницу выведите текущую дату в формате '12 мая 2015 года, воскресенье'.<br>
5.	Дан инпут и кнопка. В этот инпут вводится дата рождения в формате '01.12.1990'. По нажатию на кнопку выведите на экран сколько дней осталось до дня рождения пользователя.<br>
6.	По заходу на страницу выведите сколько дней осталось до ближайшей масленницы (последнее воскресенье весны).<br>
7.	Дан инпут и кнопка. В этот инпут вводится дата рождения в формате '31.12'. По нажатию на кнопку выведите знак зодиака пользователя.<br>
8.	Дан массив праздников. По заходу на страницу, если сегодня праздник, то поздравьте пользователя с этим праздником.<br>
9.	Сделайте скрипт-гороскоп. Внутри него хранится массив гороскопов на несколько дней вперед для каждого знака зодиака. По заходу на страницу спросите у пользователя дату рождения, определите его знак зодиака и выведите предсказание для этого знака зодиака на текущий день.<br>
10.	Дан текстареа и кнопка. В текстареа вводится текст. По нажатию на кнопку выведите количество слов в тексте, количество символов в тексте, количество символов за вычетом пробелов.<br>
11.	Дан текстареа и кнопка. В текстареа вводится текст. По нажатию на кнопку нужно посчитать процентное содержание каждого символа в тексте.<br>
12.	Дан массив слов, инпут и кнопка. В инпут вводится набор букв. По нажатию на кнопку выведите на экран те слова, которые содержат в себе все введенные буквы.<br>
13.	Дан текстареа и кнопка. В текстареа через пробел вводятся слова. По нажатию на кнопку выведите слова в таком виде: сначала заголовок 'слова на букву а' и под ним все слова, которые начинаются на 'а', потом заголовок 'слова на букву б' и все слова на 'б' и так далее. Буквы должны идти в алфавитном порядке. Брать следует только те буквы, на которые начинаются наши слова. То есть: если нет слов, к примеру, на букву 'в' - такого заголовка тоже не будет.<br>
14.	Дан инпут и кнопка. В этот инпут вводится строка на русском языке. По нажатию на кнопку выведите на экран транслит этой строки.<br>
15.	Дан инпут, 2 радиокнопочки и кнопка. В инпут вводится строка, а с помощью радиокнопочек выбирается - нужно преобразовать эту строку в транслит или из транслита обратно.<br>
16.	Дан массив с вопросами и правильными ответами. Реализуйте тест: выведите на экран все вопросы, под каждым инпут. Пользователь читает вопрос, пишет свой ответ в инпут. Когда вопросы заканчиваются - он жмет на кнопку, страница обновляется и вместо инпутов под вопросами появляется сообщение вида: 'ваш ответ: ... верно!' или 'ваш ответ: ... неверно! Правильный ответ: ...'. Правильно отвеченные вопросы должны гореть зеленым цветом, а неправильно - красным.<br>
17.	Модифицируем предыдущую задачу: пусть теперь тест показывает варианты ответов и радиокнопочки. Пользователь должен выбрать один и вариантов.<br>
18.	Модифицируем предыдущую задачу: пусть теперь на один вопрос может быть несколько правильных ответов. Пользователь должен отметить один или несколько чекбоксов.<br>
19.	Напишите скрипт, который будет считать факториал числа. Само число вводится в инпут и после нажатия на кнопку пользователь должен увидеть результат.<br>
20.	Напишите скрипт, который будет находить корни квадратного уравнения. Для этого сделайте 3 инпута, в которые будут вводиться коэффициенты уравнения.<br>
21.	Даны 3 инпута. В них вводятся числа. Проверьте, что эти числа являются тройкой Пифагора: квадрат самого большого числа должен быть равен сумме квадратов двух остальных.<br>
22.	Дан инпут и кнопка. В инпут вводится число. По нажатию на кнопку выведите список делителей этого числа.<br>
23.	Дан инпут и кнопка. В инпут вводится число. По нажатию на кнопку разложите число на простые множители.<br>
24.	Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите список общих делителей этих двух чисел.<br>
25.	Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите наибольший общий делитель этих двух чисел.<br>
26.	Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите наименьшее число, которое делится и на одно, и на второе из введенных чисел.<br>
27.	Даны 3 селекта и кнопка. Первый селект - это дни от 1 до 31, второй селект - это месяцы от января до декабря, а третий - это годы от 1990 до 2025. С помощью этих селектов можно выбрать дату. По нажатию на кнопку выведите на экран день недели, соответствующий этой дате, например, ‘воскресенье'.
<br>



Код на PHP
```php
//1 
<?php
 $var = 'abcde';
 echo $var[0]; //выведем букву 'h'
 echo $var[1]; //выведем букву 'e'
 echo $var[4]; //выведем букву 'o'
?><br>
//2
<?php
 echo 60 * 60 * 24;
?><br>
//3
<?php
 $var = 1;
 $var += 12;
 $var -= 14;
 $var *= 5;
 $var /= 7;
 $var++;
 $var--;
 echo $var;
?><br>
//4
<?php
$a = 3;
echo $a;
?><br>
//5
<?php
$a = 10;
$b = 2;
echo $a + $b;
echo $a - $b;
echo $a * $b;
echo $a / $b;
?><br>
//6
<?php
$c = 15;
$d = 2;
$result = $c + $d;
echo $result;
?><br>
//7
<?php
$a = 10;
$b = 2;
$c =5;
echo $a + $b + $c;
?><br>
//8
<?php
$a = 17;
$b = 10;
$c = $a - $b;
$d = 7;
$result = $c + $d;
echo $result;
?><br>
//9
<?php
$text = 'Привет, Мир!';
echo $text;
?><br>
//10
<?php
$text1 = 'Привет, ';
$text2 = 'Мир!';
echo $text1 . $text2;
?><br>
//11
<?php
$name = 'Димас';
echo 'Привет, ' . $name . '!';
?><br>
//12
<?php
$age = 22;
echo 'Мне ' . $age . ' года!';
?><br>
//13
<?php
$text = 'abcde';
echo $text[0];
echo $text[2];
echo $text[4];
?><br>
//14
<?php
$text = 'abcde';
$text[0] = '!';
?><br>
//15
<?php
$num = '12345';
$sum = $num[0] + $num[1] + $num[2] + $num[3] + $num[4];
?><br>
//16
<?php
$hour = 60 * 60;
$day = $hour * 24;
$month = $day * 30;
?><br>
//17
<?php
$hour = 0;
$min = 19;
$sec = 33;
echo $hour . ':' . $min . ':' . $sec;
?><br>
//18
<?php
$a = 3;
$a *= $a;
echo $a;
?><br>
//19
<?php
$var = 47;
$var += 7;
$var -= 18;
$var *= 10;
$var /= 20;
echo $var;
?><br>
//20
<?php
$text = 'Я';
$text .= ' хочу';
$text .= ' знать';
$text .= ' PHP!';
echo $text;
?><br>
//21
<?php
$var = 10;
$var++;
$var++;
$var--;
echo $var;
?><br>

//22
<?php
$var = 10;
$var += 7;
$var++;
$var--;
$var += 12;
$var *= 7;
$var -= 15;
echo $var;
?>
```

CODEWARS
```JavaScript
function findAverage(array) {
  let total = 0;
  let average = 0;
  if (array.length === 0) {
    return 0;
  } else {
    for (let i = 0; i < array.length; i++) {
      total += array[i]
    }
    average = total / array.length
    return average;
  }
}
function findEvenIndex(arr) {
  var sum = 0,
  leftSum = 0;
  for (var i = 0; i < arr.length; i++) {
    sum = sum + arr[i];
  }
  for (var i = 0; i < arr.length; i++) {
    sum = sum - arr[i];
    if (leftSum === sum) {
      return i;
    }
    leftSum = leftSum + arr[i];
  }
  return -1;
}
function alphabetPosition(text) {
  let sentence = text.toLowerCase().split("");
  for (let i = sentence.length - 1; i >= 0; i--) {
    if(sentence[i].match(/[a-z]/) === null) {
      sentence.splice(i, 1);
    }
  }
  let alphaArr = [];
  for (let i = 0; i < 26; i++) {
    alphaArr.push(String.fromCharCode(97 + i));
  }
  return sentence.map(item => alphaArr.indexOf(item) + 1).join(" ");
}
function breakChocolate(n,m) {
 if(n > 0 && m > 0) {
      return n * m - 1;
  } else {
    return 0;
  }
}
```
КОДЕ
```JavaScript
const express = require('express');
const QRCode = require('qrcode');
const app = express();

app.get('/generate', async (req, res) => {
  const url = req.query.url;

  if (!url) {
    return res.status(400).send('URL не указан.');
  }
//QRCode.toDataURL() для генерации QR-кода на основе переданного URL. 
try {
  const qr = await QRCode.toDataURL(url, {
  width: 600, 
  height: 600, 
  color: {
  dark: '#081272', // Цвет  модулей QR-кода
  light: '#ffffff' // Цвет светлых модулей QR-кода
  },
  margin: 10 
  });
  res.send(`<img src="${qr}" />`);
  } catch (err) {
  res.status(500).send('Ошибка при создании QR-кода.');
  }
  });
app.get('/', async (req, res) => {
    res.send("добавить  /generate?url=https://vk.com/dmitriy_andreev65")
  });

app.listen(3000, () => {
  console.log(`Сервер запущен на порту 3000`);
});
```
ПОЧТА
```JavaScript
const nodemailer = require('nodemailer');


const smtpConfig = {
  host: 'smtp.mail.ru',
  port: 587,
  secure: false, // true для SSL, false для других
  auth: {
    user: 'dimasandreev071@mail.ru',
    pass: 'jH6PgYsNgQ6iYz0E3DxV',
  },
};

//  для отправки почты
const transporter = nodemailer.createTransport(smtpConfig);

// Параметры 
const mailOptions = {
  from: 'dimasandreev071@mail.ru',
  to: 'dimasandreev019@gmail.com',
  subject: 'Enotik',
  text: 'Poloskyn',
 
};

// Отправляем 
transporter.sendMail(mailOptions, (error, info) => {
  if (error) {
    return console.log('Ошибка отправки письма:', error);
  }
  console.log('Письмо успешно отправлено:', info.messageId);
});
```
  <h2 style="text-align: center">ВЫВОД</h2>
 PHP — одним из самых популярных серверных языков программирования для веб-разработки. Он используется в следующих сферах:

Веб-программирование. Используется для создания динамических веб-сайтов и веб-приложений. С помощью PHP можно генерировать интерактивные формы, обрабатывать данные, работать с БД и создавать динамический контент.

Разработка фреймворков. Есть несколько PHP-фреймворков (Laravel, Symfony, Zend Framework), упрощающих разработку веб-приложений и облегчающих реализацию стандартных функций.

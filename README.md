<h1>Инструкция по копированию базы данных с ssms для студентов КИУ</h1>
<h3>!!!Перед началом выполнения инструкции необходимо отключить антивирус на вашем ПК</h3>
<details>
<summary>Отключение антивируса (раскрывается)</summary>

Нажимаем на значок антивируса
<img src="images/antivirus1.png" alt="Значок антивируса">

Переходим в раздел "Защита от вирусов и угроз"
<img src="images/antivirus2.png" alt="Переход в нужынй раздел">

Переходим в управление настройками
<img src="images/antivirus3.png" alt="Управление настройками">

Переключаем все ползунки
<img src="images/antivirus4.png" alt="Переключение ползунков">

Готово
</details>
<h2>1 часть. Установка sql server и ssms</h2>

<h3>Установка sql server:</h3> <a href="https://github.com/MaksimFomin06/instructions-for-copying-a-database-from-SSMS/raw/refs/heads/main/sql%20server/SQL2022-SSEI-Dev.exe?download=" download>SQL Server </a>
<details>
<summary>Инструкция по запуску (раскрывается)</summary>
<ul>
<li>
Запускаем файл
<img src="images/sql1.png" alt="Запуск exe файла">
</li>
<li>
В всплывающем окне разрешаем внесение изменений на устройстве("Да")
</li>
<li>
Выбираем тип установки "Базовая"
<img src="images/sql2.png" alt="Базовая">
</li>
<li>
Нажимаем "Принять"
<img src="images/sql3.png" alt="">
</li>
<li>
Проверяем место установки и нажимаем кнопку "Установить"
<img src="images/sql4.png" alt="">
</li>
<li>
Ждем конца установки. Размер ~8.5gb.
Нажимаем "Закрыть" и "Да"
<img src="images/sql5.png" alt="">
</li>
</ul>
</details>

<h3>Скачать ssms:</h3> <a href="https://github.com/MaksimFomin06/instructions-for-copying-a-database-from-SSMS/raw/refs/heads/main/ssms/SSMS-Setup-RUS.exe?download=" download>SSMS-Setup-RUS.exe ~695mb</a>
<details>
<summary>Инструкция по запуску (раскрывается)</summary>
<ul>
<li>
Запускаем файл
<img src="images/ssms1.png" alt="">
</li>
<li>
В всплывающем окне разрешаем внесение изменений на устройстве("Да")
</li>
<li>
Проверяем расположение и кнопку "Установить".
После установки нажимаем "Закрыть"
<img src="images/ssms2.png" alt="">
</li>
</ul>
</details>
<h2>2 часть. Настройка ssms</h2>
<details>
<summary>Настройка (раскрывается)</summary>
<ul>
<li>
Открываем ssms. Нас встречает такое меню.
<img src="images/ssms3.png" alt="">
</li>
<li>
Далее в окне выбираем "Продолжить обзор"
<img src="images/ssms4.png" alt="">
</li>
<li>
Выбираем как на фото. Далее "ОК" и "Соединить"
<img src="images/ssms5.png" alt="">
</li>
</ul>
</details>
<h2>3 часть. Копирование БД с сервера</h2>
<details>
<summary>Копирование бд (раскрывается)</summary>
<ul>
<li>
Правой кнопкой мыши нажимаем на нужную БД
<img src="images/copy1.png" alt="">
</li>
<li>
Нажимаем "Задачи" -> "Сформировать скрипты"
<img src="images/copy2.png" alt="">
</li>
<li>
Выйдет такое меню
<img src="images/copy3.png" alt="">
</li>
<li>
Нажимаем "Далее"
</li>
<li>
Выбираем как на фото, затем "Далее"
<img src="images/copy4.png" alt="">
</li>
<li>
Нажимаем дополнительно. "Сформировать скрипт для зависимостей -> True"
<img src="images/recovery7.png" alt="">  
</li>
<li>
Далее выбираем параметры сохранения и обязательно запоминаем путь сохранения и название файла. Нажимаем "Далее" два раза
<img src="images/copy5.png" alt="">
</li>
<li>
Итоговый результат. Нажимаем "Готово"
<img src="images/copy6.png" alt="">
</li>
</ul>
</details>
<h2>4 часть. Копирование бд в ssms</h2>
<details>
<summary>Инструкция по копированию</summary>
<ul>
<li>
В ssms создаем базу данных с таким же названием как и на сервере
<img src="images/recovery.png" alt="">
</li>
<li>
Выйдет окно. В "Имя базы данных" пишем название БД. Нажимаем "ОК"
<img src="images/recovery3.png" alt="">
</li>
<li>
Находим наш файл в проводнике, нажимаем на него два раза
<img src="images/recovery1.png" alt="">
</li>
<li>
Файл откроется в ssms и нам нужно будет его выполнить
<img src="images/recovery2.png" alt="">
</li>
<li>
Если вы все сделали правильно то скрипт выполнится успешно
<img src="images/recovery4.png" alt="">
</li>
<li>
Можем проверить правильность копирования выводом случайных данных из БД
<img src="images/recovery5.png" alt="">
</li>
</ul>
</details>
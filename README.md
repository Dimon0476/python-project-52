### Hexlet tests and linter status:
[![Actions Status](https://github.com/Dimon0476/python-project-52/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/Dimon0476/python-project-52/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/72e67f235110f750217c/maintainability)](https://codeclimate.com/github/Dimon0476/python-project-52/maintainability)

https://railway.app/project/67d2670b-bf80-4501-ba3d-c9da23c1e953/service/0043f576-fff7-4769-b713-12fb5f866030

<h3>Менеджер задач</h3>
<p>Простое веб-приложения для управления задачами в компании или команде.
Реализовано на фреймворке <b>Django 4.1.4</b> используя встроенные представления на основе классов (CBV) и базу данных <b>PostgreSql</b>. Дизайн сайта - <a href='https://getbootstrap.com/docs/5.0/getting-started/introduction/'>Bootstrap v5.0</a></p>
<ul>
  <li>Регистрация и аутентификация пользователей.</li>
  <li>CRUD : пользователей, статусов, меток, задач.</li>
  <li>Доступ к статусам, меткам и задачам имеют только авторизированные пользователи.</li>
  <li>Пока задаче присвоен статус или метка, ее нельзя удалить.</li>
  <li>Присутсвует фильтрация задач.</li>
  <li>Локализация RU/EN. По умолачанию RU. Переведено с EN. Папка с переводами locale/ru/</li>
  <li>Подключен <a href='https://rollbar.com'>Rollbar</a> (сервис для отслеживания и сбора ошибок)</li>
  <li>Покрытие тестами</li>
</ul>
<h3>Переменные окружения</h3>
<p>Необходимо в корне проекта создать файл .env и записать туда значения переменных.</p>
<pre>
SECRET_KEY =
DATABASE_URL = postgres://USER:PASSWORD@HOST:PORT/NAME
ROLLBAR_TOKEN = 
</pre>
<h3>Установка</h3>
<pre>
$ git clone https://github.com/Dimon0476/python-project-52.git
$ cd python-project-52.git
$ make setup
# Сайт станет доступен по адресу http://127.0.0.1:8000/ и http://0.0.0.0:8000/ 
</pre>
<h1>Степин Сергей - "Помощник поступающему в 10 класс Лицея НИУ ВШЭ на направление МатИнфо"</h1>
<h2>Группа 10И1</h2>
<h2>Электронная почта: <a href="sstepin425@gmail.com">sstepin425@gmail.com</h2>

<h2><a href="https://vk.com/flex1smyl1fe">VK</a></h2>

<h3>[НАЗВАНИЕ]</h3>
"Калькулятор вероятности поступления в 10 класс Лицея НИУ ВШЭ на направление МатИнфо"
<h3>[ПРОБЛЕМНОЕ ПОЛЕ]</h3>
Учащиеся перед экзаменами, участием в олимпиаде или другой работе(самостоятельной, контрольной) часто задаются вопросами "Смогу ли я хорошо написать? Какой у меня шанс получить 5 по этой работе? Наберу ли я достаточно баллов?" Вступительные экзамены в Лицей НИУ ВШЭ в 10 (или 9) класс не являются исключением. Например, я сам очень волновался за свои шансы на поступление, и, думаю, это знакомо многим поступившим в лицей. Поэтому я хочу создать сайт, который собирает ответы на несколько вопросов и на основе ответов уже поступивших на МатИнфо с общего потока учеников выдает вероятность поступить на это направление. Примерные критерии: оценка по математике, участие в олимпиадах, обучение в физмат классе и т.д. Так ученик поймет, какие у него шансы поступить по сравнению с абитуриентами, которые уже поступили на МатИнфо. Также на сайте будут разделы, которые смогут помочь абитуриенту подготовиться к экзаменам. Сайт будет представлять собой некоторый инструмент по подготовке к поступлению на направление МатИнфо с информацией про направление и тренировками.
<h3>[ЗАКАЗЧИК / ПОТЕНЦИАЛЬНАЯ АУДИТОРИЯ]</h3>
<p>Ученики 9 класса, готовящиеся к поступлению в 10 класс Лицея НИУ ВШЭ на направление "Информатика, инженерия и математика".</p>
<h3>[АППАРАТНЫЕ ТРЕБОВАНИЯ]</h3>
<p>Браузеры Chrome(версия 80 и выше), Firefox(версия 70 и выше), Safari(версия 13.0 и выше) (браузеры и их версии, поддерживающие HTML5)</p>
<h3>[ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ]</h3>
<ul>
  <li>Переход на сайт по URL-адресу</li>
  <li>Регистрация на сайте и хранение результатов</li>
  <li>Главная страница, на которой будет кратко представлена информация о МатИнфо</li>
  <li>Возможность пройти форму/опрос для поределения шанса поступить на МатИнфо с учетом результатов поступивших</li>
  <li>После прохождения будут доступны подсказки: предметы, которые нужно подтянуть/побольше потренироваться, советы по подготовке</li>
  <li>Раздел, в котором будут собраны полезные материалы для подготовки к вступительным испытаниям</li>
  <li>Тренировки по демоверсиям экзаменов прошлых лет (онлайн-тест)</li>
  <li>Просмотр своих результатов по тренировке и получение советов (по какому предмету больше порешатьи поизучать)</li>
  <li>*Бонус: тест "Насколько ты МатИнфо?" - скорее просто небольшая деталь, которая привлечет внимание поступающего</li>
</ul>   
<h3>[ПОХОЖИЕ / АНАЛОГИЧНЫЕ ПРОДУКТЫ]</h3>
<p>Аналогичных или подобных расчетчиков вероятности поступления конкретно в "Лицей" нет. Существуют калькуляторы вероятности поступления в ВУЗы.</p>
<h3>[ИНСТРУМЕНТЫ РАЗРАБОТКИ]</h3>
<ul>
  <li>Excel, Google формы, MySQL - сбор, хранение, сортировка собранных данных</li>
  <li>HTML, CSS, JS - frontend часть</li>
  <li>Python (flask), SQL - backend(расчет по формуле, БД)</li>
</ul>
<h3>[ЭТАПЫ РАЗРАБОТКИ]</h3>
<ol>
  <li>Опрос учащихся Матинфо 10 и 11 класс (короткие "интервью" с ~10 людьми на выбора вопросов для формы; составление опроса(8-12 вопросов) и распространение среди учеников)</li>
  <li>Обработка данных опроса (сотавление таблицы результатов опроса)</li>
  <li>Формула вероятности(разработка формулы для расчета вероятности поступления с учетом всех критериев и их весов (<a href = "https://github.com/ssstepin/IT-project_repo/blob/main/algorithm.md">алгоритм разработки<a>))</li>
  <li>Backend часть проекта
    <ul>
      <li>Изучение организации БД(MySQL, SQL)</li>
      <li>Организация базы данных с хранящимися в ней профилями ответов на опрос</li>
      <li>Создание модуля расчета вероятности по формуле</li>
    </ul>
    </li>
  <li>Frontend часть проекта - html форма из 8-12 вопросов, запросы на backend, вывод результата</li>
  <li>Соединение backend'а и frontend'а (JS)</li>
  <li>URL - регистрация домена, хостинг, подключение</li>
  <li>Релиз(выкладка) - изучение процесса выкладки через git  кода на URL, выкладка кода на адрес "калькулятора"</li>
  <li>Тестирование</li>
  <li>Подготовка проекта к защите</li>
  <li>Дополнительно: после публикации списков рекомендованных к зачислению в Лицей весной-летом 2021 предложить рекомендованным пройти опрос (результаты будут в репозитории)</li>
</ol>
<h3>[ВОЗМОЖНЫЕ РИСКИ]</h3>
<ul>
  <li>Нехватка времени на изучение нужных материалов и необходимых навыков</li>
  <li>Проблемы с регистрацией домена</li>
  <li>Недостаточное количество собранных ответов на опрос</li>
</ul>

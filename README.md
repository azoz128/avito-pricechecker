# avito-pricechecker
Этот скрипт на Python использует библиотеку Selenium для автоматизации веб-браузера и сбора данных о ценах на товары с сайта Avito. Скрипт выполняет следующие действия:

Настраивает параметры для запуска браузера Google Chrome с помощью Selenium.
Открывает страницу поиска на Avito по заданному запросу.
Ожидает загрузки элементов страницы, содержащих информацию о ценах.
Извлекает цены из первых 20 найденных объявлений.
Обрабатывает и очищает текст цен, преобразуя их в числовой формат.
Вычисляет минимальную, максимальную и среднюю цену из собранных данных.
Выводит результаты на экран и предлагает сохранить их в текстовый файл.
При сохранении результатов, записывает данные в файл и предлагает открыть его.
Закрывает браузер и завершает выполнение программы.

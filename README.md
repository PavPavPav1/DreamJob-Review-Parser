## DreamJob Reviews Parser

Этот парсер написан преимущественно с помощью библиотеки **Selenium** и **BeautifulSoup**. Он позволяет автоматизировать сбор отзывов о том или ином работодателе с сайта **[DreamJob](https://dreamjob.ru/)**

Он создан для сбора отзывов о работодателе и последующей оценки здоровья HR бренда различными методами, такими как ручное кодирование или анализ тональности отзывов с помощью методов машинного обучения и другие.

### Для запуска потребуется:
1. Скачать ChromeDriver соответствующей версии с [сайта](https://chromedriver.com/download)
2. Добавить файлы **chromedriver** и **LICENSE.chromedriver** в отдельную папку
3. Прописать путь до **chromedriver** в переменной 
4. Прописать ссылку на работодателя, отзывы которого хотите получить 
5. Прописать путь сохранения файла

Парсер автоматически откроет браузер, зайдёт на сайт и автоматически листая его вниз, соберёт все отзывы и оценки в CSV таблицу.


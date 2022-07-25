Данный проект содержит в себе автоматизированные тесты по проверке функционала сайта ozon.ru.

Автотесты написаны на Python с использованием PyTest, Selenium и PageObject.

How to run:

Download driver for Chrome: https://chromedriver.chromium.org/downloads

Install all required python packages library

Run in terminal with line: python -m pytest -v --driver Chrome --driver-path <~>/chromedriver.exe tests/"enter the name of the file with autotests".py

Автотесты хранятся в папке tests.

Файл 01_tests_StartPage_links_01.py - содержит в себе автотесты, проверяющие корректность ссылок и переходов в меню из стартовой страницы сайта

Файл 02_tests_StartPage_Search_Menu.py - содержит в себе автотесты, проверяющие функционал модуля поиска товаров и сортировку по типу товаров на сайте

Файл 03_test_Card_Product.py - содержит в себе автотесты, проверяющие функционал карточки товаров представленных на сайте

Файл 04_test_ProfileMenu_Favorites.py - содержит в себе автотесты, проверяющие функционал модуля 'Избранное'

Файл 05_tests_ProfileMenu_Cart.py - содержит в себе автотесты, проверяющие функционал модуля 'Корзина'

Файл 06_tests_ProfileMenu_LogIn.py - содержит в себе автотесты, проверяющие некоторый функционал модуля 'Авторизация на сайте'

Файл ozon.py - содедржит в себе базу локаторов сайта, используемых в автотестах этого проекта

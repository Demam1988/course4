course4

Уважаемый пользователь!

Данный проект на Python предназначен для вывода информации о вакансиях с SuperJob и HeadHunter. Вакансии сохраняются в файл json. Вакансии можно сохранять, удалять, фильтровать. С какой платформы собирать вакансии - решает пользователь, путем ввода цифры. Предусмотрено 2 режима работы: Работа с платформами и работа с файлом, если он существует. В проекте используются следующие библиотеки и модули Python: json, requests, fake_useragent, ABC, pytest, pytest-cov

Описание файлов проекта:

main.py - основная функция, запуск кода.
classes.py - файл с описанием и методами используемых классов.
utils.py - исполняемые функции.
pyproject.toml - файл конфигурации проекта, описывающий всё, что нужно, чтобы управлять зависимостями проекта, запускать код на исполнение
.gitignore - содержит список файлов и папок проекта, которые игнорируются и не отслеживаются Git.
Инструкция по установке и запуску проекта: Проект следует клонировать.

Пример использования:

Привет!

Получить новые вакансии
Работать с файлом
1 Введите поисковый запрос (название вакансии): python разработчик Выберите платформу, с которой будем получать вакансии: 3. SuperJob 4. HeadHunter 5. SuperJob и HeadHunter 3

Выберите что делать?: 0. Вывести все вакансии

Вывести топ вакансий по зарплате
Отфильтровать вакансии по зарплате начиная с самой высокооплачиваемой
Отфильтровать вакансии по городу
Получить вакансии с зарплатой не ниже заданного уровня
Вывести вакансии по ключевым словам
Удалить вакансии у которых зарплата ниже заданного уровня
Закончить
Тестирование. Для тестирования используется paytest. Для запуска тестов необходимо выполнить команду: pytest Эта команда выполнит все тесты, которые находятся в папке /tests. Основные assert методы: assertEqual(a, b) - проверяет равенство a и b assertIsInstance(a, b) - проверяет, что a является экземпляром b (или его наследника) assertIn(x, y) - проверяет, что x в y assertNotIn(x, y) - проверяет, что x в y Команда для запуска тестов с подсчетом покрытия:
pytest --cov src --cov-report term-missing Команда для запуска тестов с генерацией отчета: pytest --cov src --cov-report html

Если у вас возникли вопросы или проблемы при использовании проекта, свяжитесь со мной по электронной почте kls75@yandex.ru или оставьте комментарий в Issues проекта на GitHub https://github.com/kanlar75/Course_-project_3/issues.

С уважением, Мамед 
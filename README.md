# 33.1
Итоговый проект по автоматизации тестирования (PJ-04) Ссылка на чек-лист, тест-кейсы и баг репорты:

(https://docs.google.com/spreadsheets/d/1tWVqB9nrJsSpx_vEfgdZ73obmD2UduyR8offI6QfFGo/edit?gid=0#gid=0)

Автотесты имеют названия отражающие ожидаемый результат и объект тестирования.
Команда для запуска всех тестов в пакете "tests":
python -m pytest -v --driver Chrome --driver-path C:\chromedriver.exe tests
Команда для запуска отдельного теста, например, в файле test_reg_page_check.py:
python -m pytest -v --driver Chrome --driver-path C:\chromedriver.exe tests\test_reg_page_check.py -k "test_reg_page_check_all_fields_text"

1) Сделать вариант класса ViewEng с текстом на английском языке, подключить к нему интерфейс iGetView. Класс ViewEng подключить к контроллеру.
2) Сделать вариант класса Model с хранилищем типа HashMap<Long,Student>, подключить к нему интерфейс iGetModel. Класс подключить к контроллеру.
3) Добавить команду в метод run класса контролер по удалению студента:
Для этого: Добавить в switch команду DELETE
- запросить у пользователя номер студента на удаление
- вызов удаления у модели(метод добавить в интерфейс iGetModel)
- если такого нромера нет, то сообщить об этом
Весь код прокомментировать и добавить само-документацию.

(задача со *)
1) решить базовое решение
2) сделать выбор языка при запуске контроллера
3) сделать несколько моделей и студентов распределить по ним
4) если не найден студент в одной модели продолжить поиск в следующей
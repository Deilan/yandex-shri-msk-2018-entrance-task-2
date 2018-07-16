В этом репозитории находятся материалы тестового задания по вёрстке для шестой [Школы разработки интерфейсов](https://academy.yandex.ru/events/frontend/shri_msk-2018).

**Макеты:**

- [десктоп](desktop-images)
- [мобильные телефоны](touch-images)

**Спецификация:**

- [десктоп](desktop-guide)
- [мобильные телефоны](touch-guide)

## Задание

Нужно сверстать страницу списка переговрок и форму редактирования встречи. Для каждой страницы дизайнер подготовил макет (отдельно для большого экрана и мобильных телефонов).

Важно сверстать страницы в точном соответствии с макетами. Если какие-то части макетов покажутся вам непонятными, обязательно задавайте уточняющие вопросы — пишите на адрес frontendschool@yandex-team.ru.

### Страница списка переговорок

- В шапке отображается логотип сервиса и кнопка «Создать встречу».
- Слева отображается список переговорок с разбивкой по этажам.
- Справа от списка отображается диаграмма встреч.
- При клике на встречу всплывает тултип с информацией о ней.
- При наведении на свободное время появляется кнопка добавления встречи и подсвечивается название комнаты.
- Названия переговорок, у которых не осталось свободных периодов времени, отображаются менее контрастно.
- На диаграмме вертикальной линией показано текущее время.
- Сверху от списка отображается текущая дата и кнопки перехода к соседним датам.
- При клике на текущую дату отображается календарь на три месяца.
- Макет календаря дизайнер не нарисовал, сверстайте этот блок на своё усмотрение.

### Страница редактирования встречи

- Есть возможность ввести название встречи, дату и время начала и окончания встречи, выбрать участников и переговорку.
- Выпадающий календарь для поля выбора даты делать необязательно, но это будет плюсом.
- Участники встречи выбираются из списка, который появляется, когда пользователь переходит на поле поиска сотрудника.
- Выбранные участники отображаются под полем ввода.
- Если переговорка не выбрана, отображается список доступных комнат.
- Если переговорка выбрана, то вместо списка отображается только она (с возможностью отменить выбор).

## Критерии

В первую очередь мы будем проверять, свёрстаны ли страницы в точном в соответствии с макетами.
Всё должно работать в двух последних версиях Google Chrome, Яндекс.Браузера, Microsoft Edge, Mozilla Firefox, Safari, Opera. По возможности используйте приёмы безопасной деградации CSS.

Уделите внимание организации и оформлению кода. Оптимизация производительности и автоматизация будут плюсом.
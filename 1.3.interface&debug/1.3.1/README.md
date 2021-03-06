# Задача

Нужно реализовать комплексное приложение для мониторинга здоровья.

## Требуется реализовать 3 экрана приложения:

**1. Стартовый экран, на нём:** 

* Вверху экрана разместить картинку – иконку приложения, рядом с ней расположить название приложения «Комплексная система мониторинга здоровья» и фамилию автора. 

* Ниже нужно расположить согласно правилам эргономики поля для ввода ФИО и возраста пациента. 

* Ещё ниже нужно разместить кнопку «Сохранить». При нажатии на кнопку Сохранить программа должна считать данные из формы и записать в поля внутренней структуры, проверив, при необходимости, введенные данные. 

* Ниже на форме расположить панель навигации – две кнопки. При нажатии на первую – переход на экран записи показателей давления, вторая – переход на экран записи жизненных показателей здоровья.

**2. Экран записи давления – нужно реализовать форму для записи показаний давления:**

* После считывания показателей, нужно сохранить их во внутреннюю структуру данных. 

* На экран добавить элементы управления для ввода значений (описание класса ниже) и кнопку Сохранить. При сохранении надо добавлять новое значение в коллекцию значений в текущей Activity.

**3. Экран записи жизненных показателей:**

* После считывания показателей, нужно сохранить их во внутреннюю структуру данных. 

* На экран добавить элементы управления для ввода значений (описание класса ниже) и кнопку Сохранить. При сохранении надо добавлять новое значение в коллекцию значений в текущей Activity.



Для каждого экрана нужно организовать собственную структуру данных – отдельный класс.

Для стартового экрана – класс с полями :

- ФИО – строка
- Возраст – целое число

Для экрана записи давления – коллекцию с показаниями (тоже свой класс).

Выберите самостоятельно подходящую коллекцию для хранения списка значений класса Индивидуальных показателей.

Класс индивидуальных показателей:

- Верхнее давление – целое число;
- Нижнее давление – целое число;
- Пульс – целое число;
- Тахикардия – флаг да или нет;
- Дата замера – дата и время.

Для экрана записи жизненных показателей – аналогично коллекцию для хранения списка значений.

Класс жизненных показателей:

- Вес – дробное число;
- Количество шагов – целое число.



## Реализация

1. Посмотрите в лекции есть план, по сути это план реализации приложения, вам нужно составить такой же план для реализации своего приложения.

2. Используя один из сайтов (или если найдёте удобнее/лучшее) из презентации для проектирования интерфейса спроектируйте интерфейс. Как минимум нужно представить на проверку макеты трёх экранов приложения. Не забудьте про эргономику мобильных приложений.

3. Перенесите интерфейс в приложение, создайте приложение с тремя экранами и реализуйте в них интерфейс согласно макетам.

4. Создайте классы для хранения данных для каждого окна.

5. Реализуйте логику: считывание из форм, проверку значений, преобразование значений.

6. Сделайте безопасными все участки кода, где возможна ошибка.

7. В случае ошибок отладьте приложение, запустив его в режиме debug.

8. Добавьте логирование действий пользователя: Log.i для каждого нажатия на любую кнопку в приложении.

## Результаты и сдача домашнего задания

Вместе  с исходным кодом приложения нужно отправить на проверку макеты и, если сделаете, схему переходов (показывает как с одного экрана перейти на другой). Макеты экранов можно сохранить как графические файлы в папку с приложением и закачать на github вместе с файлами исходного кода. 

НО лучше отправить ссылку на макет в личном кабинете на проверку вместе с ссылкой на код (обычно сервисы для создания макетов позволяют делать прямые ссылки на макет). Также можно сделать страницу на GitHub и разместить там макеты приложения. 

При сдаче домашнего задания укажите, пожалуйста, где искать макеты интерфейса.

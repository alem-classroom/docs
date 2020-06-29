# Создание проекта в github classroom

Для возможности автоматически создавать репозитрии для учащегося нам необходимо создать `assignment` в `github classroom`

Каждый курс с проектами имеет свой `classroom`
В нем находятся все `assignment`, это название урока.
Перейдите на страницу [github classroom](https://classroom.github.com/classrooms)

Если в списке классов, нет названия вашего курса. Создайте его. <br>
Нажмите на вкладку для создания нового `classroom`

![](./img/create-assignment-1.png)

Выбираем `alem-classroom`. В этом репозитории будут находится все `template`.
![](./img/create-assignment-2.png)

Далее, вводим название курса. Его можно узнать из файла `.config` вашего курса.<br>
Параметр `name`
![](./img/create-assignment-3.png)

Теперь создаем `assignment`
![](./img/create-assignment-4.png)

`Title` должен быть в формате: <br>
`[lesson-name]-[course-name]-task` <br>
Пример: `01-intro-js-intro-task`<br>
Все параметры можно получить в репозитории курса
![](./img/create-assignment-6.png)


Нам нужно выбрать ранее подготовленный `template` в котором есть тестовый файл и директория `.github`. <br>
Подробнее в [create-template.md](./create-template.md) <br>
Выбор IDE опционален.

![](./img/create-assignment-5.png)


Добавляем ссылку в `readme.md` нашего урока.
И добавляем параметр `type` со значением `project` для урока курса.

![](./img/create-assignment-7.png)


# Создание проекта в github classroom

Для возможности автоматически создавать репозитрии для учащегося нам необходимо создать `assignment` в `github classroom`

Каждый курс имеет свой `classroom`
В нем находятся `assignment` c сигнатурой `student-${course_name}`.
> Пример для python-introduction: \
> `student-python-introduction`

Перейдите на страницу [github classroom](https://classroom.github.com/classrooms)

Если в списке классов, нет названия вашего курса. Создайте его. <br>
Нажмите на кнопку для создания нового `classroom`

![](./img/create-assignment-1.png)

Выбираем `alem-classroom`. В этой организации будут находится все `template` и `test`.
![](./img/create-assignment-2.png)

Далее, вводим название курса. Его можно узнать из файла `.config` вашего курса.<br>
Параметр `name`

![](./img/create-assignment-3.png)


Теперь создаем `assignment`

![](./img/create-assignment-4.png)


`Title` должен быть в формате: <br>
`student-[course-name]` <br>

![](./img/create-assignment-5.png)

Нам нужно выбрать ранее подготовленный `template` в котором есть файл c функциями и директория `.github`. <br>
Подробнее в [create-template.md](./create-template.md) <br>
Выбор IDE опционален.

![](./img/create-assignment-6.png)

Добавляем ссылку в `readme.md` нашего урока.
И добавляем параметр `type` со значением `project` для урока курса.

![](./img/create-assignment-7.png)


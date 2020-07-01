# Создание template для проекта

Репозиторий с проектом должен находиться в организации [alem-classroom](https://github.com/alem-classroom)

Формат названия репозитория

`[lesson-name]-[course-name]`<br>
Пример: `intro-js-intro`<br>

## JS project struct
[js template example](https://github.com/alem-classroom/js-template)

```
|__ lesson-name-course-name
    |__ .github
        |-- workflows
            |-- main.yml
    |__ test
        |-- test.js
    |__ package.json
    |__ *.json
    |__ README.md
```

## Python project struct
[python template example](https://github.com/alem-classroom/python-template)
```
|__ lesson-name-course-name
    |__ .github
        |-- workflows
            |-- main.yml
    |__ *_test.py
    |__ *.py
    |__ requirements.txt
    |__ README.md
```
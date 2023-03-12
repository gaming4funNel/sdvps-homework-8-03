# Домашнее задание к занятию "8.3. GitLab" - Иванов Игорь


### Задание 1



Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в этом репозитории.
Создайте новый проект и пустой репозиторий в нём.
Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.
В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.

![git](https://github.com/gaming4funNel/sdvps-homework-8-03/blob/main/img/gitlab-runner.png)
![git](https://github.com/gaming4funNel/sdvps-homework-8-03/blob/main/img/gitlab-runner2.png)
---

### Задание 2

Что нужно сделать:

Запушьте репозиторий на GitLab, изменив origin. Это изучалось на занятии по Git.
Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.
В качестве ответа в шаблон с решением добавьте:

файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне;
скриншоты с успешно собранными сборками.

![git](https://github.com/gaming4funNel/sdvps-homework-8-03/blob/main/img/gitlab-ci.png)

![git](https://github.com/gaming4funNel/sdvps-homework-8-03/blob/main/img/stage_test.png)
![git](https://github.com/gaming4funNel/sdvps-homework-8-03/blob/main/img/stage_build1.png)
![git](https://github.com/gaming4funNel/sdvps-homework-8-03/blob/main/img/stage_build2.png)

## Дополнительные задания (со звездочкой*)

### Задание 3*

Измените CI так, чтобы:

этап сборки запускался сразу, не дожидаясь результатов тестов;
тесты запускались только при изменении файлов с расширением *.go.
В качестве ответа добавьте в шаблон с решением файл gitlab-ci.yml своего проекта или вставьте код в соответсвующее поле в шаблоне.


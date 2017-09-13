## Laboratory work II

Данная лабораторная работа посвещена изучению утилит для разработки проектов

## Tasks

- [x] 1. Ознакомиться со ссылками учебного материала
- [x] 2. Выполнить инструкцию учебного материала
- [x] 3. Составить отчет и отправить ссылку личным сообщением в **Slack**

 ВЫПОЛНЕНИЕ ЛАБОРАТОРНОЙ 02:
 
```
$ export GITHUB_USERNAME=desta-study // добавляем переменную в среду окружения 

$ export GIST_TOKEN=bbe827a785aeb47ce4a6fbac13dd1ab66670d5d0     // добавляем переменную в среду окружения

$ alias edit=subl   // сокращаем команду edit

$ cd ~  // выход в домашний каталог 

$ mkdir -p workspace/labs/projects/     // создаем новый каталог( -р не выдает ошибок, если существует, создает
                    родительские каталоги, если необходимо)

$ mkdir -p workspace/labs/tasks/    // создаем новый каталог

$ mkdir -p workspace/labs/reports/     // создаем новый каталог

$ cd ~/workspace/labs/     // переход по заданному пути

$ export LAB_NUMBER=02  // добавляем переменную в среду окружения 

$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}    // создаем новую директорию, переходим внутрь и создаем пустой репозиторий, затем добавляем новый удалённый репозиторий для указанного URL, обновляем рабочую директорию до последнего коммита

Клонирование в «tasks/lab02»… remote: Counting objects: 28, done. remote: Total 28 (delta 0), reused 0 (delta 0), pack-reused 28 Распаковка объектов: 100% (28/28), готово.

$ mkdir reports/lab${LAB_NUMBER}    // создаем новый каталог

$ cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md    // переход по заданному пути
     
$ cd reports/lab${LAB_NUMBER}     // переход по заданному пути

$ edit REPORT.md   //открытие в SUBLIME TEXT REPORT.md
```

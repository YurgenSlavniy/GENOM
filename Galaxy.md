#  Galaxy Training! 
### GTN Learning Pathway:

We recommend you follow the tutorials in the order presented on this page. They have been selected to fit together and build up your knowledge step by step. If a lesson has both slides and a tutorial, we recommend you start with the slides, then proceed with the tutorial. 

### Introduction to Galaxy and Sequence analysis

This learning path aims to teach you the basics of Galaxy and analysis of sequencing data. You will learn how to use Galaxy for analysis, and will be guided through the most common first steps of any genome analysis; quality control and a mapping or assembly of your genomic sequences.

New to Galaxy and/or the field of genomics? Follow this learning path to get familiar with the basics!

# Обучение Galaxy!
### Схема обучения GTN:

Мы рекомендуем вам следовать инструкциям в порядке, представленном на этой странице. Они были выбраны так, чтобы соответствовать друг другу и шаг за шагом накапливать ваши знания. Если в уроке есть и слайды, и учебное пособие, мы рекомендуем начать со слайдов, а затем перейти к учебному пособию.

### Введение в Galaxy и анализ последовательностей

Этот путь обучения направлен на то, чтобы научить вас основам Galaxy и анализу данных секвенирования. Вы узнаете, как использовать Galaxy для анализа, и пройдете через наиболее распространенные первые шаги любого анализа генома; контроль качества и картирование или сборка ваших геномных последовательностей.


# Module 1: Introduction to Galaxy
Get a first look at the Galaxy platform for data analysis. We start with a short introduction (video slides & practical) to familiarize you with the Galaxy interface, and then proceed with a slightly longer introduction tutorials where you perform a first, very simple, analysis.
### A short introduction to Galaxy

# МОДУЛЬ 1: Введение в Galaxy
Получите первый взгляд на платформу Galaxy для анализа данных. Мы начнем с краткого введения (видео слайды и практические занятия), чтобы познакомить вас с интерфейсом Galaxy, а затем перейдем к более длинным вводным учебным пособиям, в которых вы выполните первый, очень простой анализ.

### Короткое введение в Galaxy

### Overview
***Questions:***
- How to get started in Galaxy

***Objectives:***
- Learn how to upload a file
- Learn how to use a tool
- Learn how to view results
- Learn how to view histories
- Learn how to extract and run a workflow
- Learn how to share a history

***Time estimation:*** 40 minutes

***Level:*** Introductory Introductory

***Supporting Materials:***

***Last modification:*** May 9, 2023

***License:*** Tutorial Content is licensed under Creative Commons Attribution 4.0 International License. The GTN Framework is licensed under MIT

***purlPURL:*** https://gxy.io/GTN:T00190 

# Обзор
Это краткое введение в пользовательский интерфейс Galaxy.
Мы рассмотрим ключевые задачи в Galaxy: 
- загрузку файлов,
- использование инструментов,
- просмотр истории 
- выполнение рабочих процессов.

# Overview
- This is a short introduction to the Galaxy user interface - the web page that you interact with.
- We will cover key tasks in Galaxy: uploading files, using tools, viewing histories, and running workflows.

# Оглавление (Agenda):
1) Overview
- 1.1. What does Galaxy look like?
2) Key Galaxy actions
- 2.1. Name your current history
- 2.2. Upload a file
- 2.3. Use a tool
- 2.4. View results
- 2.5. Run another tool
- 2.6. Re-run that tool with changed settings
- 2.7. Share your history
- 2.8. Convert your analysis history into a workflow
- 2.9. Create a new history
- 2.10 Look at all your histories
- 2.11 Run workflow in the new history
3) Conclusion

# What does Galaxy look like?
### > Hands-on: Log in to Galaxy

1) Open your favorite browser (Chrome, Safari or Firefox as your browser, not Internet Explorer!)
2) Browse to your Galaxy instance
3) Log in or register

# Как выглядит Galaxy?
### > Практическое занятие: войдите в Galaxy

1) Откройте ваш любимый браузер. (Chrome, Safari или Firefox в качестве браузера, а не Internet Explorer!)
2) Зайдите на сайт ***https://usegalaxy.org/***
3) Залогиньтесь или зарегестрируйтесь

`Комментарий:` Разные серверы Galaxy

Это изображение Galaxy Australia, расположенное на usegalaxy.org.au.

Конкретный сервер Galaxy, который вы используете, может выглядеть немного иначе и иметь другой веб-адрес:

- Основной сервер Galaxy - `usegalaxy.org`.
- Европейский сервер Galaxy - `usegalaxy.eu`.

# Homepage
The Galaxy homepage is divided into three panels:
- Tools on the left
- Viewing panel in the middle
- History of analysis and files on the right

The first time you use Galaxy, there will be no files in your history panel.

# Домашняя стартовая страница https://usegalaxy.org/
Стартовая страница Galaxy состоит из трёх панелей:
- `Tools`  Левая панель - `инструменты`
- `Viewing`  Центральная панель - `представления`
- `History of analysis`  Правая панель - `История анализа`
- 
При первом использовании Galaxy на панели истории не будет файлов.

# Key Galaxy actions
### Name your current history

Your “History” is in the panel at the right.

### > Hands-on: Name history
1) Go to the History panel (on the right)
2) Click on galaxy-pencil (Edit) next to the history name (which by default is “Unnamed history”)

`Comment:` In some previous versions of Galaxy, you will need to click on the history name to rename it as shown here: Screenshot of the galaxy interface with the history name being edited, it currently reads "Unnamed history", the default value.

3) Type in a new name, for example, “My Analysis”
4) Click on Save

`Comment:` Renaming not an option?

If renaming does not work, it is possible you aren’t logged in, so try logging in to Galaxy first. Anonymous users are only permitted to have one history, and they cannot rename it.


# Ключевые действия Galaxy 
### Назовите свою текущую историю

Ваша «История» находится на панели справа

### > Практическое занятие: Назовите историю
1) Перейдите на панель `История` (справа)
2) Нажмите на `galaxy-карандаш` (Редактировать) рядом с названием истории (которое по умолчанию «Безымянная история»)

`Комментарий:` В некоторых предыдущих версиях Galaxy вам нужно будет щелкнуть имя истории, чтобы переименовать ее.

3) Введите новое имя, например, «Мой анализ».
4) Нажмите Сохранить

`Комментарий:` Переименование не вариант?

Если переименование не работает, возможно, вы не вошли в систему, поэтому сначала попробуйте войти в Galaxy. Анонимным пользователям разрешено иметь только одну историю, и они не могут ее переименовывать.

# Upload a file

Your “Tools” are in the panel at the left.

### > Hands-on: Upload a file from URL
1) At the top of the Tools panel (on the left), click galaxy-upload `Upload`
2) This brings up a box
3) Click `Paste/Fetch data`
4) Paste in the address of a file:
   > https://zenodo.org/record/582600/files/mutant_R1.fastq
5) Click `Start`
6) Click `Close`

Your uploaded file is now in your current history. When the file has uploaded to Galaxy, it will turn green.

`Comment:` After this you will see your first history item (called a “dataset”) in Galaxy’s right panel. It will go through the gray (preparing/queued) and yellow (running) states to become green (success).

`details:` Is this step taking a while.

Sometimes during courses, data upload gets a little slow. You can also import data through a history link.

1) Import history from: `example input history`
2) Rename `galaxy-pencil` the the history to your name of choice.

*What is this file?* 

### > Hands-on: View the dataset content
1) Click on the galaxy-eye `(eye) icon`  next to the dataset name, to look at the file content

# Загрузка данных в Galaxy
### > Практическое занятие: загрузка файла по URL-адресу
1) В верхней части панели инструментов (слева) нажмите galaxy-upload `Загрузить`
2) Откроется окно загрузки
3) Нажмите `Вставить/Выбрать данные`
4) Вставьте адрес файла:
  > https://zenodo.org/record/582600/files/mutant_R1.fastq
5) Нажмите `старт`
6) Нажмите `закрыть`

Ваш загруженный файл теперь находится в вашей текущей истории. Когда файл будет загружен в Galaxy, он станет зеленым.

`Комментарий:` После этого вы увидите свой первый элемент истории (называемый «набором данных») на правой панели Galaxy. Он пройдет через серое (подготовка/в очереди) и желтое (выполняется) состояния, чтобы стать зеленым (успех).

`Детали:` Этот шаг занимает некоторое время.

Иногда во время курсов загрузка данных немного замедляется. Вы также можете импортировать данные через ссылку истории.

1) Импортировать историю из: `пример истории ввода`
2) Переименуйте `galaxy-pencil` историю на свое имя.

*Что это за файл?*
### > Практическое занятие: просмотр содержимого набора данных
1) Нажмите на значок `Galaxy глаза (глаза)` рядом с именем набора данных, чтобы просмотреть содержимое файла.

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

*What is this file?* 

### > Hands-on: View the dataset content
1) Click on the galaxy-eye `(eye) icon`  next to the dataset name, to look at the file content

The contents of the file will be displayed in the central Galaxy panel.

This file contains DNA sequencing reads from a bacteria, in FASTQ format:

```
@mutant-no_snps.gff-24960/1
AATGTTGTCACTTGGATTCAAATGACATTTTAAATCTAA
+
5??A9?BBBDDDBEDDBFF+FGHHIIHHHEIHIIHIIAH
```

***Figure 1***: A FastQ file of course has four lines per record: 
- the record identifier (`@mutant-no_snps.gff-24960/`),
- the sequence (`AATG…`),
- the plus character (`+`),
- and then the quality scores for the sequence (`5??A…`).


*Что это за файл?*
### > Практическое занятие: просмотр содержимого набора данных
1) Нажмите на значок `Galaxy глаза (глаза)` рядом с именем набора данных, чтобы просмотреть содержимое файла.

Содержимое файла отобразится на центральной панели Galaxy.

Этот файл содержит данные секвенирования ДНК бактерии в формате FASTQ:
```
@mutant-no_snps.gff-24960/1
AATGTTGTCACTTGGATTCAAATGACATTTTAAATCTAA
+
5??A9?BBBDDDBEDDBFF+FGHHIIHHHEIHIIHIIAH
```
***Рисунок 1***: Файл FastQ, конечно, имеет четыре строки на запись:
- идентификатор записи (`@mutant-no_snps.gff-24960/`),
- последовательность (`AATG…`),
- знак плюса (`+`),
- а затем оценки качества последовательности (`5??A…`).

# Use a tool

Let’s look at the quality of the reads in this file.
### > Hands-on: Use a tool
1) Type FastQC in the `tools panel` search box (top)  `FastQC Read Quality reports` (Galaxy Version 0.73+galaxy0)
2) Click on the `FastQC Tool`: toolshed.g2.bx.psu.edu/repos/devteam/fastqc/fastqc/0.73+galaxy0 tool

The tool will be displayed in the central Galaxy panel.

3) Select the following parameters:
- param-file “Raw read data from your current history”: the FASTQ dataset that we uploaded
- No change in the other parameters

4) Click Execute `Run Tool`

This tool will run and two new output datasets will appear at the top of your history panel.


# Используйте инструмент `Tools`
Давайте посмотрим на качество чтения в этом файле.
### > Практика: использование инструмента 'tools'
1) Введите `FastQC` в поле поиска «панель инструментов» (вверху) `«FastQC Read Quality Reports»` (версия Galaxy 0.73+galaxy0)
2) Нажмите «Инструмент FastQC»: toolshed.g2.bx.psu.edu/repos/devteam/fastqc/fastqc/0.73+galaxy0

Инструмент отобразится на центральной панели Galaxy.

3) Выберите следующие параметры:
- param-file «Необработанные данные чтения из вашей текущей истории»: набор данных FASTQ, который мы загрузили
- без изменений других параметров

4) Нажмите «Выполнить» `Run Tool`.

Этот инструмент запустится, и в верхней части панели истории появятся два новых выходных набора данных.

# View results
We will now look at the output dataset called `FastQC on data 1: Webpage`.

`Comment:` 
- Note that Galaxy has given this dataset a name according to both the tool name (“FastQC”) and the input (“data 1”) that it used.
- The name “data 1” means the dataset number 1 in Galaxy’s current history (our FASTQ file).

### > Hands-on: View results
- Once it’s green, click on the galaxy-eye `(eye) icon` next to the “Webpage” output dataset.
- The information is displayed in the central panel

This tool has summarised information about all of the reads in our FASTQ file.

`Question:`
- What was the length of the reads in the input FASTQ file?
- Do these reads have higher quality scores in the centre or at the ends?
  
`Solution:`
- 150 bp
- In the center

# Посмотреть Результаты
Теперь мы рассмотрим выходной набор данных под названием «FastQC для данных 1: веб-страница».

`Комментарий:`
- Обратите внимание, что Galaxy дала этому набору данных имя в соответствии с именем инструмента («FastQC») и входными данными («данные 1»), которые он использовал.
- Название «данные 1» означает набор данных номер 1 в текущей истории Galaxy (наш файл FASTQ).

### > Практика: просмотр результатов
- Как только обработанный инструментом файл станет зеленым, щелкните значок глаза галактики (глаз) рядом с выходным набором данных «Веб-страница».
- Информация отображается на центральной панели

Этот инструмент обобщил информацию обо всех чтениях в нашем файле FASTQ.

`Вопрос:`
- Какова была длина операций чтения во входном файле FASTQ?
- Эти чтения имеют более высокие показатели качества в центре или на концах?
  
`Решение:`
- 150 б.п.  Sequence length	150
- В центре

# FastQC
### FastQC Report
- Basic Statistics
- Per base sequence quality
- Per sequence quality scores
- Per base sequence content
- Per sequence GC content
- Per base N content
- Sequence Length Distribution
- Sequence Duplication Levels
- Overrepresented sequences
- Adapter Content

- Базовая статистика
- Качество базовой последовательности
- Показатели качества последовательности
- Содержимое базовой последовательности
- Содержимое GC для каждой последовательности
- В пересчете на базовое содержание азота
- Распределение длины последовательности
- Уровни дублирования последовательности
- Перепредставленные последовательности
- Содержимое адаптера

# Run another tool
Let’s run a tool to filter out lower-quality reads from our FASTQ file.
### > Hands-on: Run another tool
1) Type Filter by quality in the tools panel search box (top)
2) Click on the tool Filter by quality Tool:
`toolshed.g2.bx.psu.edu/repos/devteam/fastq_quality_filter/cshl_fastq_quality_filter/1.0.2+galaxy0`
3) Set the following parameters:
   - param-file “Input FASTQ file”: our initial FASTQ dataset
   - “Quality cut-off value”: 35
   - “Percent of bases in sequence that must have quality equal to / higher than cut-off value”: 80

4) Click Execute 'Run Tool'

After the tool has run, its output dataset will appear at the top of your History panel.

- This dataset will be called “Filter by quality on data 1”.
- Remember that Galaxy has named this file according to the tool it used (“Filter by quality”) and the input dataset (“data 1”).
- The actual numbers in front of the datasets in the history are not important.

### What are the results from this filtering tool?

We could click on the `eye icon` to view the contents of this output file, but it will not be very informative - we will just see a list of reads.

### > Hands-on: Get metadata about a file
1) Click on the output dataset name in the History panel.
This expands the information about the file.

```
3.4 MB
format fastqsanger database ?
Quality cut-off: 35
Minimum percentage: 80
Input: 12480 reads.
Output: 10694 reads.
discarded 1786 (14%) low-quality reads.
```
`Question:` How many read has been discarded?
`Solution:` 1786 low-quality reads were discarded

#### Filter by quality (Galaxy Version 1.0.2+galaxy0)
Tool Parameters
- Input FASTQ file *
- Quality cut-off value *
- Percent of bases in sequence that must have quality equal to / higher than cut-off value *

# Запустить другой инструмент
Давайте запустим инструмент для фильтрации некачественных чтений из нашего файла FASTQ.
### > Практика: запуск другого инструмента `Filter by quality`
1) Введите Фильтр по качеству в поле поиска панели инструментов (вверху) `Filter by quality`
2) Нажмите на инструмент Фильтр по качеству Инструмент:
`toolshed.g2.bx.psu.edu/repos/devteam/fastq_quality_filter/cshl_fastq_quality_filter/1.0.2+galaxy0`
3) Установите следующие параметры:
   - param-file «Input FASTQ file»: наш исходный набор данных FASTQ
   - «Пороговое значение качества»: 35
   - «Процент баз в последовательности, качество которых должно быть равно/выше порогового значения»: 80

4) Нажмите «Выполнить» 'Run Tool'.

После запуска инструмента его выходной набор данных появится в верхней части панели «История».

- Этот набор данных будет называться «Фильтр по качеству данных 1».
- Помните, что Galaxy назвал этот файл в соответствии с используемым инструментом («Фильтровать по качеству») и входным набором данных («данные 1»).
- Фактические числа перед наборами данных в истории не важны.

### Каковы результаты этого инструмента фильтрации?

Мы могли бы щелкнуть по значку глаза, чтобы просмотреть содержимое этого выходного файла, но это будет не очень информативно — мы просто увидим список прочтений.

### > Практическое занятие: получение метаданных о файле
1) Щелкните имя выходного набора данных на панели «История».
Это расширяет информацию о файле:
```
3.4 MB
format fastqsanger database ?
Quality cut-off: 35
Minimum percentage: 80
Input: 12480 reads.
Output: 10694 reads.
discarded 1786 (14%) low-quality reads.
```
#### Фильтр по качеству (Galaxy Version 1.0.2+galaxy0)
Параметры инструмента
- Введите файл FASTQ *
- пороговое значение качества *
- Процент баз в последовательности, качество которых должно быть равно или выше порогового значения *

# Re-run that tool with changed settings
We can now try to filter our input reads to an even higher standard, and see how this changes the resulting output (an exploratory analysis). We will change the filter settings and re-run the tool.

### > Hands-on: Re-run the tool
1) Click on the `galaxy-refresh icon` (Run this job again) for the output dataset of Filter by quality tool

This brings up the tool interface in the central panel with the parameters set to the values used previously to generate this dataset.

2) Change the settings to something even stricter

For example, you might decide you want 80 percent of bases to have a quality of 36 or higher, instead of 35.

3) Click Execute `Run Tool`
4) View the results: Click on the output dataset name to expand the information

```
963 sequences
format fastqsanger database ?
Quality cut-off: 36
Minimum percentage: 80
Input: 12480 reads.
Output: 963 reads.
discarded 11517 (92%) low-quality reads.
```

`Comment:` Not the galaxy-eye (eye) icon.

`Question:` How many reads were discarded under these new filtering conditions?

`solution:` If you selected 80% of bases with 36 as quality cut-off, then 11517 reads (92%) should have been discarded, which indicates that we have gone too far with the filtering in this case.

You can re-run a tool many times with different settings. Each time you re-run the tool, its new output datasets will appear at the top of your current history.

# Перезапуск инструмента с измененными настройками
Теперь мы можем попытаться отфильтровать наши входные чтения в соответствии с еще более высоким стандартом и посмотреть, как это изменит результирующий вывод (исследовательский анализ). Мы изменим настройки фильтра и перезапустим инструмент.

### > Практика: повторно запустите инструмент
1) Щелкните значок «обновить galaxy» (запустите это задание еще раз) для выходного набора данных инструмента «Фильтровать по качеству».

Это вызывает интерфейс инструмента на центральной панели с параметрами, установленными на значения, которые использовались ранее для создания этого набора данных.

2) Изменить настройки на что-то еще более строгое

Например, вы можете решить, что хотите, чтобы 80 процентов баз имели качество 36 или выше, а не 35.

3) Нажмите «Выполнить» «Выполнить инструмент».
4) Просмотрите результаты: щелкните имя выходного набора данных, чтобы развернуть информацию.

```
963 последовательности
отформатировать базу данных fastqsanger?
Порог качества: 36
Минимальный процент: 80
Ввод: 12480 чтений.
Вывод: 963 чтения.
отброшено 11517 (92%) некачественных чтений.
```

`Комментарий:` Не значок галактического глаза (глаза).

`Вопрос:` Сколько чтений было отброшено при этих новых условиях фильтрации?

`решение:` Если вы выбрали 80% оснований с 36 в качестве отсечки качества, то 11517 чтений (92%) должны были быть отброшены, что указывает на то, что в данном случае мы зашли слишком далеко с фильтрацией.

Вы можете повторно запускать инструмент много раз с разными настройками. Каждый раз, когда вы повторно запускаете инструмент, его новые наборы выходных данных будут появляться вверху вашей текущей истории.

# Share your history

Finally, let’s imagine that you had a problem in your analysis and you want to ask for help. The easiest way to ask for help is to share your history. Try and create a link for your history and share it with…yourself!

Sharing your history allows others to import and access the datasets, parameters, and steps of your history.

1.) Share via link
- Open the `History Options` galaxy-gear menu (gear icon) at the top of your history panel and select `Share or Publish`

> galaxy-toggle `Make History accessible`

> A `Share Link` will appear that you `give to others`

- Anybody who has this link can view and copy your history

2.) Publish your history

- galaxy-toggle Make History publicly available in Published Histories
- Anybody on this Galaxy server will see your history listed under the Shared Data menu
  
3.) Share only with another user.

- Click the `Share with a user` button at the bottom
- Enter an email address for the user you want to share with
- Your history will be shared only with this user.
  
4.) Finding histories others have shared with me

- Click on `User` menu on the top bar
- Select `Histories shared with me`
- Here you will see all the histories others have shared with you directly

`Note:` If you want to make changes to your history without affecting the shared version, make a copy by going to galaxy-gear History options icon in your history and clicking Copy

# Поделитесь своей историей

Наконец, давайте представим, что у вас возникла проблема с анализом, и вы хотите попросить о помощи. Самый простой способ попросить о помощи — поделиться своей историей. Попробуйте создать ссылку на свою историю и поделиться ею с… собой!

Совместное использование вашей истории позволяет другим импортировать и получать доступ к наборам данных, параметрам и шагам вашей истории.

1.) Поделиться по ссылке
- Откройте меню галактики «Параметры истории» (значок шестеренки) в верхней части панели истории и выберите «Поделиться или опубликовать».

> galaxy-toggle `Сделать историю доступной`

> Появится ссылка «Поделиться», которую вы «даете другим»

- Любой, у кого есть эта ссылка, может просматривать и копировать вашу историю

2.) Опубликовать свою историю

- galaxy-toggle Сделать историю общедоступной в Опубликованных историях
- Любой на этом сервере Galaxy увидит вашу историю, указанную в меню «Общие данные».
  
3.) Поделиться только с другим пользователем.

- Нажмите кнопку «Поделиться с пользователем» внизу.
- Введите адрес электронной почты пользователя, с которым вы хотите поделиться
- Ваша история будет доступна только этому пользователю.
  
4.) Поиск историй, которыми другие поделились со мной

- Нажмите на меню «Пользователь» на верхней панели.
- Выберите «Истории, которыми мне поделились».
- Здесь вы увидите все истории, которыми другие поделились с вами напрямую

`Примечание:` Если вы хотите внести изменения в свою историю, не затрагивая общую версию, сделайте копию, перейдя к значку параметров истории galaxy-gear в своей истории и нажав «Копировать».

# Convert your analysis history into a workflow

When you look carefully at your history, you can see that it contains all the steps of our analysis, from the beginning (at the bottom) to the end (on top). The history in Galaxy records details of every tool you run and preserves all parameter settings applied at each step. But when you need to analyze new data, it would be tedious to do each step one-by-one again. Wouldn’t it be nice to just convert this history into a workflow that we will be able to execute again and again?

Galaxy makes this very easy with the Extract workflow option. This means any time you want to build a workflow, you can just perform the steps once manually, and then convert it to a workflow, so that next time it will be a lot less work to do the same analysis.

`Hands-on:` Extract workflow

 1.) `Clean up` your history: remove any failed (red) jobs from your history by clicking on the galaxy-delete button.

 This will make the creation of the workflow easier.

 2.) Click on `galaxy-history-options` (History options) at the top of your history panel and select Extract workflow.

The central panel will show the content of the history in reverse order (oldest on top), and you will be able to choose which steps to include in the workflow.

3.) Replace the `Workflow name` to something more descriptive, for example: `QC and filtering.`

4.) `Rename` the workflow input in the box at the top of second column to: `FASTQ reads`

5.) If there are any steps that shouldn’t be included in the workflow, you can `uncheck` them in the first column of boxes. In this case, uncheck the second `Filter by quality` tool at the bottom, where we used a too high quality cut-off.

6.) Click on the Create Workflow button near the top.

You will get a message that the workflow was created.

In a minute we will see how to find the extracted workflow and how to use it.

# Превратите историю анализа в рабочий процесс

Если вы внимательно посмотрите на свою историю, то увидите, что она содержит все этапы нашего анализа, от начала (внизу) до конца (вверху). История в Galaxy записывает сведения о каждом запущенном вами инструменте и сохраняет все настройки параметров, применяемые на каждом этапе. Но когда вам нужно проанализировать новые данные, было бы утомительно повторять каждый шаг один за другим. Было бы неплохо просто преобразовать эту историю в рабочий процесс, который мы сможем выполнять снова и снова?

Galaxy делает это очень легко с опцией рабочего процесса Extract. Это означает, что каждый раз, когда вы хотите создать рабочий процесс, вы можете просто выполнить шаги один раз вручную, а затем преобразовать его в рабочий процесс, чтобы в следующий раз выполнить тот же анализ было намного меньше работы.

`Практика:` Рабочий процесс извлечения

 1.) «Очистите» свою историю: удалите все неудачные (красные) задания из своей истории, нажав на кнопку галактики-удалить.

 Это облегчит создание рабочего процесса.

 2.) Нажмите «galaxy-history-options» (Параметры истории) в верхней части панели истории и выберите «Извлечь рабочий процесс».

На центральной панели содержимое истории будет отображаться в обратном порядке (самые старые вверху), и вы сможете выбрать, какие шаги включить в рабочий процесс.

3.) Замените «Имя рабочего процесса» на что-то более описательное, например: «Контроль качества и фильтрация».

4.) «Переименуйте» ввод рабочего процесса в поле в верхней части второго столбца на: «FASTQ читает».

5.) Если есть какие-либо шаги, которые не должны быть включены в рабочий процесс, вы можете «снять» их в первом столбце полей. В этом случае снимите второй флажок «Фильтровать по качеству» внизу, где мы использовали слишком высокое качество отсечки.

6.) Нажмите кнопку «Создать рабочий процесс» вверху.

Вы получите сообщение о том, что рабочий процесс создан.

Через минуту мы увидим, как найти извлеченный рабочий процесс и как его использовать.

# Create a new history

Let’s create a new history.

`Hands-on:` New history

1.) Create a new history
- Click `+` the `new-history icon` at the top of the history panel.

If `+` the new-history is missing:

- Click on the `galaxy-gear icon` (History options) on the top of the history panel
- Select the option `Create New`  from the menu

2.) Rename your history, e.g. “Next Analysis”

- Click on `galaxy-pencil (Edit)` next to the history name (which by default is “Unnamed history”)
- Type the new name
- Click on `Save`

If you do not have the `galaxy-pencil (Edit)` next to the history name:

1) Click on `Unnamed history `(or the current name of the history) (Click to rename history) at the top of your history panel
2) Type the new name
3) Press `Enter`

This new history does not have any datasets in it yet.

# Создать новую историю

Создадим новую историю.

`Практика:` Новая история

1.) Создать новую историю
- Нажмите «+» на «значке новой истории» в верхней части панели истории.

Если `+` новая история отсутствует:

- Нажмите на значок «галактика-шестеренка» (параметры истории) в верхней части панели истории.
- Выберите в меню пункт «Создать новый».

2.) Переименуйте свою историю, например. «Следующий анализ»

- Нажмите «галактика-карандаш (Редактировать)» рядом с названием истории (которое по умолчанию «Безымянная история»)
- Введите новое имя
- Нажмите «Сохранить».

Если у вас нет «галактики-карандаша (редактировать)» рядом с названием истории:

1) Нажмите «Безымянная история» (или текущее название истории) (Нажмите, чтобы переименовать историю) в верхней части панели истории.
2) Введите новое имя
3) Нажмите «Ввод».

В этой новой истории еще нет наборов данных.

# Look at all your histories

Where is your first history, called “My Analysis”?

`Hands-on:` View histories

1) Click on `galaxy-history-options` (History options) and then click on the `galaxy-columns Show Histories side-by-side`

A new page will appear with all your histories displayed here.

2) Copy a dataset into your new history

- Click on the FASTQ dataset in “My Analysis” history
- Drag it into the “Next Analysis” history
        
This makes a copy of the dataset in the new history (without actually using additional disk space).

3) Click on the `Home icon` galaxy-home (or Analyze Data on older versions of Galaxy) in the top panel to go back to your analysis window

Your main Galaxy window will now show “Next Analysis” as the current history, and it will have one dataset in it.

At any time, you can go back into the “View all histories” page and “Switch to” a different history.

# Посмотрите на все свои истории

Где находится ваша первая история под названием «Мой анализ»?

`Практика:` Просмотр истории

1) Нажмите на galaxy-history-options (Параметры истории), а затем нажмите на столбцы галактик Показать истории бок о бок

Появится новая страница со всеми вашими историями, отображаемыми здесь.

2) Скопируйте набор данных в новую историю

- Нажмите на набор данных FASTQ в истории «Мой анализ».
- Перетащите его в историю «Следующий анализ»
        
Это создает копию набора данных в новой истории (фактически без использования дополнительного дискового пространства).

3) Нажмите значок «Главная» galaxy-home (или «Анализ данных» в более старых версиях Galaxy) на верхней панели, чтобы вернуться в окно анализа.

Ваше главное окно Galaxy теперь будет отображать «Следующий анализ» как текущую историю, и в нем будет один набор данных.

В любой момент вы можете вернуться на страницу «Просмотреть все истории» и «Переключиться» на другую историю.

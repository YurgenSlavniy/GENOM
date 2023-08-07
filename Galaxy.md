#  Galaxy Training! 
### GTN Learning Pathway:

We recommend you follow the tutorials in the order presented on this page. They have been selected to fit together and build up your knowledge step by step. If a lesson has both slides and a tutorial, we recommend you start with the slides, then proceed with the tutorial. 

### Introduction to Galaxy and Sequence analysis

This learning path aims to teach you the basics of Galaxy and analysis of sequencing data. You will learn how to use Galaxy for analysis, and will be guided through the most common first steps of any genome analysis; quality control and a mapping or assembly of your genomic sequences.

New to Galaxy and/or the field of genomics? Follow this learning path to get familiar with the basics!
______________________________________________________________________
# Обучение Galaxy!
### Схема обучения GTN:

Мы рекомендуем вам следовать инструкциям в порядке, представленном на этой странице. Они были выбраны так, чтобы соответствовать друг другу и шаг за шагом накапливать ваши знания. Если в уроке есть и слайды, и учебное пособие, мы рекомендуем начать со слайдов, а затем перейти к учебному пособию.

### Введение в Galaxy и анализ последовательностей

Этот путь обучения направлен на то, чтобы научить вас основам Galaxy и анализу данных секвенирования. Вы узнаете, как использовать Galaxy для анализа, и пройдете через наиболее распространенные первые шаги любого анализа генома; контроль качества и картирование или сборка ваших геномных последовательностей.

______________________________________________________________________
# Module 1: Introduction to Galaxy
Get a first look at the Galaxy platform for data analysis. We start with a short introduction (video slides & practical) to familiarize you with the Galaxy interface, and then proceed with a slightly longer introduction tutorials where you perform a first, very simple, analysis.
______________________________________________________________________
# МОДУЛЬ 1: Введение в Galaxy
Получите первый взгляд на платформу Galaxy для анализа данных. Мы начнем с краткого введения (видео слайды и практические занятия), чтобы познакомить вас с интерфейсом Galaxy, а затем перейдем к более длинным вводным учебным пособиям, в которых вы выполните первый, очень простой анализ.
______________________________________________________________________

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
______________________________________________________________________
# Обзор
Это краткое введение в пользовательский интерфейс Galaxy.
Мы рассмотрим ключевые задачи в Galaxy: 
- загрузку файлов,
- использование инструментов,
- просмотр истории 
- выполнение рабочих процессов.
______________________________________________________________________
# Overview
- This is a short introduction to the Galaxy user interface - the web page that you interact with.
- We will cover key tasks in Galaxy: uploading files, using tools, viewing histories, and running workflows.
______________________________________________________________________
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
______________________________________________________________________
# What does Galaxy look like?
### > Hands-on: Log in to Galaxy

1) Open your favorite browser (Chrome, Safari or Firefox as your browser, not Internet Explorer!)
2) Browse to your Galaxy instance
3) Log in or register
______________________________________________________________________
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
______________________________________________________________________
# Homepage
The Galaxy homepage is divided into three panels:
- Tools on the left
- Viewing panel in the middle
- History of analysis and files on the right

The first time you use Galaxy, there will be no files in your history panel.
______________________________________________________________________
# Домашняя стартовая страница https://usegalaxy.org/
Стартовая страница Galaxy состоит из трёх панелей:
- `Tools`  Левая панель - `инструменты`
- `Viewing`  Центральная панель - `представления`
- `History of analysis`  Правая панель - `История анализа`
 
При первом использовании Galaxy на панели истории не будет файлов.
______________________________________________________________________
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
______________________________________________________________________

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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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

______________________________________________________________________
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
______________________________________________________________________
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

______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
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
______________________________________________________________________
# Run workflow in the new history

Now that we have built our workflow, let’s use it to re-create our small analysis in a single step. The same workflow could also be used on some new FASTQ data to quickly repeat the same analysis on different inputs.

`Hands-on:` Run workflow

1) Click on `Workflow` in the top menu bar of Galaxy.

Here you have a list of all your workflows. Your newly created workflow should be listed at the top:

If you click on a workflow name, you can see all available actions for the workflow, e.g. edit, copy, rename, delete.

2) Click on the `workflow-run` (Run workflow) button next to your workflow.

The central panel will change to allow you to configure and launch the workflow.

3) Check that the “FASTQ reads” input is set to the FASTQ dataset we have copied to the new history.

In this page we could change any parameter for the tools composing the workflow as we would do when running them one by one.

4) Click the `Run Workflow` button at the top-right of the screen.

You should see a message that the workflow was successfully invoked. Then jobs will start to run and datasets appear in your “Next Analysis” history, replicating the steps of your previous history.

### Conclusion

Well done! You have completed the short introduction to Galaxy, 

- where you named the history,
- uploaded a file,
- used a tool,
- viewed results and
- run a workflow.

Additional tutorials are available for a more in-depth introduction to Galaxy’s features.
______________________________________________________________________
# Запустить рабочий процесс в новой истории

Теперь, когда мы построили наш рабочий процесс, давайте воспользуемся им, чтобы воссоздать наш небольшой анализ за один шаг. Тот же рабочий процесс можно также использовать для некоторых новых данных FASTQ, чтобы быстро повторить тот же анализ для разных входных данных.

`Практика:` Запуск рабочего процесса

1) Нажмите «Рабочий процесс» в верхней строке меню Galaxy.

Здесь у вас есть список всех ваших рабочих процессов. Ваш вновь созданный рабочий процесс должен быть указан вверху:

Если вы нажмете имя рабочего процесса, вы увидите все доступные действия для рабочего процесса, например. редактировать, копировать, переименовывать, удалять.

2) Нажмите на кнопку `workflow-run` (Запустить рабочий процесс) рядом с вашим рабочим процессом.

Центральная панель изменится, чтобы вы могли настроить и запустить рабочий процесс.

3) Убедитесь, что вход «Чтения FASTQ» настроен на набор данных FASTQ, который мы скопировали в новую историю.

На этой странице мы могли изменить любой параметр для инструментов, составляющих рабочий процесс, как если бы мы запускали их один за другим.

4) Нажмите кнопку «Запустить рабочий процесс» в правом верхнем углу экрана.

Вы должны увидеть сообщение об успешном вызове рабочего процесса. Затем начнут выполняться задания, и наборы данных появятся в вашей истории «Следующий анализ», повторяя шаги вашей предыдущей истории.

### Заключение

Отличная работа! Вы завершили краткое введение в Galaxy, 
- где назвали историю,
- загрузили файл,
- использовали инструмент,
- просмотрели результаты и
- запустили рабочий процесс.
______________________________________________________________________
Доступны дополнительные руководства для более глубокого ознакомления с функциями Galaxy.

# Key Points:

- The Galaxy interface has tools on the left, viewing pane in the middle, and a history of your data analysis on the right.
- You can create a new history for each analysis. All your histories are saved.
- To get data into Galaxy, you can upload a file by pasting in a web address. There are other ways to get data into Galaxy (not covered in this tutorial): you can upload a file from your computer, and you can import an entire history.
- Choose a tool and change any settings for your analysis.
- Run the tool. The output files will be saved at the top of your history.
- View the output files by clicking on the eye icon.
- View all your histories and move files between them. Switch to a different history.
- Log out of your Galaxy server. When you log back in (to the same server), your histories will all be there.

### Frequently Asked Questions
Have questions about this tutorial? Check out the tutorial FAQ page or the FAQ page for the Introduction to Galaxy Analyses topic to see if your question is listed there. If not, please ask your question on the GTN Gitter Channel or the Galaxy Help Forum

### Feedback
Did you use this material as an instructor? Feel free to give us feedback on how it went.
Did you use this material as a learner or student? Click the form below to leave feedback. 
______________________________________________________________________
# Ключевые моменты:

- В интерфейсе Galaxy инструменты слева, панель просмотра посередине и история анализа ваших данных справа.
- Вы можете создать новую историю для каждого анализа. Все ваши истории сохранены.
- Чтобы получить данные в Galaxy, вы можете загрузить файл, вставив веб-адрес. Есть и другие способы загрузки данных в Galaxy (не рассмотренные в этом руководстве): вы можете загрузить файл со своего компьютера или импортировать всю историю.
- Выберите инструмент и измените любые настройки для вашего анализа.
- Запустите инструмент. Выходные файлы будут сохранены в верхней части вашей истории.
- Просмотрите выходные файлы, нажав на значок глаза.
- Просматривайте все свои истории и перемещайте файлы между ними. Переключиться на другую историю.
- Выйдите из своего сервера Galaxy. Когда вы снова войдете в систему (на тот же сервер), все ваши истории будут там.

### Часто задаваемые вопросы
Есть вопросы по этому уроку? Посетите страницу часто задаваемых вопросов по учебнику или страницу часто задаваемых вопросов для темы Introduction to Galaxy Analyses, чтобы узнать, есть ли там ваш вопрос. Если нет, задайте свой вопрос на канале GTN Gitter или на справочном форуме Galaxy.

### Обратная связь
Вы использовали этот материал в качестве преподавателя? Не стесняйтесь оставлять нам отзывы о том, как все прошло.
Вы использовали этот материал в качестве ученика или ученика? Нажмите на форму ниже, чтобы оставить отзыв.

______________________________________________________________________
# BibTeX
```
@misc{introduction-galaxy-intro-short,
author = "Anna Syme and Nicola Soranzo",
	title = "A short introduction to Galaxy (Galaxy Training Materials)",
	year = "",
	month = "",
	day = ""
	url = "\url{https://training.galaxyproject.org/training-material/topics/introduction/tutorials/galaxy-intro-short/tutorial.html}",
	note = "[Online; accessed Mon Jul 31 2023]"
}
@article{Hiltemann_2023,
	doi = {10.1371/journal.pcbi.1010752},
	url = {https://doi.org/10.1371%2Fjournal.pcbi.1010752},
	year = 2023,
	month = {jan},
	publisher = {Public Library of Science ({PLoS})},
	volume = {19},
	number = {1},
	pages = {e1010752},
	author = {Saskia Hiltemann and Helena Rasche and Simon Gladman and Hans-Rudolf Hotz and Delphine Larivi{\`{e}}re and Daniel Blankenberg and Pratik D. Jagtap and Thomas Wollmann and Anthony Bretaudeau and Nadia Gou{\'{e}} and Timothy J. Griffin and Coline Royaux and Yvan Le Bras and Subina Mehta and Anna Syme and Frederik Coppens and Bert Droesbeke and Nicola Soranzo and Wendi Bacon and Fotis Psomopoulos and Crist{\'{o}}bal Gallardo-Alba and John Davis and Melanie Christine Föll and Matthias Fahrner and Maria A. Doyle and Beatriz Serrano-Solano and Anne Claire Fouilloux and Peter van Heusden and Wolfgang Maier and Dave Clements and Florian Heyl and Björn Grüning and B{\'{e}}r{\'{e}}nice Batut and},
	editor = {Francis Ouellette},
	title = {Galaxy Training: A powerful framework for teaching!},
	journal = {PLoS Comput Biol} Computational Biology}
}

```
______________________________________________________________________
### Galaxy Administrators: Install the missing tools

You can use Ephemeris's `shed-tools install` command to install the tools used in this tutorial.

> shed-tools install [-g GALAXY] [-a API_KEY] -t <(curl https://training.galaxyproject.org/training-material/api/topics/introduction/tutorials/galaxy-intro-short/tutorial.json | jq .admin_install_yaml -r)

Alternatively you can copy and paste the following YAML
```
---
install_tool_dependencies: true
install_repository_dependencies: true
install_resolver_dependencies: true
tools:
- name: fastq_quality_filter
  owner: devteam
  revisions: 43a7370aa010
  tool_panel_section_label: Introduction to Galaxy Analyses
  tool_shed_url: https://toolshed.g2.bx.psu.edu/
- name: fastq_quality_filter
  owner: devteam
  revisions: ce9cd02d5b88
  tool_panel_section_label: Introduction to Galaxy Analyses
  tool_shed_url: https://toolshed.g2.bx.psu.edu/
- name: fastqc
  owner: devteam
  revisions: 9da02be9c6cc
  tool_panel_section_label: Introduction to Galaxy Analyses
  tool_shed_url: https://toolshed.g2.bx.psu.edu/
- name: fastqc
  owner: devteam
  revisions: 3d0c7bdf12f5
  tool_panel_section_label: Introduction to Galaxy Analyses
  tool_shed_url: https://toolshed.g2.bx.psu.edu/
```
______________________________________________________________________
# Galaxy 101
Authors:
- Saskia Hiltemann
- Nicola Soranzo
- Clemens Blank
- Nekrutenko
- Björn Grüning
- Anne Pajon
- Helena Rasche
______________________________________________________________________
# Overview

`Questions:` Which coding exon has the highest number of single nucleotide polymorphisms (SNPs) on human chromosome 22?

`Objectives:`

- Familiarize yourself with the basics of Galaxy
- Learn how to obtain data from external sources
- Learn how to run tools
- Learn how histories work
- Learn how to create a workflow
- Learn how to share your work

`Time estimation:` 1 hour

`Level:` Introductory Introductory - 

`Supporting Materials:`

- https://zenodo.org/record/4104428
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/workflows/
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/faqs/
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html#
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html#

`Last modification:` May 16, 2023

`License: Tutorial Content` is licensed under Creative Commons Attribution 4.0 International License. The GTN Framework is licensed under MIT 
______________________________________________________________________
# Обзор

`Вопросы:` Какой кодирующий экзон имеет наибольшее количество однонуклеотидных полиморфизмов (SNP) на хромосоме 22 человека?

`Цели:`

- Ознакомьтесь с основами Galaxy
- Научитесь получать данные из внешних источников
- Научитесь запускать инструменты
- Узнайте, как работают истории
- Научитесь создавать рабочий процесс
- Узнайте, как поделиться своей работой

`Оценка времени:` 1 час

`Уровень:` Вводный Вводный -

`Вспомогательные материалы:`

- https://zenodo.org/record/4104428
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/workflows/
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/faqs/
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html#
- https://usegalaxy.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html#

`Последняя модификация:` 16 мая 2023 г.

«Лицензия: Учебное содержание» находится под лицензией Creative Commons Attribution 4.0 International License. GTN Framework находится под лицензией MIT.
______________________________________________________________________

# Introduction

This tutorial aims to familiarize you with the Galaxy user interface. It will teach you how to perform basic tasks such as importing data, running tools, working with histories, creating workflows, and sharing your work.

`Comment:` Results may vary

Your results may be slightly different from the ones presented in this tutorial due to differing versions of tools, reference data, external databases, or because of stochastic processes in the algorithms.

______________________________________________________________________
# Введение

Это руководство предназначено для того, чтобы познакомить вас с пользовательским интерфейсом Galaxy. Он научит вас выполнять основные задачи, такие как импорт данных, запуск инструментов, работа с историями, создание рабочих процессов и совместное использование вашей работы.

`Комментарий:` Результаты могут отличаться

Ваши результаты могут немного отличаться от представленных в этом руководстве из-за разных версий инструментов, справочных данных, внешних баз данных или из-за стохастических процессов в алгоритмах.
______________________________________________________________________
# Agenda

In this tutorial, we will:

1) Introduction
2) Setting the stage: Exons and SNPs
- 2.1) Locating Exons
3) Analysis
- 3.1) Find exons with the most SNPs
- 3.2) Count the number of SNPs per exon
- 3.3) Sort the exons by SNPs count
- 3.4) Select the top five exons
- 3.5) Recovering exon info
- 3.6) Displaying data in UCSC genome browser
4) Galaxy management
- 4.1) Convert your analysis history into a workflow
- 4.2) The workflow editor
- 4.3) Run workflow on different data
- 4.4) Share your work
5) Conclusion
______________________________________________________________________
# Повестка дня

В этом уроке мы будем:

1. Введение
2) Подготовка к сцене: экзоны и SNP
- 2.1) Расположение экзонов
3) Анализ
- 3.1) Найдите экзоны с наибольшим количеством SNP
- 3.2) Подсчитайте количество SNP на экзон
- 3.3) Сортировка экзонов по количеству SNP
- 3.4) Выберите пять верхних экзонов
- 3.5) Восстановление информации об экзоне
- 3.6) Отображение данных в браузере генома UCSC
4) Управление Galaxy
- 4.1) Преобразуйте историю анализа в рабочий процесс
- 4.2) Редактор рабочего процесса
- 4.3) Запуск рабочего процесса на разных данных
- 4.4) Поделитесь своей работой
5. Вывод
______________________________________________________________________

# Setting the stage: Exons and SNPs

`We start with the question:` In human chromosome 22, which exon has the highest number of single nucleotide polymorphisms (SNPs)?

`Comment:` Background

Not everyone has the same background and that’s ok! You may have studied different organisms with different gene models, or you may not be familiar with the biological aspect at all. The biological background is not necessary for following this tutorial, we just like to provide research context for any tutorial. Here are brief explanations of some of the concepts mentioned in this tutorial:

- **Nucleotides** are the A, C, T, and Gs that make up DNA.
- **Chromosomes** can be thought of as a very long piece of DNA (string of A, C, T, Gs) Some organisms have chromosomes, in this tutorial we will use Human chromosome number 22.
- **Features** are regions of the chromosome that are interesting for one reason or another. Some examples of features include genes, terminators, transcription start sites, and repeat regions.
- **Genes** are one kind of interesting feature, a region that will be transcribed into RNA before being translated into proteins.
- **Exons** are fundamental components of eukaryotic genes. A typical eukaryotic gene contains numerous exons separated by introns. An entire gene containing both exons and introns is transcribed into a pre-messenger RNA or pre-mRNA. During maturation introns are excised from the pre-mRNA in a process called splicing. A mature messenger RNA, or simply mRNA, is then translated into protein during the process of translation.
```
DNA -> 1Exon - intron - 2Exon - intron - 3Exon - intron (spiral)
RNA -> 1Exon - intron - 2Exon - intron - 3Exon - intron (one line)
mRNA -> 1Exon_spectrum - 2Exon_spectrum - 3Exon_spectrum (one line)

```
`Figure 1:` An original piece of DNA containing introns and exons has the introns cut out before the exons are joined together to form the mRNA. (Image from WikiMedia, under the Public Domain)

SNP is an abbreviation for single-nucleotide polymorphism. It is pronounced as “snip”. SNPs are single nucleotide differences between a sequenced individual compared to some reference sequence; where one individual might have an A, another could have a C in that position. Databases of SNPs have been created for many organisms and they include any single nucleotide deviation from the reference sequence which appears in some percentage of the population (e.g. >1%). These are often especially interesting to geneticists as the causes of certain inheritable diseases.

You may be familiar with the UCSC Genome Browser https://genome.ucsc.edu/ or another resource like it, and know that you can find the data there. But even with your data in hand, you still have the question: “how do I actually compute this?” There is really a straightforward answer: Galaxy. So let’s try it…

Browse to your favorite Galaxy instance and log in or register.

______________________________________________________________________

# Подготовка к этапу: экзоны и SNP

`Начнем с вопроса:` какой экзон хромосомы 22 человека имеет наибольшее количество однонуклеотидных полиморфизмов (SNP)?

`Комментарий:` Бэкграунд - прошлый опыт. 

Не у всех одинаковый опыт и бэкграунд, и это нормально! Возможно, вы изучали разные организмы с разными моделями генов или вообще не знакомы с биологическим аспектом. Биологический бэкграунд не обязателен для изучения этого урока, нам просто нравится предоставлять исследовательский контекст для любого урока. Вот краткие пояснения некоторых концепций, упомянутых в этом руководстве:

- **Нуклеотиды** — это A, C, T и G, из которых состоит ДНК.
- **Хромосомы** можно рассматривать как очень длинный фрагмент ДНК (цепочка A, C, T, G). У некоторых организмов есть хромосомы, в этом уроке мы будем использовать хромосому человека номер 22.
- **Особенности** — это участки хромосомы, представляющие интерес по той или иной причине. Некоторые примеры признаков включают гены, терминаторы, сайты начала транскрипции и области повторов.
- **Гены** — это одна из интересных особенностей, область, которая будет транскрибироваться в РНК, прежде чем транслироваться в белки.
- **Экзоны** являются фундаментальными компонентами эукариотических генов. Типичный эукариотический ген содержит множество экзонов, разделенных интронами. Целый ген, содержащий как экзоны, так и интроны, транскрибируется в пре-мессенджерную РНК или пре-мРНК. Во время созревания интроны вырезаются из пре-мРНК в процессе, называемом сплайсингом. Затем в процессе трансляции зрелая информационная РНК или просто мРНК транслируется в белок.
```
DNA -> 1Exon - intron - 2Exon - intron - 3Exon - intron (spiral)
RNA -> 1Exon - intron - 2Exon - intron - 3Exon - intron (one line)
mRNA -> 1Exon_spectrum - 2Exon_spectrum - 3Exon_spectrum (one line)

```
`Рисунок 1:` В исходном фрагменте ДНК, содержащем интроны и экзоны, интроны вырезаются до того, как экзоны соединяются вместе, образуя мРНК. (Изображение из WikiMedia, находящееся в общественном достоянии)

SNP является аббревиатурой однонуклеотидного полиморфизма. Произносится как «снип». SNP представляют собой различия в отдельных нуклеотидах между секвенированным индивидуумом по сравнению с некоторой эталонной последовательностью; где у одного человека может быть A, у другого может быть C в этой позиции. Базы данных SNP были созданы для многих организмов, и они включают любое отклонение одного нуклеотида от эталонной последовательности, которое встречается в некотором проценте популяции (например, > 1%). Часто они представляют особый интерес для генетиков как причины некоторых наследственных заболеваний.

Возможно, вы знакомы с UCSC Genome Browser https://genome.ucsc.edu/ или другим подобным ресурсом и знаете, что можете найти там данные. Но даже с вашими данными у вас все еще есть вопрос: «Как я могу это вычислить?» На самом деле есть простой ответ: *Galaxy*. Итак, давайте попробуем…

Перейдите к своему любимому экземпляру Galaxy и войдите в систему или зарегистрируйтесь.

______________________________________________________________________
# How do I create an account on a public Galaxy instance?

1) To create an account at any public Galaxy instance, choose your server from the available list of Galaxy Platforms.
There are 3 main public Galaxy servers:

- UseGalaxy.org, 
- UseGalaxy.eu, 
- UseGalaxy.org.au.

2) Click on “Login or Register” in the masthead on the server.
3) On the login page, find the Register here link and click on it.
4) Fill in the the registration form, then click on Create.
  
Your account should now get created, but will remain inactive until you verify the email address you provided in the registration form.

5) Check for a Confirmation Email in the email you used for account creation.
6) Click on the Email confirmation link to fully activate your account.

galaxy-info Delivery of the confimation email is blocked by your email provider or you mistyped the email address in the registration form?

Please do not register again, but follow the instructions to change the email address registered with your account! The confirmation email will be resent to your new address once you have changed it.
______________________________________________________________________
# Как создать учетную запись в общедоступном экземпляре Galaxy?

1) Чтобы создать учетную запись в любом общедоступном экземпляре Galaxy, выберите свой сервер из доступного списка платформ Galaxy.
Есть 3 основных общедоступных сервера Galaxy:

- Используйте Galaxy.org,
- Используйте Galaxy.eu,
- Используйте Galaxy.org.au.

2) Нажмите «Войти или зарегистрироваться» в шапке на сервере.
3) На странице входа найдите ссылку «Регистрация здесь» и нажмите на нее.
4) Заполните регистрационную форму, затем нажмите «Создать».
  
Теперь ваша учетная запись должна быть создана, но она останется неактивной, пока вы не подтвердите адрес электронной почты, указанный в регистрационной форме.

5) Проверьте наличие письма с подтверждением в электронном письме, которое вы использовали для создания учетной записи.
6) Нажмите на ссылку подтверждения по электронной почте, чтобы полностью активировать свою учетную запись.

galaxy-info Доставка электронного письма с подтверждением заблокирована вашим провайдером электронной почты или вы неправильно указали адрес электронной почты в регистрационной форме?

Пожалуйста, не регистрируйтесь снова, а следуйте инструкциям по изменению адреса электронной почты, зарегистрированного в вашей учетной записи! Письмо с подтверждением будет повторно отправлено на ваш новый адрес, как только вы его измените.  
______________________________________________________________________
The `Galaxy interface` consists of three main parts:

- The available Tools are listed on the left
- The Central Panel will let you run analyses and view outputs
- Your analysis History is recorded on the right

Galactic triptych: the three panels of Galaxy interface: Tools, Center Panel, and History

When you start Galaxy for very first time, your history will be empty. Let’s add some data to it.
______________________________________________________________________
«Интерфейс Galaxy» состоит из трех основных частей:

- Доступные инструменты перечислены слева
- Центральная панель позволит вам запускать анализы и просматривать результаты
- История вашего анализа записывается справа

Галактический триптих: три панели интерфейса Galaxy: инструменты, центральная панель и история.

Когда вы запускаете Galaxy в первый раз, ваша история будет пустой. Добавим к нему некоторые данные.
______________________________________________________________________
`Hands-on:` Create history

Make sure you start from an empty analysis history.

`Creating a new` history:

1) Click '+' the new-history icon at the top of the history panel.

If the '+' new-history is missing:
- Click on the galaxy-gear icon (History options) on the top of the history panel
- Select the option Create New from the menu

2) `Rename` your history to be meaningful and easy to find. You can do this by clicking on the title of the history (which by default is Unnamed history) and typing Galaxy 101 as the name. Do not forget to hit the Enter key on your keyboard to save it.
______________________________________________________________________
`Практика:` Создание истории

Убедитесь, что вы начинаете с пустой истории анализа.

`Создание новой` истории:

1) Нажмите «+» на значок новой истории в верхней части панели истории.

Если новая история «+» отсутствует:
- Нажмите на значок шестеренки галактики (параметры истории) в верхней части панели истории.
- Выберите опцию «Создать новый» в меню.

2) «Переименуйте» свою историю, чтобы она была осмысленной и ее было легко найти. Вы можете сделать это, щелкнув заголовок истории (по умолчанию это Безымянная история) и введя Galaxy 101 в качестве имени. Не забудьте нажать клавишу Enter на клавиатуре, чтобы сохранить его.
______________________________________________________________________
# Locating Exons

First we need to get some data into our history. You can upload files from your computer, or Galaxy can also fetch data directly from external sources. We know UCSC has exon locations for humans and we can use Galaxy to import the data for chromosome 22, directly from the UCSC table browser.

`Hands-on:` Upload SNPs and Exons

1) At the top of the `Tools panel` (on the left), click galaxy-upload `Upload Data`
This brings up a box:

2) Click `Paste/Fetch` data and paste in the following URLs in the box that appears.

- https://zenodo.org/record/4104428/files/UCSC-hg38-chr22-Coding-Exons.bed
- https://zenodo.org/record/4104428/files/UCSC-hg38-chr22-dbSNP153-Whole-Gene-SNPs.bed

3) Click `Start`, and then `Close`

4) When they are ready, `rename` galaxy-pencil the datasets to Exons and SNPs, respectively.

***renaming dataset***
- Click on the galaxy-pencil pencil icon for the dataset to edit its attributes
- In the central panel, change the Name field
- Click the Save button

For this tutorial, we made the input datasets available on Zenodo for you. However, these datasets can also obtained directly from UCSC, without leaving Galaxy. Below we describe how you can do this, but it is not necessary for this tutorial. Note that since the data in UCSC is updated frequently, you might get slightly different results in the rest of this tutorial if you use these files.

`Comment:` In order to get the datasets from the UCSC server, you need to have an account in an instance.
______________________________________________________________________
# Обнаружение экзонов

Сначала нам нужно получить некоторые данные в нашу историю. Вы можете загружать файлы со своего компьютера, или Galaxy также может получать данные напрямую из внешних источников. Мы знаем, что в UCSC есть расположение экзонов для человека, и мы можем использовать Galaxy для импорта данных для хромосомы 22 непосредственно из браузера таблиц UCSC.

Практические занятия: загрузка SNP и экзонов

1) В верхней части панели «Инструменты» (слева) нажмите galaxy-upload «Загрузить данные».
Это вызывает окно.

2) Нажмите «Вставить/выбрать» данные и вставьте следующие URL-адреса в появившееся поле.

- https://zenodo.org/record/4104428/files/UCSC-hg38-chr22-Coding-Exons.bed
- https://zenodo.org/record/4104428/files/UCSC-hg38-chr22-dbSNP153-Whole-Gene-SNPs.bed

3) Нажмите «Пуск», а затем «Закрыть».

4) Когда они будут готовы, «переименуйте» в Exons и SNP соответственно.

***переименование набора данных***
- Нажмите на значок карандаша для набора данных, чтобы изменить его атрибуты.
- В центральной панели изменить поле Имя
- Нажмите кнопку Сохранить

Для этого руководства мы сделали наборы входных данных доступными для вас в Zenodo. Однако эти наборы данных также можно получить напрямую из UCSC, не покидая Galaxy. Ниже мы опишем, как вы можете это сделать, но это не обязательно для этого урока. Обратите внимание, что, поскольку данные в UCSC часто обновляются, вы можете получить немного другие результаты в оставшейся части этого руководства, если будете использовать эти файлы.

`Комментарий:` Чтобы получить наборы данных с сервера UCSC, вам необходимо иметь учетную запись в экземпляре.
______________________________________________________________________

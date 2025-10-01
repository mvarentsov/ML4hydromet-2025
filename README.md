# ML4hydromet-2025

Курс "Машинное обучение в гидрометеорологии" для магистров I года обучения географического факультета МГУ имени М.В. Ломоносова.   

Читают **Михаил Варенцов** ([ИСТИНА](https://istina.msu.ru/workers-beta/10689047/), [ResearchGate](https://www.researchgate.net/profile/Mikhail-Varentsov-2)) и **Михаил Криницкий** ([персональная страница](https://sail.ocean.ru/staff/mikhail-krinitskiy), [ResearchGate](https://www.researchgate.net/profile/Mikhail-Krinitskiy)).

Предыдущая версия курса [ML4hydromet-2024](https://github.com/mvarentsov/ML4hydromet-2024#)

## Материалы по курсу

| Название | Дата | Тема | Материалы |
| ----- | ---- | ----- | ------- |

## Домашние работы
Все работы следует оформлять в виде файлов Jupiter Notebook, включающих исходный код, результаты (графики, таблицы и пр.) и текстовые пояснения в формате Markdown.
Выполненные работы следует присылать на почту ml4hydromet@ml4es.ru. 

| Название | Срок сдачи | Материалы |
| ----- | ---- | ----- |
*бонусное задание не входит в базовую формулу оценивания, но обеспечивает дополнительные бонусные баллы в случае выполнения

## Готовые коллекции данных для выполнения практических работ

| Название и ссылка| Предметная область | Куратор | Описание возможных задач|
| ----- | ---- | ----- |----- | 
| [DASIO (All-Sky Imagery over the Ocean)](https://github.com/mvarentsov/ML4hydromet-2025/blob/main/DASIO-dataset-description.md) |Атмосферная радиация и облачность| Михаил Криницкий| Аппроксимация радиационных потоков на основе фотоснимков небесной полусферы
| [DISO3 (In-Situ Observations over the Ocean)](https://github.com/mvarentsov/ML4hydromet-2025/blob/main/DISO3-dataset-description.md) |Приводный слой атмосферы|  Михаил Криницкий| Анализ взаимосвязей между метеовеличинами
| [DDM (Discharge and Meteorology)](https://github.com/mvarentsov/ML4hydromet-2025/blob/main/DDM-dataset-description.md)|Гидрология| Михаил Варенцов|Аппроксимация и прогноз расхода воды в реке на основе осредненных по водосбору характеристиках метеорологического режима по данным реанализа
| [DUHI (Urban Heat Island)](https://github.com/mvarentsov/ML4hydromet-2025/blob/main/DUHI-dataset-description.md)|Городская метеорология|Михаил Варенцов|Аппроксимация и прогноз интенсивости городского острова тепла - разности температуры между городом и фоновым ландшафтом|
| [DCIPP (Convective Intensive Precipitation Predictors)](https://github.com/mvarentsov/ML4hydromet-2025/edit/main/DCIPP_dataset-description.md)|Метеорология|Юлия Ярынич (julia.yarinich@yandex.ru)|Оценка рисков возникновения опасных явлений, связанных с глубокой конвекцией|

## Полезные ссылки
- Канал StatQuest про статистику и ML (на английском): [YouTube](https://www.youtube.com/@statquest), [сайт](https://statquest.org)

## Рекомендуемая литература

-	*Мэрфи К.П.* Вероятностное машинное обучение. Введение. М.: ДМК Пресс, 2022. 990 с.
  - англоязычный вариант (оригинал, доступен бесплатно): [Murphy K.P. Probabilistic machine learning: an introduction. Cambridge, Massachusetts: The MIT Press, 2022. 826 p.](https://probml.github.io/pml-book/book1.html)
-	*Флах П.* "Машинное обучение. Наука и искусство построения алгоритмов, которые извлекают знания из данных." / Флах П. М.: ДМК Пресс, 2015. 400 c.
-	Маккинни У. Python и анализ данных / Пер. с англ. Слинкин А.А. – М: ДМК Пресс, 2015. – 482 с. ([Google Books](https://books.google.ru/books/about/Python_%D0%B8_%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.html?id=YC0kEAAAQBAJ&redir_esc=y))
-	Брюс П., Брюс Э. Практическая статистика для специалистов Data Science. – БХВ-Петербург, 2018. — 304 с. ([Google Books](https://books.google.ru/books?hl=ru&lr=&id=l_6MDwAAQBAJ&oi=fnd&pg=PA5&dq=%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F+%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0+%D0%B4%D0%BB%D1%8F+%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D0%B8%D1%81%D1%82%D0%BE%D0%B2+data+science&ots=fB2sdc0NnS&sig=S7_kC8Nv2Ipg5By2UbTDVDGVvqE&redir_esc=y#v=onepage&q=%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F%20%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D0%B8%D1%81%D1%82%D0%BE%D0%B2%20data%20science&f=false))



Дополнительные источники

- *Гудфеллоу Я., Бенджио И., Курвилль А.* "Глубокое обучение." / М.: ДМК Пресс, 2017. 652 c.

  - англоязычный вариант (онлайн, бесплатный): [Ian Goodfellow, Yoshua Bengio and Aaron Courville "Deep Learning"](https://www.deeplearningbook.org/)

- *Николенко С. И., Кадурин А. А., Архангельская Е. О.* "Глубокое обучение." / СПб.: Питер. 2019. 480 с.

- *Peter Bruce and Andrew Bruce* ["Practical Statistics for Data Scientists, 2nd Edition"](https://www.oreilly.com/library/view/practical-statistics-for/9781492072935/) / Sebastopol, CA, USA: O’Reilly Media, 2020.

- *Шай Шалев-Шварц, Шай Бен-Давид* "Идеи машинного обучения." / - М.: ДМК Пресс, 2018. 432 c.

- [*Hastie T., Tibshirani R., Friedman J.* "The Elements of Statistical Learning: Data Mining, Inference, and Prediction, Second Edition"](https://web.stanford.edu/~hastie/Papers/ESLII.pdf) / T. Hastie, R. Tibshirani, J. Friedman, 2-е изд., New York: Springer-Verlag, 2009.

  ​	Первод на русский язык: ([Фридман Дж., Хасти Т., Тибширани Р. "Основы статистического обучения"](https://www.ozon.ru/product/osnovy-statisticheskogo-obucheniya-intellektualnyy-analiz-dannyh-logicheskiy-vyvod-i-prognozirovanie-180548799/))

- *Bishop C.* "Pattern Recognition and Machine Learning" / C. Bishop, New York: Springer-Verlag, 2006.

  ​	Перевод на русский язык: [Бишоп К.М. "Распознавание образов и машинное обучение"](https://www.ozon.ru/product/raspoznavanie-obrazov-i-mashinnoe-obuchenie-bishop-kristofer-m-180548800/)

- [**Matrix cookbook**](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf) - справочник по соотношениям в матричной форме

- Курс лекций [К.В. Воронцова](http://www.machinelearning.ru/wiki/index.php?title=%D0%A3%D1%87%D0%B0%D1%81%D1%82%D0%BD%D0%B8%D0%BA:%D0%9A%D0%BE%D0%BD%D1%81%D1%82%D0%B0%D0%BD%D1%82%D0%B8%D0%BD_%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2):

  - [Математические методы обучения по прецедентам](http://www.machinelearning.ru/wiki/images/6/6d/Voron-ML-1.pdf)
  - [Оценивание и выбор моделей](http://www.machinelearning.ru/wiki/images/2/2d/Voron-ML-Modeling.pdf)
  - [Логические алгоритмы классификации](http://www.machinelearning.ru/wiki/images/3/3e/Voron-ML-Logic.pdf)
  - [Алгоритмические композиции](http://www.machinelearning.ru/wiki/images/0/0d/Voron-ML-Compositions.pdf)

- Курс лекций [Л.М. Местецкого](http://www.machinelearning.ru/wiki/index.php?title=%D0%A3%D1%87%D0%B0%D1%81%D1%82%D0%BD%D0%B8%D0%BA:Mest) ["Математические методы распознавания образов"](http://www.ccas.ru/frc/papers/mestetskii04course.pdf)

- Препринт книги Cosma Rohilla Shalizi "Advanced Data Analysis from an Elementary Point of View". [Доступен онлайн](https://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/).

- *James G., Witten D., Hastie T., Tibshirani R.,* 2013. "An Introduction to Statistical Learning: with Applications in R", Springer Texts in Statistics. Springer-Verlag, New York. Книга [доступна для скачивания](http://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf).

- Интерактивная онлайн-книга *Aston Zhang, Zack C. Lipton, Mu Li, Alex J. Smola* ["Dive into Deep Learning"](http://d2l.ai/) 


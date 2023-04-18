# Введение в глубокое обучение и вообще

Добро пожаловать на страничку курса "Введение в глубокое обучение и вообще". 

- Большая часть материалов курса нагло украдена из других курсов. В README к каждой неделе я пытался описывать что и где я спёр
- Материалы для каждого семинара лежат в папках `/week*`
- Курс сделан на pytorch [(в 2022 был на tensorflow)](https://github.com/FUlyankin/deep_learning_tf)
- Если вы хотите скачать из репозитория конкретную папку, просто вставьте ссылку на неё [в сервис для скачки.](https://minhaskamal.github.io/DownGit/#/home) Ну либо наконец уже [разберитесь с git](https://githowto.com/ru) и сделайте pull. 


> Нашёл на этой страничке ошибку? Нашёл какой-то ультраполезный ресурс? Придумал какое-то интересное задание для семинара? Есть конструктивная критика? Не молчи, заводи issue, делай пулл-реквест и напиши мне на почту filfonul@gmail.com или в Telegram (@Ppilif). 


- 📦 [Таблица с оценками](https://docs.google.com/spreadsheets/d/1r5koThyau5cxgp6MZAIFIwh0zdttyKe5B-nkpLatzmo/edit?usp=sharing)
- 📦 [Видео записи семинаров и лекций](https://youtube.com/playlist?list=PLNKXA-74YGLhB1xyYPK78L_M5DeMCPOY4)
- 📦 [Список проектов для получения бонусных баллов](https://github.com/FUlyankin/deep_learning_pytorch/blob/main/projects.md)
- 📦 Все важные объявления будут дублироваться в чате курса. Там же можно задать свои вопросы. Жми кнопку ниже и попадёшь в чат.

[![TG2](https://img.shields.io/badge/Telegram-DL--announcement-blue)](https://t.me/+BvoZ8PGnkmw5Mjcy)


## Идеология курса 

Показать, что никакого искусственного интеллекта не существует. Нейросетка — это просто ансамбль из регрессий. Дать понять на каком уровне развития сейчас находится эта область машинного обучения и когда ждать нормальный искуственный интеллект, который всех поработит ну или хотябы будет присылать терминаторов.


## Примерный план курса

Это приблизительный план. По ходу курса он будет немного видоизменяться. 

- [__week01__](./week01_intro) От регрессии к нейросети. Введение в pytorch. 
- [__week02__](./week02_pytorch) Решаем ручные задачки и продолжаем погружаться в pytorch. 
- [__week03__](./week03_gd) 50 оттенков градиентного спуска. Учимся искать матричные производные.
- [__week04__](./week04_backprop) Копаемся в алгоритме обратного распространения ошибки. Пробуем его закодить. 
- [__week05__](./week05_conv_nets) Свёрточные нейросети. Наконец-то добрались до них сквозь всю математику! 
- [__week06__](./week06_conv_nets) Продолжаем разбираться со свёрточными сетками 
- [__week07__](./week07_lego) Нейросети - конструктор LEGO. Говорим про разные функции активации, инициализацию, дропаут и регуляризацию. Нормализация по батчам, лучшие практики для обучения нейросетей
- [__week08__](./week08_fine_tuning) Современные архитектуры свёрточных сетей. Transfer learning.
- [__week09__](./week09_computer_vision) Разговариваем про задачи компьютерного зрения.
- [__week10__](./week10_nlp&w2v) Работа с текстами, введение в NLP, идея эмбедингов: w2v.
- [__week11__](./week11_rnn) Рекурентные нейронные сетки: RNN, LSTM, GRU. Временные ряды. 
- [__week12__](./week12_seq2seq) Seq2seq модели. Механизмы внимания. Автопереводчики.
- [__week13__](./week13_transformer) Разбираемся с трансформерами.
- [__week14__](./week14_SSL_BERT_GPT_metric_learning) Другие способы обучения нейросеток, BERT, GPT, metric learning
- **Где-то тут проводим контрольную работу!**
- [__week15__](./week15_GAN) Генеративные сетки
- [__week16__](./week16_FUN) Резервная лекция. Если она останется, то на ней рассказать что-нибудь прикольное.


## Домашки

Будет шесть домашек. 

1. Основы tensorflow, сбор своих первых нейросетей на tensorflow
2. Собираем нейросеть своими руками
3. Большое задание по работе с картинками
4. Маленькое задание на рекуррентные сетки и временные ряды
5. Большое задание по работе с текстами
6. Маленькое задание про генеративные сетки либо компьютерное зрение

В домашних заданиях будет довольно много бонусных баллов. Из-за их наличия вы сможете выбирать те разделы, которые вас больше всего заинтересовали. Одну домашку можно не делать без уважительной причины. Итоговая оценка будет ставиться за лучшие пять заданий. 


## Самый важный раздел 

Итоговая оценка вычисляется по формуле: 

```
Накоп = 0.3 СР + 0.5 ДЗ + 0.2 КР 

Итог = min(10, 0.7 Накоп + 0.3 Экз)
```

- [ ] ДЗ - средняя оценка за домашки на python (6 заданий), одна домашка сделанная хуже всего при расчёте средней оценки, не учитывается
- [ ] СР - средняя оценка за самостоялки на семинарах (около 10 квизов), две работы, написанные хуже всего, не учитываются
- [ ] КР - балл за письменную контрольную работу
- [ ] Экз - балл за письменный экзамен

Если накопленная оценка оказалась >= 6, а также за контрольную вы получили оценку >=6, можно забрать себе накопленную оценку как автомат и не сдавать экзамен. На примеры квизов, мидтёрма и экзаменов можно посмотреть [в репозитории прошлого года](https://github.com/FUlyankin/deep_learning_tf/tree/main/quizes)


__Правила сдачи заданий:__ 

За каждый день просрочки после мягкого дедлайна снимается 1 балл. После жёсткого дедлайна работы не принимаются. Даже при опозданиии на одну секунду. Сдавайте работы заранее. 

Есть исключение, и имя ему __Late days policy.__ У каждого студента есть право отложить мягкий дедлайн на 1,2 или 3 дня. Суммарно для откладывания в запасе есть три дня. Можно отодвинуть один дедлайн на три дня, а можно три дедлайна подвинуть на один день. Распоряжаться этими днями студент может как угодно. Жёсткий дедлайн, при этом, не меняется. 

При обнаружении плагиата оценки обнуляются всем, кто был задействован в списывании, а также подаётся докладная записка в учебный офис. При наличии уважительной причины пропущенную проверочную можно написать позднее, а дедлайн по домашнему заданию может быть перенесён. Дедлайн по домашнему заданию переносится на количество дней, равное продолжительности уважительной причины. Решение о том, является ли причина уважительной, принимает исключительно учебный офис. 

Любой из студентов может быть вызван на защиту любого домашнего задания. На защите по тексту работу ему задаётся несколько вопросов. Если студент не отвечает на них, работа обнуляется.


### Книги:

- 📚 Николенко: «Глубокое обучение. Погружение в мир нейронных сетей.» — книга, которую всем рекомендую читать в первую очередь.
- 📚 Гудфеллоу, Бенджио: «Глубокое обучение.» — библия глубокого обучения с ответами на многие вопросы и хорошей математикой.
- 📚 Педро Домингос: «Верховный Алгоритм.» — книга для рефлексии и мыслях о том, когда же нас поработит искуственный интеллект.
- 📚 Machine Learning with PyTorch and Scikit-Learn by Sebastian Raschka - долго думал какую книгу сюда вкинуть про пайторч. В итоге выбрал эту.  Себастьян Рашка оч крутой чел, который вошёл в 2021 году в  top-100 AI-инфлюенсеров. У него [клёвый блог про ML,](https://sebastianraschka.com/blog/) а ещё он недавно выложил в паблик [свои курсы по ML и DL](https://sebastianraschka.com/teaching/)
- 📚 [Интерактивный учебник](https://fulyankin.github.io/deep_learning_masha_book/intro.html) с разбором семинарских листочков от Ульянкина Филиппа (меня)


### Онлайн-курсы:

- 🤖 [Deep learning на пальцах.](https://dlcourse.ai) Семён из кремниевой долины записывает лекции на youtube. Объясняет и правда на пальцах. Причём сложные вещи. Круто смотреть его стримы в метро, пока куда-то едешь. 
- 🤖 Бесплатный [курс по pytorch от Samsung.](https://stepik.org/org/srr) Состоит из двух частей: [про CV](https://stepik.org/course/50352/promo) и [про NLP.](https://stepik.org/course/54098/promo)
- 🤖 [Вышкиниские лекции Жени Соколова](https://www.youtube.com/watch?v=62sP9QKYrgI&list=PLEwK9wdS5g0qa3PIhR6HBDJD_QnrfP8Ei)
- 🤖 [Курс нейронок, который читают в ШАД и сколтехе.](https://github.com/yandexdataschool/Practical_DL/tree/master)  Есть варианты кода на разных фреймворках. Есть видео лекций на русском и английском.
- 🤖 [Лекции с физтеховской deep learning school.](https://www.youtube.com/@DeepLearningSchool/playlists) Они открыли новый набор и до 26 февраля можно даже [зарегистрироваться](https://dls.samcs.ru/regform) и проходить курс в основном потоке.  
- 🤖 [CS231 от Стэнфорда](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PLSVEhWrZWDHQTBmWZufjxpw3s8sveJtnJ) Есть видео на youtbe и конспекты. Я часто буду на них ссылаться.  Многие курсы используют их материалы у себя. 
- 🤖 [Нейронные сети от Andrew Ng.](https://www.coursera.org/specializations/deep-learning) Когда ML ещё не был таким модным, все смотрели его лекции. Подходит для тех, кто хочет всё делать медленно и непринуждённо.
- 🤖 [Deep Learning Fundamentals](https://lightning.ai/pages/courses/deep-learning-fundamentals/) от Себастьяна Рашка. Во втором модуле основы пайторча. Курс выглядит приятно, запись в процессе.  \href{https://sebastianraschka.com/blog/2021/dl-course.html}{Ещё один курс Себастьяна по DL} из вуза, где он преподаёт.


Устарело, но ещё можно найти:

- 🤖 Бесплатный [курс по tf от Google.](https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187) Короткий. Покрывает весь базовый Keras. Все тетрадки выложены в colab. Внутри есть очень странные интервью.  
- 🤖 [Advanced ML от Яндекса.](https://www.coursera.org/specializations/aml) Это для тех, кто хочет развиваться дальше. В специализации есть разные специфические курсы. Первый из них про нейронки. Код на Tensorflow. Версия библиотеки там пока что старая.


## Лицензия

Весь контент, созданный для этого курса распространяются на правах лицензии [MIT License](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/LICENSE) Материалы публикуются как общественное достояние.

<img align="center" src="http://www.roundcrisis.com/presentations/ndc-oslo/images/legos.jpg" height="250" width="500">
<br>
<br>

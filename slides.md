---
# You can also start simply with 'default'
theme: seriph
addons:
  - "@twitwi/slidev-addon-ultracharger"
addonsConfig:
  ultracharger:
    inlineSvg:
      markersWorkaround: false
    disable:
      - metaFooter
      - tocFooter

background: /cover.jpg

# some information about your slides (markdown enabled)
title: Соревнования по анализу данных и методам ИИ
subtitle: some subtitle
date: 14/02/2025
venue: HSE
author: Алексей Болдырев
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
# transition: slide-down
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

<br>

## Соревнования<br> по анализу данных и методам ИИ<br> в курсе глубинного обучения<br> как эффективный инструмент<br> совместного развития *hard* и *soft* skills<br><br><br>
## Преподавательский марафон 2025<br><br>
### Олег Мельников, Максим Карпов, <u>Алексей Болдырев</u><br><br>
#### ВШЭ 14/02/2025

<div>
<br>
<span style="color:#b3b3b3ff; font-size: 11px; float: right;">Изображение: Midjourney 6.0
</span>
</div>


<style>
  :deep(footer) { padding-bottom: 3em !important; }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
zoom: 0.8
---

<style scoped>
.img-container {
  background-color: purple;
  padding: 10px 0;
  width: 200px;
}

img {
  border-radius: 50%;
  width: 180px;
  height: 180px;
  display: block;
  margin: 0 auto;
}

img.rect-img {
  object-fit: cover;
}
</style>


# Авторы методики

<div class="grid grid-cols-[3fr_4fr_3fr] gap-15">

<div>
<figure>
  <img src="/Oleg.jpg" style="height: 125px !important, border-radius: 50%;">
</figure>
<p style="text-align: center">Олег Мельников</p>

* (Ранее) приглашенный преподаватель ФКН
* Преподает:
  * Обработку естественного языка и машинное обучение (Stanford)
  * Статистику (UC Berkeley)
  * Глубинное обучение<br> (Johns Hopkins)
</div>

<div>
<figure>
  <img src="/Maksim.jpg" style="height: 125px !important, border-radius: 50%;">
</figure>
<p style="text-align: center">Максим Карпов</p>

* Старший преподаватель ФКН
* Преподает:
  * Python (курсы для бакалавриата и магистратуры)
  * Введение в анализ данных
  * Статистический анализ в социально-экономической сфере

  * **Машинное обучение 1**
  * **Глубинное обучение**

</div>

<div>
<figure>
  <img src="/Alexey.jpg" style="height: 125px !important, border-radius: 50%;">
</figure>
<p style="text-align: center">Алексей Болдырев</p>

* Доцент ФКН
* Преподает:
  * Машинное обучение для построения моделей
  * **Машинное обучение 1**
  * **Глубинное обучение**
  * Научную визуализацию данных
</div>
</div>

---
zoom: 0.97
---

# Курсы машинного обучения<br>и глубинного обучения

<div class="abs-tr mx-57 my-5">
  <img src="/FCS_logo_full_L.svg" class="h-16">
</div>

<div class="abs-tr mx-25 my-1">
  <img src="/DSBA_logo.png" class="h-28">
</div>

<div class="abs-tr mx--2 my-1">
  <img src="/ICEF_logo.png" class="h-28">
</div>
<div class="grid grid-cols-2 gap-15">

<div>

* Два практико-ориентированных курса:
  1. [**(Классическое) машинное обучение**](https://www.hse.ru/edu/courses/900069512)
      * 1-2 модули
  2. [**Глубинное обучение**](https://www.hse.ru/edu/courses/900066057)
      * 3-4 модули
* ~100 студентов
  * ПАД ФКН (3 курс)
  * МИЭФ (4 курс)
* Команда:
  * 2 лектора
  * 4 семинариста
  * 4 учебных ассистента
</div>
<div>
<br>
<br>

### Развитие компетенций:
* Анализ данных
* Выбор подходящей модели машинного обучения
  * Её настройка
  * Интерпретация её результатов
* Освоение методов глубинного обучения
  * От полносвязных сетей<br> до больших языковых моделей
* **Использование командной работы**
</div>
</div>

---

# *Hard* skills для машинного обучения

<div class="grid grid-cols-[3fr_2fr] gap-15">

<div>

* Нужно подобрать “подходящую” функцию под наблюдаемые данные.
* Проблемы:
  * Таких функций бесконечно много;
  * Какая из них "подходящая"?
  * Часто невозможно перебрать данные вручную;
    * Миллионы наблюдений;
    * Тысячи признаков.

<br>

#### У задач, к которым применяется машинное обучение, <span v-mark="{ at: 1, color: 'red', type: 'underline' }">не существует</span> "правильного" (эталонного) решения.
  * Можно ли примененить это в образовании?🤔 
<br>
<div style="color:#b3b3b3ff; font-size: 12px">Источник изображения: <a href="https://xkcd.com/2048/">https://xkcd.com/2048</a></div>
</div>
<div>
<figure>
  <img src="/curve_fitting_2x.png" style="width: 270px !important;">
</figure>
</div>
</div>

---
zoom: 0.97
---

# Платформа Kaggle
* Kaggle - крупнейшее в мире сообщество специалистов по исследованию данных, готовых решить поставленную проблему предиктивного моделирования с помощью соревнований.
* Вы задаете условия соревнования, участники (кагглеры) создают свои алгоритмы,<br> а платформа Kaggle в реальном времени оценивает их точность, чтобы выявить победителя.

<br>
<div class="grid grid-cols-4 gap-15">
<div>
<figure>
  <img src="/Kaggle_intro_1.svg" style="width: 135px !important">
</figure>
<p style="text-align: center">22+ миллионов участников</p>
</div>
<div>
<br>
<figure>
  <img src="/Kaggle_intro_2.svg" style="width: 145px !important">
</figure>
<p style="text-align: center">15+ миллионов загруженных алгоритмов</p>
</div>
<div>
<figure>
  <img src="/Kaggle_intro_3.svg" style="width: 110px !important">
</figure>
<p style="text-align: center">5700 проведенных соревнований</p>
</div>
<div>
<figure>
  <img src="/Kaggle_intro_4.svg" style="width: 120px !important">
</figure>
<p style="text-align: center">400 тысяч наборов данных</p>
</div>
</div>

<div style="color:#b3b3b3ff; font-size: 12px">Источник: <a href="https://www.kaggle.com/code/carlmcbrideellis/kaggle-in-numbers">https://www.kaggle.com/code/carlmcbrideellis/kaggle-in-numbers</a></div>

---
layout: statement
---

## Примеры соревновательных задач из курсов<br> машинного обучения и глубинного обучения<br> на ПАД ФКН и МИЭФ

---

# Определение стоимости драгоценных камней

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <figure>
  <img src="/diamonds_properties.png" style="width: 320px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:<br>
     <a href="https://www.nature.com/articles/s41598-023-44326-w">https://www.nature.com/articles/s41598-023-44326-w</a></span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_diamonds.png" style="width: 420px !important; position:relative; top: -20px; left: 13px">
</figure>
</div>
</div>

---

# Классификация бактерий по их ДНК

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <br>
  <br>
  <br>
  <figure>
  <img src="/dna.png" style="width: 380px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:<br>
     <a href="https://deepmind.google/discover/blog/predicting-gene-expression-with-ai/">https://deepmind.google/discover/blog/predicting-gene-expression-with-ai/</a></span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_genomics.png" style="width: 420px !important; position:relative; top: -10px; left: 13px">
</figure>
</div>
</div>

---

# Определение фонем

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <br>
  <br>
  <br>
  <figure>
  <img src="/phonemes.png" style="width: 480px !important; position:relative; left: -45px">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:<br>
    Рис. 5.5 из книги T.Hastie, R. Tibshirani, J. Friedman,<br> The Elements of Statistical Learning: Data Mining, Inference, and Prediction (2017)</span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_phonemes.png" style="width: 420px !important; position:relative; top: -20px; left: 13px">
</figure>
</div>
</div>

---

# Классификация звезд

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <br>
  <br>
  <br>
  <figure>
  <img src="/galaxies.jpg" style="width: 480px !important; position:relative; left: -45px">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:<br>
    <a href="https://classic.sdss.org/news/releases/20031028.powerspectrum.php">https://classic.sdss.org/news/releases/20031028.powerspectrum.php</a></span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_stellar.png" style="width: 420px !important; position:relative; top: -20px; left: 13px">
</figure>
</div>
</div>

---

# Определение рейтинга фильма

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <br>
 
 #### Адаптированное соревнование [Netflix Prize](https://ru.wikipedia.org/wiki/Netflix_Prize)
  <br>
  <figure>
  <img src="/netflixawards.480.jpg" style="width: 460px !important; position:relative; left: -20px">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:<br><a href="https://archive.nytimes.com/bits.blogs.nytimes.com/2009/09/21/netflix-awards-1-million-prize-and-starts-a-new-contest/">
    Jason Kempin/Getty Images Netflix prize winners</a></span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_netflix.png" style="width: 420px !important; position:relative; top: -10px; left: 13px">
</figure>
</div>
</div>

---

# Прогнозирование курса криптовалюты

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <br>
  <br>
  <br>
  <figure>
  <img src="/OHLC_chart.svg" style="width: 460px !important; position:relative; left: -20px">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:<br>
    <a href="https://datavizcatalogue.com/methods/OHLC_chart.html">https://datavizcatalogue.com/methods/OHLC_chart.html</a></span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_crypto.png" style="width: 420px !important; position:relative; top: -10px; left: 13px">
</figure>
</div>
</div>

---

# Определение двигательной активности человека

<div class="grid grid-cols-[2fr_2fr] gap-1">

<div>
  <br>
  <br>
  <br>
  <br>
  <figure>
  <img src="/har.jpg" style="width: 460px !important; position:relative; left: -20px">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; float: left;"><span>Источник изображения:    <a href="https://www.nytimes.com/wirecutter/reviews/the-best-fitness-trackers/">Marki Williams</a></span>
    </figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Kaggle_har.png" style="width: 420px !important; position:relative; top: -10px; left: 13px">
</figure>
</div>
</div>

---

# Как студенту во всем разобраться?

#### <ins>Проблема</ins>: студенты не могут и не обязаны разбираться<br> во всех столь разнообразных предметных областях.
<br>
<br>

#### <ins>Решение</ins>:
* Вместе с условиями соревнования мы предлагаем студентам:
  1. 🔤 **Простое базовое решение**
      * 📖 Основанное на одной из пройденных ранее тем курса;
        * Например: модель линейной регрессии;
      * Помогает студентам не тратить много времени на трудоемкие, но простые действия.
  2. 🔍💡 **Стартовые идеи**:
      * ❔ Наводящие вопросы;
      * 📑 Ссылки на исследования, посвященные решению похожей задачи.

---
zoom: 0.85
---

# Техническая организация соревнований

* На странице курса в **Smart LMS**:
  * Преподаватель добавляет активность [Assignment](https://docs.moodle.org/401/en/Assignment_activity), где приводит правила соревнования,<br> оставляет ссылки на страницу соревнования на Kaggle и на базовое решение в [Colab](https://colab.research.google.com)
  * Преподаватель создает [шаблоны групп](https://docs.moodle.org/401/en/Groupings), добавляет и настраивает активность [Group choice](https://docs.moodle.org/401/en/Group_choice_activity)
  * Студенты выбирают себе команду в активности Group choice
<figure>
<img src="/moodle_group_choice.png" style="width: 420px !important;">
</figure>

* В **Kaggle**:
  * Преподаватель настраивает соревнование (🔢 набор данных, 📜 правила оценивания, ⏰ дедлайны,<br> 👩‍🎓👨‍🎓количество участников в командах, 📦 количество отправок решений в день)
  * Студенты создают команды под тем же именем, что и в Smart LMS
* В **Colab**:
  * В Jupyter-тетрадке c базовым решением студентам доступен программный интерфейс<br> для загрузки набора данных и для отправки решений на Kaggle

---
zoom: 0.93
---

# Турнирная таблица соревнования

<div class="grid grid-cols-[1fr_1fr] gap-1">
<div>
<figure>
<img src="/LB_1.png" style="width: 360px !important;">
</figure>

##### <span>&#8203; &#8203; &#8203; &#8203; &#8203;</span> ...

<figure>
<img src="/LB_3.png" style="width: 360px !important;">
</figure>
</div>
<div>
<figure>
<img src="/LB_2.png" style="width: 360px !important;">
</figure>

##### <span>&#8203; &#8203; &#8203; &#8203; &#8203;</span> ...

<figure>
<img src="/LB_4.png" style="width: 360px !important;">
</figure>
</div>
</div>
<br>

##### Студенты в режиме реального времени видят результат своей команды в общедоступной турнирной таблице

---

# Оценивание команд

#### После окончания соревнования публикуется<br> приватная турнирная таблица:
<div class="grid grid-cols-[3fr_4fr] gap-10">
<div>
<figure>
<img src="/LB.png" style="width: 420px !important;">
</figure>
</div>
<div>

* Kaggle автоматически засчитывает последнее отправленное / лучшее решение
* Всем студентам в команде выставляется одинаковая оценка согласно квартилю в приватной турнирной таблице
* Учебные ассистенты проверяют соответствие решения команды правилам соревнования
  * Регламентировано снятие баллов за несоблюдение тех или иных правил
</div>
</div>
<br>

#### Большие языковые модели не помогут (на сегодняшний день) с ответами (как в квизах)!

---
zoom: 0.95
---

# Развитие *soft* skills

### Студенты тренируют:
  * 🤝👥🙌 **Навыки командной работы**
    * Способности к коммуникации для решения задач межличностного взаимодействия
      * особенно в случах, когда студенты не выбирают в какой команде окажутся
    * Распределение ролей и зон ответственности в команде
    * Взаимное оценивание и взаимная обратная связь
  * 📅⏳ **Умение работать в сжатые сроки**
    * Промежуточный дедлайн для формирования команды и отправки первого решения позволяет неявно указать студентам на важность организации работы в команде и на сроки выполнения
  * 📚📝💡 **Способность к самоорганизации и самообразованию**
  * 🌟📈 **Презентацию результатов собственного труда**
    * По окончании соревнования команды первого квартиля турнирной таблицы должны опубликовать своё решение (прочие команды делают это по желанию) 

---
zoom: 0.95
---

# Преимущества предложенной методики командных соревнований для преподавателей

* Сокращение работы преподавателей и учебных ассистентов
  * Масштабирование ограничено количеством команд на одного учебного ассистента
* ⚗️ "Методическая лаборатория":
  * 👥 Командообразование
    * Самостоятельный выбор сокомандников / случайное распределение по командам
    * Размер команды
    * 💬 Отзывы на сокомандников
  * ⚙️ Автоматическое оценивание по квартилям
  * ✔️ Гибкие дедлайны

<br>
<div class="grid grid-cols-[3fr_2fr] gap-1">
<div>

* 📊 Первичная (до оценивания) аналитика<br> успеваемости студентов
</div>
<div>
<figure>
<img src="/analytics.png" style="width: 320px !important; position:relative; top: -130px;">
</figure>
</div>
</div>

---
zoom: 1.1
---
# Выводы

#### Предложенная методика командных соревнований по анализу данных:<br>

* Позволяет одновременно развивать *hard* и *soft* skills студентов

* Дополняет традиционные формы домашних заданий<br> для курсов машинного и глубинного обучения

* Устойчива к полному решению при помощи Больших языковых моделей

* Легко масштабируется

* Экономит время преподавателей, учебных ассистентов и студентов

* Является "Методической лабораторией"

* Предоставляет первичную аналитику успеваемости студентов

---
layout: statement
---

## Спасибо за внимание!

<br>
<br>

#### Рад ответить на ваши вопросы по почте <a href="mailto:aboldyrev@hse.ru">aboldyrev@hse.ru</a> и в Телеграме <a href="https://t.me/aboldyrev">@aboldyrev</a>

<PoweredBySlidev mt-10 />

---
layout: center
class: text-center
---

# Дополнительные слайды

---
zoom: 0.87
---

# Чем привлекает машинное обучение?

### Работодателей, исследователей
  * Позволяет ускорить и масштабировать принятие решений:
    * Поиск информации в интернете (Яндекс, Google, ...)
    * Поиск товаров, сервисов, документов (Ozon, Amazon, ...)
    * Рекомендации (Сбер, КиноПоиск, Netflix, ...)
    * Инвестиции в акции (алгоритмы следят за миллионами трендов и инвестируют за доли секунды)
  * Сокращать затраты на производство, улучшить/индивидуализировать сервисы
  * Оставаться конкурентоспособными на рынке
### Студентов
  * Высокооплачиваемые и интеллектуальные работы/проекты (в Яндекс, Сбер, FAANG, ...)
  * Стабильные карьеры на международном рынке с конкурентными зарплатами
    * Большой, растущий спрос на инженеров, программистов, data scientists
  * Сотрудничество с выдающимися учёными в мире
  * Разработка решений глобальных проблем
  * Изобретение будущих технологий

---

# 💬 Отзывы на сокомандников

#### В "Методической лаборатории" мы экспериментировали с командообразованием
* Оказалось, что студентам затруднительно работать одновременно в случайно сформированных командах и в сжатые сроки
  * Основные претензии студентов к сокомандникам:
    * Не коммуницируют
    * Не выполняют договоренности и срывают сроки
* Мы решили потребовать от студентов оценить сокомандников после завершения соревнования, пройдя небольшой опросник (см. следующий слайд).

* Хотя каждому участнику команды выставляется единая оценка по результатам положения в турнирной таблице Kaggle, индивидуальные оценки участников команды могут быть скорректированы в сторону увеличения или уменьшения в зависимости от отзывов участников об их командной работе.

---

# 💬 Отзывы на сокомандников

##### Вопросы в отзывах оцениваются по шкале: 10=Потрясающе, 9=Отлично, 8=Очень хорошо, 7=Хорошо, 6=Выше среднего, 5=Средне, 4=Ниже среднего, 3=Слабо, 2=Очень слабо, 1=Ужасно, 0=нет мнения или неприменимо
<br>
<div class="grid grid-cols-2 gap-10">
<div>

* Эффективность обучения в команде
* Моя доступность и коммуникабельность в соревновании
* Моя помощь в обучении сокомандников
* Моя эффективность в этом соревновании
* Помощь сокомандника в моем обучении
* Моя готовность к этому заданию
</div>
<div>

* Эффективность организации команды
* Участие, вовлеченность, отзывчивость сокомандника
* Доступность и коммуникабельность сокомандника
* Готовность сокомандника к выполнению задания
</div>
</div>
<br>

##### В опроснике есть опциональное текстовое поле:<br> "Поделитесь вашим опытом работы в группе.<br> Расскажите нам, что у вас получилось хорошо, а что можно улучшить."

---
zoom: 1.1
---

# 💬 Отзывы на сокомандников

* Использование такого опросника осуществляет взаимное оценивание и взаимную обратную связь во взаимодействии студентов внутри команд
  * ➕ Позволяет снизить число спорных случаев при выставлении оценок
  * ➖ Сопряжено с дополнительными накладными расходами времени и труда

* Предварительный вывод: большинство студентов не готовы к интенсивной работе в **случайно сформированных** командах
<br>
<br>

* <ins>Альтернативный подход</ins>: студенты сами формируют команды<br> и целиком отвечают за успех в выполнении задания
  * Возможны соло-команды по желанию студента
  * ➖ Студенты поляризуются в сильные и слабые команды
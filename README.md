# Coursework_analytics

**Описание работы:**

Вам необходимо подготовить данные и описать их. Данные реальные и содержат пропущенные значения, а также лишние относительно друг друга данные.
Опишите данные: <br>
1. **(p)** Посчитайте
      * общее количество курсов в датасете, 
      * количество модулей на каждом курсе, 
      * количество уроков в каждом модуле на каждом курсе, 
      * медианное количество уроков в модуле на каждом курсе, 
      * количество учеников на каждом курсе
      * минимальный, максимальный, средний, медианный возраст студентов
      * минимальный, максимальный, средний, медианный возраст студентов на каждом курсе
2. **(m)** Постройте bar-chart, отражающий количество студентов на каждом курсе. Ticks нужно развернуть так, чтобы они были читаемы
3. **(m)** Постройте горизонтальный (столбцы должны располагаться горизонтально) bar-chart, отражающий количество студентов на каждом курсе. 
4.     На основании рассчитанных значений опишите данные (описание должно быть полным и покрывать все полученные выше метрики)


Codebook
courses.csv содержит следующие значения:

     id – идентификатор курса
     title – название курса
     field – сфера, к которой относится курс


students.csv содержит следующие значения:

     id – идентификатор студента
     city – город студента
     birthday – день рождения студента


course_contents.csv содержит следующие значения:

     course_id – идентификатор курса
     module_number – номер модуля
     module_title – название модуля
     lesson_number – номер урока
     lesson_title – название урока
     lesson_token – токен урока
     is_video – наличие видео (true/false)
     is_homework – наличие домашней работы (true/false)


progresses.csv содержит следующие значения:

     id – идентификатор прогресса
     student_id – идентификатор студента
     course_id – идентификатор курса


progress_phases.csv содержит следующие значения:

     progress_id – идентификатор прогресса
     module_number – номер модуля
     lesson_number – номер урока
     status – статус прохождения урока
     start_date – дата начала
     finish_date – дата окончания





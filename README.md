sqlite3

.open /home/sfleta/Загрузки/test.db
.mode csv
.headers off
.import /home/sfleta/DataGripProjects/sql_diy_course/persons.csv persons
.import /home/sfleta/DataGripProjects/sql_diy_course/adress.csv adress
.import /home/sfleta/DataGripProjects/sql_diy_course/contacts.csv contacts
.import /home/sfleta/DataGripProjects/sql_diy_course/lessons.csv lessons
.import /home/sfleta/DataGripProjects/sql_diy_course/material.csv material
.import /home/sfleta/DataGripProjects/sql_diy_course/schedule.csv schedule

.import /home/sfleta/DataGripProjects/sql_diy_course/material_lesson.csv material_lesson
.import /home/sfleta/DataGripProjects/sql_diy_course/person_lesson.csv person_lesson
.quit

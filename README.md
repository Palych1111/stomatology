**Курсовая "Стоматология"**

**Цель автоматизации:**

Быстрая запись к врачу,благодаря автоматизированной системе.

**Описание предметной области:**

Требуется разработать автоматизированную систему для быстрой записи к врачу на приём.

Пациент имеет возможность выбора даты и времени,выбор специалиста и услуги.

Возможность осуществления управленческого учёта и контроля деятельности медицинского центра (какой специалист, в какое время, на какую сумму оказал услуги, какие материалы были использованы, в каком количестве, а также другую подобную информацию можно будет отследить практически мгновенно).

Увеличение пропускной способности медицинского центра (сокращается время приёма пациентов благодаря автоматизации)


Любое использование материалов допускается только при наличии гиперссылки

# Сущности:

# Doctors

- id-id доктора

- Fio_doctor-ФИО доктора

- Phone-номер телефона доктора

- Specialization-Специальность

- Category-Кфалификация(от квалификации зависит стоимость услуги)
 
# Patients

- id-id пациента
- Fio_patient-ФИО пациента
- Phone_patient-номер телефона пациента
- Year_of_Birth-дата рождения

# Visits

- id_visit-id визита
- Fio_patient-ФИО пациента
- Fio_doctor-ФИО доктора
- Date_and_time_visit-дата и время визита
- Purpose_of_the_visit-цель визита
- Price-цена
- Diagnosis-диагноз

# Servises
- id_servis-id услуги
- name_servis-наименование услуги



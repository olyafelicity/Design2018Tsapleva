**Отчет о лабораторных работах**<br>
Студент группы [ИДБ-15-12](https://github.com/stankin/design-2018/wiki/list-idb-15-12) Цаплева О. А.<br>
**Лабораторная 1**<br>
Индивидуальное задание IDEF0 (png)<br>
 [ссылка idef0 шесть вопросов](http://127.0.0.1:62622/idef0/index.html?id=3)<br>
 <img src="modelred.png"><br>
 [ссылка диаграммы классов](http://www.plantuml.com/plantuml/png/JOzDIiH048NNqwSePgNW8SRn0kvSDzsDqqnFMgeJN8WG5Lm9MRYNn1E8Fn0YnYkylf4LiZ2Rehxt7e-gJIerbzKXgBJtnPLcVI0JT4fqerPRRVQN7Al2diKGcIvsldHgTSeShsTb6oGYmSZMyLAwLNFB6Ys-y8at3FaUOwxNf1ETIpkXo_NiaOplt93mVxON6l4kz2DxenP5ZvD062O77-Zf26r-41xnAzPTVZeXFEC57LwFvPITjuwCPnESshZ2ohj_)<br>
<img src="tab.png"><br>
 [ссылка диаграммы прецедентов](http://www.plantuml.com/plantuml/png/fO_1IiD048RFdQSOSj93mGSGQUeva9ld9LdRfPkip4xmO8NWmQkFe9wybgeWLViCks_awAPIl4f8yk___VCpE_6iYBl6Wb-OzaAHQb1Lx0YlO3HLrM96hclhKsV5EfiRrZ3AYTnbSgPM8X9qL6lQjwxt-ZglA-NrlnkjFcTaXsHcSyRQaAxOk1RIlkKHAezPU0gluJrimrh-cso0nG3lOo_eMRwhy27FQXSe4t-GeHTXctWJjh7_7K_qCVQ9On93yEsdT2sdJz5t6UmkdFyjlKsynF4O3_93aFTR5Y3B7oz5bL28iJoHXM6Ysxfhx1S0)
<img src="scheme.png"><br>
**Лабораторная 2**<br>
IDEF0 (png)<br>
<img src="modelred.png"><br>
**Определение надсистемы (среды функционирования)**<br>
[Блок Plan-Do-Check](http://127.0.0.1:55093/idef0/index.html?id=4)<br> 
<img src="model2.png"><br>
[Блок Check](http://127.0.0.1:55093/idef0/index.html?id=24)<br>
<img src="check.png"><br>
**Лабораторная 3**<br>
[Блок Создание оригинал-макета книги](http://127.0.0.1:55093/idef0/index.html?id=58)<br>
<img src="originalmake.png"><br>

[Блок Создание оригинал-макета книги](http://127.0.0.1:55093/idef0/index.html?id=58)<br>
<img src="originalmake.png"><br>
### Лабораторная работа №4
***
### Определение основных средств автоматизации
Определение требований к модели
* Формальное определение объекта моделирования (процесса) - построение функционально-воксельной модели рельефа
* Формальное определение точки зрения (владелец, руководитель) - разработчик
* Формальное определение цели моделирования (вопросы к модели) - визуализация довольно сложного процесса построения функционально-воксельной модели.
* Формальное определение темы курсового проекта (наименование информационной системы) - Система для выделения сложных форм рельефа

### Разработка диаграмм в RAMUS<br>
![ссылка на диаграммы](http://127.0.0.1:53682/fullmodel/index.html?id=3)<br>

* Контекстная диаграмма А0 - "построение функционально-воксельной модели рельефа"

![A0](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/model0.png)

* Декомпозиция диаграммы уровня А0 на четыре блока

![A1-А4](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/modelaa0.png)

* Декомпозиция блока А2 "Триангуляция Делоне"

![A21-A23](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/modelaa2.png)

* Декомпозиция блока А3 "Билинейная интерполяция"

![A31-A34](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/modela3.png)

* Декомпозиция блока А4 "Построение М-образов"

![A41-A43](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/modela4.png)
### Лабораторная работа №5
***

### Определение основных средств автоматизации
* Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование):
  - Рабочие станции (электронные устройства);
  - Сервер приложений;
  - Сервер БД.
* Определение конфигурации программных средств (одноуровневые, многоуровневые, встроенные, распределенные):
  - Многоуровневые (трехуровневые).
* Определение допустимых видов хранилищ и их размещения:
  - Внутренняя память устройства.
  - База данных на сервере БД.

### Разработка диаграмм в RAMUS - декомпозиция всех автоматизируемых блоков в DFD

* Декомпозиция блока А1 "Вычисление облака точек"

![A11](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/modeldfda1.png)

* Декомпозиция блока А23 "Определение топологии связей между узлами"

![A12](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/modeldfda23.png)

### Лабораторная работа №6
***

![](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/potok.png)

[Код UML](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/erdpotok.txt)


![](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/rolesim.png)

[Код UML](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/roles.txt)

![](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/mod2.png)

[Код UML](https://github.com/olyafelicity/Design2018Tsapleva/blob/master/mod1.txt)




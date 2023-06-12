# Модель телефона и зарядки в Blender :iphone:
## Пример работы
![my phone](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/eca9e899-3243-4a38-9ede-4ec035416ec0)
![зарядка модель](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/63a23547-3c75-4280-ba39-f827506533be)

---
![image](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/efa5bc86-c497-4f72-b987-6285dd965e7e)
---
# О работе
Для создания 3D моделей я использовал проргамму Blender.

Blender — профессиональное свободное и открытое программное обеспечение для создания трёхмерной компьютерной графики.

## Первая работа
Для первой работы я использовал готовые фотки (референсы) телефона с разных ракурсов, добавив их в проект блендер. Потом редактировал модель по данным фоткам.

![телефон1](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/d66ce414-3c5c-4978-9819-f98c252bbeb9)
![телефон2](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/ff00496b-287a-41c5-978b-aa59d4e4bd0d)

Основные функции, которые я использовал:

- **Bevel** - модификатор сглаживающий края сетки, к которой он применяется, с некоторым контролем того, как и где скос применяется к сетке.

Использовался для скругления краёв у корпуса телефона, стекла телефона, стекла у задней камеры, формы с помощью, которой вырезал передний и нижний динамики, гнездо для зарядки.

![image](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/079ec887-72ba-4280-8230-75047d296afc) 

- **Boolean** - модификатор выполняющий операции с сетками, которые в противном случае слишком сложны для выполнения всего за несколько шагов путем редактирования сеток вручную. Он использует одну из трёх доступных логических операций для создания одной сетки из двух:

![image](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/fc68df74-9640-4d41-83ec-127c1d961282)

Объединение (Union), пересечение (Intersection) и разность (Difference) между объектами Cube и UV Sphere с применением модификатора к сфере и использованием куба в качестве цели.

Использовалась для выреза отверстий нижнего динамика, датчика отпечатков пальца, зарядного разъёма, переднего динамика.

- **Matrials Properties** - настройка, помогающая задать материал объекта, цвет и редактировать свойства материала.
![image](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/ff0838e7-0ed5-4666-ad86-5ff0d8bce817)

## Вторая работа
Зарядку же я делал без использования референсов. В данной работе использовались те же самые функции, но был дабавлен новый объект, из которого в последствии был сделан шнур.

- **BezierCurvey(Кривая Безье)** - добавляет 2D кривую, придав толщину (в параметре Depth) которой, можно создать 3D кривую.

![image](https://github.com/Sazukiro/My-Phone-and-Charger-in-Blender/assets/133951840/96ef3880-792f-44fc-9b9b-2b45f1ab69cd)

---
# Ссылка на теоретический материал:

<a href="https://youtu.be/5sh7_tONFaM"><img src = "https://i.ytimg.com/vi/5sh7_tONFaM/maxresdefault.jpg" width=80%></a>

---

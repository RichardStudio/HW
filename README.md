# HW
UnrealEngine HomeWork

Название проекта: HWA

Описание: 3D platformer с процедурной генерацией

Gameplay: 

•	Цель игры: пройти как можно больше уровней

•	Бонусы: игроку доступно 2 бонуса. Freeze замораживает все движущееся объекты на несколько секунд. Boots позволяет проходить сквозь стены на платформах в течении нескольких секунд.

•	Препятствия: в игре представлено несколько видов платформ:

1.	Стандартная платформа. Она ничего не делает. На ней можно стоять.
2.	Платформа со стеной. Игрок может ее перепрыгнуть или пройти с помощью ботинок.
3.	Вращающаяся платформа. Сбивает игрока с направления.
4.	Платформа с двигающейся сферой, которая убивает при соприкосновении.
5.	Платформа с коробкой, которую можно двигать.
6.	Финиш. Генерирует новый уровень с повышенной сложностью. 

•	Игровой процесс. В самом начале игрок появляется на платформе со случайным бонусом. Он может использовать его в любой момент по нажатию на кнопку Е. На каждом уровне игроку предстоит пройти несколько препятствий. Чем больше сложность, тем больше препятствий ему нужно пройти. Передвижение на клавиши WASD, прыжок SPACE. При использовании бонуса Freeze все движущиеся препятствия замирают. При использовании ботинок стены на платформах становятся проходимыми. 

•	Конец уровня. Если игрок умирает (падает или умирает от сферы), то уровень перезагружается и генерируется заново. Если игрок доходит до финиша, то количество препятствий на следующем уровне увеличивается и уровень перегенирируется.

Текстуры и графика: в игре использованы стандартные текстуры и модели. Для финиша использовалась картинка из интернета.
Генерация: в игре используется процедурная генерация. Предсказать уровень изначально невозможно. Препятствия генерируются случайно. С каждым пройденным уровнем кол-во препятствий увеличивается на 5.

Технологии: игра разрабатывалась на Unreal Engine 4.26. Для компьютеров с операционной системой Windows 10.

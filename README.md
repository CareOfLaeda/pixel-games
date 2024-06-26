<img align="right" src="https://github.com/pixel-quest/pixel-games/raw/main/img/logo.png" height="200">

# 🕹 Игры [Pixel Quest](https://pixelquest.ru)

Репозиторий содержит исходный код игр проекта [Pixel Quest](https://pixelquest.ru), написанных на языке Lua.
Здесь представлены исходники не всех игр проекта, часть игр по-прежнему написана на Go и со временем будет также перенесена на Lua.

### Следить за технической стороной проекта Pixel Quest можно в телеграм канале [@pixel_quest](https://t.me/pixel_quest)

Скрипты обслуживаются виртуальной машиной [GopherLua](https://github.com/yuin/gopher-lua), написанной на языке Go.
На данный момент используется **GopherLua v1.1.1** (Lua5.1 + оператор goto из Lua5.2).

См. базовое описание структуры скрипта и понятийный аппарат в [Wiki](https://github.com/pixel-quest/pixel-games/wiki)  
Шаблон скрипта с подробными комментариями – [template_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/template_v1/template_v1.lua)

### Отладочная платформа
Для написания и отладки кода игр у нас есть специальная web-платформа, доступ к которой можно получить, вступив в группу телеграм [@pixel_quest_games](https://t.me/pixel_quest_games)

<img src="https://github.com/pixel-quest/pixel-games/raw/main/img/stand1.jpg">

<img src="https://github.com/pixel-quest/pixel-games/raw/main/img/stand2.jpg">

### Список текущих механик Pixel Quest
- **Lua**
  - Заставка **Радуга** – *переливающийся пол* [rainbow_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/rainbow_v1/rainbow_v1.lua)
  - **Пиксель дуэль** – *собираем свой цвет быстрее соперника* [pixel_duel_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/pixel_duel_v1/pixel_duel_v1.lua)
  - **Море волнуется** – *соревнуемся и собираем на цветном поле свой цвет* [sea_is_rough_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/sea_is_rough_v1/sea_is_rough_v1.lua)
  - **Безопасный цвет** – *нужно успеть встать на безопасный цвет, прежде чем поле загорится красным* [safe_color_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/safe_color_v1/safe_color_v1.lua)
  - **Пинг-понг** – *платформами отбиваем мячик друг другу* [ping_pong_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/ping_pong_v1/ping_pong_v1.lua)
  - **Танцы** – *ловим пиксели под веселую корейскую музыку* [dance_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/dance_v1/dance_v1.lua)
  - **Найди цвет** – *на разноцветном поле требуется найти нужный цвет* [find_color_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/find_color_v1/find_color_v1.lua)
  - **Защита базы** – *по центру карты стоит база, которую защищают игроки* [tower_defence_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/tower_defence_v1/tower_defence_v1.lua)
  - **Лава дуэль** – *игровое поле поделено на зоны, где отдельные игроки соревнуются на скорость* [lava_duel_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/lava_duel_v1/lava_duel_v1.lua)
  - **Эстафета** – *две команды соревнуются между собой на скорость прохождения* [classics_race_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/classics_race_v1/classics_race_v1.lua)
  - **Лабиринт** – *аналог Пакмана* [labyrinth_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/labyrinth_v1/labyrinth_v1.lua)
  - **Сапёр** – *соревновательная игра на запоминание рисунка мин* [minesweeper_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/minesweeper_v1/minesweeper_v1.lua)
  - **Перебежка** – *бегаем от кнопки к кнопке, перепрыгивая полоску лавы* [dash_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/dash_v1/dash_v1.lua)
  - **Змейка** – *аналог Пиксель дуэли против компьютерной змейки* [snake_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/snake_v1/snake_v1.lua)
  - **Час пик** – *выведи машинку из затора в час пик*  [huarong_v1.lua](https://github.com/pixel-quest/pixel-games/blob/main/huarong_v1/huarong_v1.lua)
- **Go**
  - Заставка **Круги на воде** – *расходящиеся круги от шагов*
  - Заставка **Марио** – *рисунок Марио во весь пол с переливающимся фоном*
  - **Пол – это лава** – *собираем синие, избегая лавы (самая жирная и тяжёлая механика, под неё имеется конструктор уровней)*
  - **Классики** – *классики 3х6*

### Приоритетная очередь механик на разработку
- **Повтори рисунок** – *нужно на скорость нарисовать рисунок по шаблону (уже в процессе разработки на Lua)* 
- **Черепашьи бега** – *игроки быстро попеременно нажимают на пиксели, а на экране бегут черепашки*
- **Вирус** – *игроки захватывают поле своим цветом*
- **Арканоид** – *платформой отбиваем мячик, выбивая блоки на противоположной стороне*

## Лицензия
**Игры Pixel Quest** распространяются по лицензии [CC BY-NC-SA 4.0](https://github.com/pixel-quest/pixel-games/blob/main/LICENSE)  
Коммерческое использование запрещено.  
Обязательно указание первоисточника.  
Pixel Quest © 2023−2024  
  
ООО "Пиксель Квест"  
ОГРН: 1235000071371  
ИНН: 5050159532  
КПП: 505001001  

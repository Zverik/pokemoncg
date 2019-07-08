---
layout: default
lang: ru
title: Pokemon DIY Card Game
translate: переведите
or: или
improve: предложите улучшение
---
## Подготовка

Для игры понадобится кубик d6, простой карандаш для временных пометок
и стирательная резинка, чтобы удалить старые пометки.

Сначала нужно нарисовать карточки:

* 30+ карт обычных покемонов
* 5+ карт легендарных покемонов
* 10+ карт покеболлов
* 10+ карт других предметов (список см. внизу)

Итого, 55 карт минимум: двух листов картона А4, разделённого на полоски 4×7,
должно хватить.

На обороте нужно различить обычных и легендарных покемонов,
а также все предметы скопом (покеболлы и обычные, это сюрприз).

![](images/pokemoncg_pokemon.jpg)

На карте каждого обычного покемона обязательно нарисовать точечки
по его [Catch Rate](https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_catch_rate),
см. таблицу:

| 255  | 1 |
| 200+ | 2 |
| 130+ | 3 |
| 90+  | 4 |
| 45+  | 5 |
| 1+   | 6 |

У легендарных всегда 7, можно не рисовать. Если покемон выдуманный, то бросайте кубик.

## Начало игры

Игрокам выдаётся по 1 стартовому покемону (специальному или из нормальных)
с силой 1 и по 1-2 покебола. У игрока может быть сколько угодно покемонов
в запасе и только 3 в игре. Менять их можно вне боя когда угодно.
Предметов может быть сколько угодно.

## Ход

![](images/pokemoncg_overview.jpg)

Открываем покемона и кидаем кубик d6, чтобы определить его силу по таблице.
В ней A — сила самого слабого покемона у игрока, а Z — самого сильного. Очевидно, минимум — 1.

| 1 | A–1 |
| 2 | A   |
| 3 | A+1 |
| 4 | Z–1 |
| 5 | Z   |
| 6 | Z+1 |

Для небольшого усложнения игры можно использовать 4=A+2, 5=Z–1, 6=Z.

Таблица победы такая:

| Сила покемона игрока относительно N — силы покемона на столе | Сколько нужно выкинуть на кубике, чтобы победить |
|--------------|----|
| N+2 и больше | победа автоматом |
| N+1          | 2+ |
| N            | 4+ |
| N–1          | 6  |
| N–2 и меньше | проигрыш автоматом |

При проигрыше покемон теряет сознание и пропускает следующую битву.
В бой вступает следующий покемон игрока — но покемон на поле с каждой битвой теряет одно очко силы.
То есть, покемон 7 уровня после победы над покемоном игрока бьётся со следующим,
но уже с силой 6. Сила может быть 0 и не может быть -1.

В любое время можно сбежать.

### После боя

![](images/pokemoncg_active.jpg)

При победе игрок берёт карточку предмета (можно использовать в следующий ход)
и ставит чёрточку на всех покемонах, участвовавших в битве (и только них:
если покемон отсиживался, чёрточки не получает). Три чёрточки — плюс уровень.

Если разница между силой покемонов 3 и больше — то ставим две чёрточки. 6 — три, 9 — четыре и так далее.

### Ловим покемона

После боя можно кинуть покебол и попытаться поймать покемона. Для поимки нужно кинуть кубик
и чтобы результат был не меньше, чем число точек на карточке. Если покемон не побеждён, нужно выкинуть на один больше.

Например, если легендарный покемон не побеждён, то нужно выкинуть 8 и больше.
Используя ультрабол, достаточно выкинуть 6. Если победить этого покемона, то нужны 5 или 6.
Наконец, добавив карту «+2 к поимке», для ловли ультраболом побеждённого легендарного покемона
достаточно выкинуть 3 или выше — вероятность поимки 67%.

Можно кидать несколько покеболов, если первые не сработали.

Пойманному покемону нужно отметить базовый уровень — который выпал ему перед боем.

## Легендарные покемоны

Когда старший покемон достигает 10 уровня, в игру вступают легендарные покемоны.
Ими можно либо заменять покемона на столе, когда выпадает 1, либо выкладывать каждые 6 ходов,
либо выкладывать по запросу. Их сила равна d6+B, где B — сила самого сильного покемона у игрока.

## Цель игры

Игра заканчивается когда угодно. Как вариант, можно ограничить время (игра затягивается!)
или поставить цель поймать особенного легендарного покемона.

## Покеболы и предметы

![](images/pokemoncg_items.jpg)

Какие бывают покеболы:

* покебол
* ультрабол (-2)
* мастербол (ловит всегда — один в игре)
* все остальные виды (-1)

Какие бывают предметы:

* +1 к атаке (один раз во время боя)
* +2 к поимке (на одного покемона)
* level up (один раз вне боя)
* прогнать покемона (во время боя; остаётся item)

## Дополнения

### Типы покемонов

Также можно задать каждому покемону тип. Можно ограничиться набором из трёх-пяти:
вода, огонь, трава, воздух. Или взять полный набор из игры — но тогда таблица силы будет сложнее.

Покемон, у которого тип сильнее того, что играет против него, получает +1 к силе во время боя.

В карты предметов добавляем «убрать тип»: он снимает бонус за тип в одном бою.

### Два и более игроков

Когда играют два и более игроков, они тащат покемонов по очереди. Они могут обмениваться
предметами вне боя. Если новый игрок вступает в середине игры, игроки должны
дать ему покемона и покебол из своих.

Игроки могут биться между собой. Они выставляют предметы, которые получит победитель.
Затем каждый побеждает самого сильного покемона противника. Первым ходит тот,
кому предложили биться, либо по договорённости.

### В поле

Можно не сидеть над колодой, а спрятать покемонов на улице. Возможно распределить их
тематически: например, по типам или размерам. С ними прячем и предметы. Возможно, по два:
покебол + предмет. Участники тогда сами их находят и дерутся, кидая кубики.
Целью можно поставить, например, поймать всех покемонов.

## Приложения

### Таблица сил покемона

Используем формулу из раздела «Ход»:

| в колоде | 1 | 2 | 3 | 4 | 5 | 6 |
|----------|---|---|---|---|---|---|
| 1—1      | 1 | 1 | 2 | 1 | 1 | 2 |
| 1—2      | 1 | 1 | 2 | 1 | 2 | 3 |
| 1—3      | 1 | 1 | 2 | 2 | 3 | 4 |
| 1—4      | 1 | 1 | 2 | 3 | 4 | 5 |
| 2—2      | 1 | 2 | 3 | 1 | 2 | 3 |
| 2—3      | 1 | 2 | 3 | 2 | 3 | 4 |
| 2—4      | 1 | 2 | 3 | 3 | 4 | 5 |
| 3—3      | 2 | 3 | 4 | 2 | 3 | 4 |
| 3—4      | 2 | 3 | 4 | 3 | 4 | 5 |
| 4—4      | 3 | 4 | 5 | 3 | 4 | 5 |

Для альтернативной формулы с A+2:

| в колоде | 1 | 2 | 3 | 4 | 5 | 6 |
|----------|---|---|---|---|---|---|
| 1—1      | 1 | 1 | 2 | 3 | 1 | 1 |
| 1—2      | 1 | 1 | 2 | 3 | 1 | 2 |
| 1—3      | 1 | 1 | 2 | 3 | 2 | 3 |
| 1—4      | 1 | 1 | 2 | 3 | 3 | 4 |
| 2—2      | 1 | 2 | 3 | 4 | 1 | 2 |
| 2—3      | 1 | 2 | 3 | 4 | 2 | 3 |
| 2—4      | 1 | 2 | 3 | 4 | 3 | 4 |
| 3—3      | 2 | 3 | 4 | 5 | 2 | 3 |
| 3—4      | 2 | 3 | 4 | 5 | 3 | 4 |
| 4—4      | 3 | 4 | 5 | 6 | 3 | 4 |

## Авторы

Все права на изображения и названия покемонов, а также само слово «покемон» принадлежат The Pokemon Company.

Остальное на этом сайте опубликовано под лицензией CC0. Автор идеи — Илья Зверев, с дополнениями других участников.
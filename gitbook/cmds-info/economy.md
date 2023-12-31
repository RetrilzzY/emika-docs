---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 💸 Команды экономики

***

{% hint style="info" %}
#### Подсказка&#x20;

**`<...>`** - обязательный аргумент\
**`[...]`** - необязательный аргумент

\
**`/команда`**- вызов через слэш(/)\
**`!команда`** - вызов через префикс (по умолчанию `!`, можно изменить при помощи _`/manage-prefix`_)\
**`команда`** - вызов через слэш и префикс
{% endhint %}

{% hint style="info" %}
Во многих командах есть такое понятие как aliases - это значит что команду можно вызвать разными названиями например: `!профиль !п`
{% endhint %}

<details>

<summary><code>!профиль</code> - посмотреть свой профиль или других участников</summary>

**Использование:**

`!профиль` или `!профиль <упоминание участника>`

**Возможные варианты вызова команды:** `!п` `!профайл`

</details>

<details>

<summary><code>!баланс</code>- просмотр баланса</summary>

**Использование:**

`!баланс`

**Возможные варианты вызова команды:** `!б`

</details>

<details>

<summary><code>!вывод</code> - вывести 🪙 из банка</summary>

**Использование:**

`!вывод <сумма>`

**Возможные варианты вызова команды:** `!в` `!вывести`

_Комиссия 2% + налог от богатства_

</details>

<details>

<summary><code>!депозит</code> - положить 🪙 в банк</summary>

**Использование:**

`!депозит <сумма>`

**Возможные варианты вызова команды:** `!д`

_Комиссия 4% + налог от богатства_

</details>

<details>

<summary><code>!доход</code> - зарплата с профессии</summary>

**Использование:**

`!доход`

**Возможные варианты вызова команды:** `!зарплата` `!деньга`

</details>

<details>

<summary><code>!казик</code> - КАЗИНО!</summary>

**Использование:**

`!казик <ставка> <место>`

Места: сумма x3 - \[1-12, 13-24, 25-36]; сумма x2 - \[1-18, 19-36, четное (четн), нечетное (нечетн)]

**Возможные варианты вызова команды:** `!к` `!казино`

**Пример:**&#x20;

`!казик 1000 13-24`

</details>

<details>

<summary><code>!лаки-джет</code> - Lucky Jet</summary>

**Использование:**

`!лаки-джет <ставка>`

**Возможные варианты вызова команды:** `!лк`

**Пример:**&#x20;

`!лаки-джет 50000`

</details>

<details>

<summary><code>!сфспин</code> - безопасная рулетка с профессиями</summary>

**Использование:**

`!сфспин`

**Возможные варианты вызова команды:** `!сфс`

_Можно использовать один раз в 30 минут_

</details>

<details>

<summary><code>!магазин</code> - посмотреть товары в магазине</summary>

**Использование:**

`!магазин`

**Возможные варианты вызова команды:** `!магазик` `!магаз`

</details>

<details>

<summary><code>!купить</code> - купить предмет из магазина</summary>

**Использование:**

`!купить <артикул предмета>`

**Пример:**&#x20;

`!купить 001`

</details>

<details>

<summary><code>!ограбить</code> - ограбить кого-нибудь</summary>

**Использование:**

`!ограбить <упоминание-участника>`

**Возможные варианты вызова команды:** `!грабануть` `!грабить` `!ограблить`

**Пример:**&#x20;

`!ограбить @neviz_`

_Можно использовать один раз в 30 минут_

</details>

<details>

<summary><code>!топ</code> - лидеры по количеству 🪙 на сервере</summary>

**Использование:**

`!топ`

**Возможные варианты вызова команды:** `!лидерборд` `!лидеры`

</details>

<details>

<summary><code>!глобал-топ</code> - лидеры по количеству 🪙 изо всех серверов</summary>

**Использование:**

`!глобал-топ`

**Возможные варианты вызова команды:** `!гтоп`

</details>

<details>

<summary><code>!перевести</code> - перевести деньги кому-нибудь</summary>

**Использование:**

`!перевести <упоминание пользователя> <сумма>`

**Возможные варианты вызова команды:** `!перевод`

**Пример:**&#x20;

`!перевести @retrilzzy 5000`

_Комиссия 10%_

</details>

<details>

<summary><code>!работать</code> - дополнительные 🪙</summary>

**Использование:**

`!работать`

**Возможные варианты вызова команды:** `!работа` `!пахать`

</details>

<details>

<summary><code>!серв-перевод</code> - перевести сумму на свой баланс в другом сервере</summary>

**Использование:**

`!серв-перевод <сумма> <id сервера>`

**Возможные варианты вызова команды:** `!серв-перевести`

**Пример:**&#x20;

`!серв-перевод 7777 123456789`

_Комиссия 30%_\
_Можно использовать один раз в 60 минут_

</details>

{% hint style="warning" %}
Для перевода на другой сервер надо чтоб были разрешены переводы между серверами [#economy-settings-upravlenie-modulem-ekonomiki](general.md#economy-settings-upravlenie-modulem-ekonomiki "mention"), а также у вас должен быть профиль на серверах
{% endhint %}

<details>

<summary><code>!рулетка</code>- рулетка с поинтами </summary>

**Использование:**

`!рулетка <бесплатная/платная>`

_Стоимость платной: 10,000,000 🪙_&#x20;

**Возможные варианты вызова команды:** `!р` `!крутилка` (<mark style="background-color:blue;">бесплатная</mark> можно заменить на <mark style="background-color:blue;">б</mark> и <mark style="background-color:purple;">платная</mark> на <mark style="background-color:purple;">п</mark>)

**Пример:**&#x20;

`!рулетка бесплатная`

</details>

<details>

<summary><code>!русская-рулетка</code>- русская рулетка один победитель</summary>

**Использование:**

`!русская-рулетка <сумма>`

**Возможные варианты вызова команды:** `!р-р`

**Пример:**&#x20;

`!русская-рулетка 4000`

</details>

<details>

<summary><code>!обменять</code>- обменик валют</summary>

**Использование:**

`!обменять <coin/s.point> <количество> <s.point/u.point>`&#x20;

**Толкование:** _обменять какое-то `количество`_ _`coin/s.point` в_ _**s.point/u.point**_

**Возможные варианты вызова команды:** `!обменник` `!обмен`



**Пример:**&#x20;

`!обменять coin 1000000 s.point`

**Толкование:** _обменять 100000 coin в s.point_

</details>

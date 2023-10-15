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

# 🛠 Команды модерации

***

{% hint style="info" %}
#### Подсказка&#x20;

**`<...>`** - обязательный аргумент\
**`[...]`** - необязательный аргумент

\
**`/команда`**- вызов через слэш(/)\
**`!команда`** - вызов через префикс (по умолчанию `!`, можно изменить при помощи _`/manage-prefix`_)\
`команда` - вызов через слэш и префикс
{% endhint %}

<details>

<summary><code>lock</code> - Блокирует отправку сообщений в канал</summary>

**Использование:**

`lock [#канал/идентификатор]`

**Пример:**&#x20;

`!lock #chat`

</details>

<details>

<summary><code>unlock</code> - Разблокирует канал</summary>

**Использование:**

`unlock [#канал/идентификатор]`

**Примеры:**&#x20;

`!unlock #чатик`

`!unlock 123456789`

</details>

<details>

<summary><code>clear</code> - Очищает сообщения в канале</summary>

**Использование:**

`clear <количество>`

**Пример:**&#x20;

`!clear 7`

</details>

<details>

<summary><code>mute</code> - Замьютить участника на сервере</summary>

**Использование:**

`mute <участник> <насколько минут> [причина]`

**Пример:**&#x20;

`!mute @Emika 10 проиграл все деньги в казике`

</details>

<details>

<summary><code>unmute</code> - Размьютить участника на сервере</summary>

**Использование:**

`unmute <участник>`

**Пример:**&#x20;

`!unmute @Emika`

</details>

{% hint style="warning" %}
Для использования команд`lock unlock clear mute unmute`необходима роль с разрешением **"Управление сообщениями"** или вы должны быть **администратором**
{% endhint %}

<details>

<summary><code>kick</code>- Исключает участника с сервера</summary>

**Использование:**

`kick <участник> [причина]`

**Пример:**&#x20;

`!kick @ds.mandar1n нубик`

</details>

{% hint style="warning" %}
Для использования команды `kick` необходима роль с разрешением **"Выгонять Участников"** или вы должны быть **администратором**
{% endhint %}

<details>

<summary><code>ban</code> - Забанить участника на сервере</summary>

**Использование:**

`ban <участник> [причина]`

**Пример:**&#x20;

`!ban @ozai1155 24.3`

</details>

<details>

<summary><code>unban</code> - Разбанить участника на сервере</summary>

**Использование:**

`unban <идентификатор>`

**Пример:**&#x20;

`!unban 1089857134323306526`

</details>

{% hint style="warning" %}
Для использования команды `ban unban` необходима роль с разрешением **"Банить Участников"** или вы должны быть **администратором**
{% endhint %}

<details>

<summary><code>role</code> - Добавить или удалить роль у участника</summary>

**Использование:**

`role <add/remove> <участник> <роль>`

**Пример:**&#x20;

`!role add @ReZero2 Задрот`

</details>

{% hint style="warning" %}
Для использования команды `role` необходима роль с разрешением **"Управлять ролями"** или вы должны быть **администратором**
{% endhint %}

<details>

<summary>!<code>nuke</code> - Уничтожает все сообщения в канале</summary>

**НЕ ИСПОЛЬЗОВАТЬ!**

</details>

{% hint style="warning" %}
Для использования команды nuke необходимо быть **администратором**
{% endhint %}

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

# 🌟 Основные команды

***

{% hint style="info" %}
**Подсказка**

**`<...>`** - обязательный аргумент\
**`[...]`** - необязательный аргумент

\
**`/команда`**- вызов через слэш(/)\
**`!команда`** - вызов через префикс (по умолчанию `!`, можно изменить при помощи _`/manage-prefix`_)\
**`команда`** - вызов через слэш и префикс
{% endhint %}

<details>

<summary><code>/manage-prefix</code> - Установите свой префикс для вашего сервера</summary>

**Пример:**

`/manage-prefix prefix: ?`

</details>

<details>

<summary><code>/economy-settings</code> - Управление модулем экономики</summary>

**Пример:**

`/economy-settings settings: перевод и принятие средств с других серверов action: разрешить`

</details>

<details>

<summary><code>/manage-modules</code> - Управление модулями бота</summary>

**Пример:**

`/manage-modules module: economy action: отключить`

</details>

{% hint style="warning" %}
Для использования команд`/manage-prefix /manage-modules /economy-settings` необходима роль с разрешением **"Управление сервером"** или вы должны быть **администратором**
{% endhint %}

<details>

<summary><code>/waifu-pics, /nekos-life, /waifu-im, /random-waifu, /gif</code> – Изображения/гифки в аниме-стиле</summary>

**Примеры:**

`/waifu-im tag: waifu tag2: uniform`

`/nekos-life tag: neko`

</details>

<details>

<summary><code>/image-search</code> – Поиск изображения по текстовому запросу</summary>

**Пример:**

`/image-search query: apple`

</details>

<details>

<summary><code>/magic-ball, /nekos-ball</code> – Один верный ответ на твой вопрос (но это не точно)</summary>

**Пример:**

`/magic-ball question: Это вопрос?`

</details>

<details>

<summary><code>/embed-pro</code> - Полезный инструмент для создания эмбед сообщений</summary>

**Пример:**

`/embed-pro title: Это эмбед description: Да, это так color: purple text: @Emika#2626`

</details>

<details>

<summary><code>/play, /stop</code> - Команды управление радио (по жанрам)</summary>

**Пример:**

`/play genre: lo-fi`

</details>

<details>

<summary><code>gpt</code> - Текстовый искусственный интеллект на движке gpt-3.5-turbo от OpenAI</summary>

**Использование:**

`gpt <промпт>`

**Примеры:**

`!gpt Привет кто ты?`

`/gpt prompt: Привет кто ты?`

</details>

<details>

<summary><code>img-dalle, img-sdxl, img-kandinsky</code> - ИИ для генерации изображений на движке Dall-E от OpenAI и SDXL от Stability AI</summary>

**Использование:**

`img-dalle <промпт>` | `img-sdxl <промпт>` | `img-kandinsky <промпт>`

**Примеры:**

`!img-sdxl breathtaking night street of Tokyo, cars, neon lights. award-winning, professional, highly detailed`

<img src="../.gitbook/assets/sdxl_ex (2).png" alt="SDXL_Output" data-size="original">

`/img-kandinsky prompt: A highly photorealistic image of a off road race track, complete with precise replicas of the world’s most iconic heavy noun, captured at the moment of a sharp turn, with smoke and sparks flying from under the wheels and the noun drifting around the bend. The image captures the excitement of the moment, with happy and noisy fans cheering and waving in the background. (The image is depicted at dusk, with the headlights)`

<img src="../.gitbook/assets/kandinsky_ex (1).png" alt="Kandinsky_Output" data-size="original">

</details>

<details>

<summary><code>user-info</code> - Узнать информацию о себе или участнике</summary>

**Использование:**

`user-info [упоминание участника]`

**Пример:**

`!user-info @Retrilzzy`

</details>

<details>

<summary><code>server-info</code> - Узнать информацию о сервере</summary>

**Пример:**\
`!server-info`

</details>

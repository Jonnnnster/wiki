---
order: 11.5
title: Подключение бота к Telegram Business через Notibot
---

#### **1\. Включение Business Mode в боте**

1. **Откройте BotFather** (@BotFather) в Telegram.

2. Выберите нужного бота (который подключен к @NotibotruBot).

3. Отправьте команду:

   ```
   /mybots  
   ```

4. Выберите бота --> **Bot Settings** --> **Business Mode**.

   ![](./podklyuchenie-k-telegram-business-cherez-notibot-2.jpeg){width=479px height=477px}

5. Включите переключатель **"Turn on"**.

   ![](./podklyuchenie-k-telegram-business-cherez-notibot-3.jpeg){width=545px height=188px}

#### **2\. Подключение бота к Telegram Business и настройки в Notibot**

1. **В Telegram:**

   -  Откройте **Настройки** --> **Telegram для бизнеса**.

      ![](./podklyuchenie-k-telegram-business-cherez-notibot-4.jpeg){width=594px height=1004px}

   -  Выберите **"Чат-боты"** --> **"Добавить бота"**.

      ![](./podklyuchenie-k-telegram-business-cherez-notibot-5.jpeg){width=591px height=1280px}

   -  Введите @username\_бота, который подключен к @NotibotruBot

      ![](./podklyuchenie-k-telegram-business-cherez-notibot-6.jpeg){width=591px height=1280px}

2. **В Notibot:**

   -  Переходим в бота, который подключен к @NotibotruBot и в **Telegram Business.**

   -  Отправляем команду в чат с ботом:

      ```
      /setcommands  
      ```

   -  В ответ укажите:

      -  **Ключевое слово** (например, ключ).

      -  **Текст на кнопке**

      -  **Ссылку на страницу, которая** должна быть открыта (например, [https://t.me/вашbot/aboutme?startapp=a_7XQyEHGLckfmodpcU4DTJg_lp](https://t.me/natalyshchurovabot/aboutme?startapp=a_6XQyEHGLckfmodpcU4DTJg_lp)).

         ![](./podklyuchenie-k-telegram-business-cherez-notibot.jpeg){width=546px height=307px}

   -  **Укажите текст сообщения для команды**

      ![](./podklyuchenie-k-telegram-business-cherez-notibot-7.jpeg){width=522px height=192px}

   -  **Можно отправить картинку, которая будет прикреплена к сообщению**

      ![](./podklyuchenie-k-telegram-business-cherez-notibot-8.jpeg){width=492px height=169px}

   -  **Выбрать закреплять сообщение или нет**

      ![](./podklyuchenie-k-telegram-business-cherez-notibot-9.jpeg){width=508px height=147px}

   -  **Команда успешно добавлена!**
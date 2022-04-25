# dChikitsa Telegram Bot

- To begin with simply put your Telegram Authorization Token into the [application.properties](https://github.com/dchikitsa-health/dChikitsaTelegramBot/blob/main/src/main/resources/application.properties) file.

- Integrate the Bot with DHP, and you can easily change the [Bot Class](https://github.com/dchikitsa-health/dChikitsaTelegramBot/blob/main/src/main/java/com/dchikitsa/dhp/service/Bot.java) and customise the behaviour.

## How to create Telegram Bot and receive Telegram Authorization Token

### Creating a new bot:

- Step 1. Enter @Botfather in the search tab and choose this bot.

![photo_2022-04-25_12-30-30](https://user-images.githubusercontent.com/82867130/165043316-fee61bb5-a83d-4a83-b7c1-e3c9d3f1a9bd.jpg)


- Step 2. Click “Start” to activate BotFather bot.

- Step 3. Choose or type the /newbot command and send it.

![photo_2022-04-25_12-30-07](https://user-images.githubusercontent.com/82867130/165044025-a3632f4c-fcc2-46ff-a3b7-6df5e02d11ad.jpg)


- Step 4. Choose a name for your bot — your subscribers will see it in the conversation. And choose a username for your bot — the bot can be found by its username in searches. Username must be unique and end with the word “bot.”

- Step 5. After you c
hoose a suitable name for your bot — the bot is created.

- Step 6. Copy Telegram Authorization Token into the [application.properties](https://github.com/dchikitsa-health/dChikitsaTelegramBot/blob/main/src/main/resources/application.properties) file.

![photo_2022-04-25_12-30-23](https://user-images.githubusercontent.com/82867130/165044299-ab702c74-35d0-4158-bd54-783841acad24.jpg)


### Creating a bot menu:

- Step 1: Choose /setcommand to create command list.

![photo_2022-04-25_13-03-19](https://user-images.githubusercontent.com/82867130/165044439-9aef55d6-9018-47b9-a299-47e174e1b242.jpg)

- Step 2: Use the given format to create the list.

![photo_2022-04-25_13-03-24](https://user-images.githubusercontent.com/82867130/165044583-8929f31c-d35f-4e92-bbc2-7b2728bfd246.jpg)


## How to run this code:

Run this command in the command line:
mvn spring-boot:run



*Tadaaa! your bot is created....*




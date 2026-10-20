<img src="media/banner.png" width="100%">

**[Русский](#русский) · [English](#english)**

> 🔒 Исходный код закрыт. В репозитории только описание бота.
> 🔒 Source code is private. This repo contains a showcase only.

---

## Русский

**Lumi** — большой бот для Discord-сообщества: экономика, игры, кланы, браки, модерация, верификация голосом, приватные комнаты, музыка и ивенты. Работает как связка из нескольких процессов (основной бот, музыка, комнаты, верификация) с общей базой MySQL.

### Экономика и магазин
- **Валюта.** Монеты и золото, банк, переводы, топы.
- **Магазин.** Роли, фоны профиля, личные роли на заказ.
- **Профиль.** Карточка рисуется через `canvas`: уровень, статистика, купленный фон.
- **Рефералы.** Награды выдаются по вехам: голосовая верификация, часы в войсе, две недели на сервере. Так платят только за живых людей.

### Игры и развлечения
- **Казино.** «Дракон» с множителями, сетка дверей, подземелье.
- **Дуэли, крестики-нолики, змейка, 2048.**
- **Мафия с ИИ-ведущим.** Бот озвучивает ход игры голосом (TTS), распознаёт речь игроков и следит за фолами.
- **Караоке-баттлы.** Бот записывает выступления в голосовом канале, подмешивает минусовку, выкладывает записи и проводит голосование.
- **Кланы.** Уровни, постройки, приглашения, цвета.
- **Браки и знакомства.** Анкеты с фото, история браков.

### Модерация и сервер
- **Голосовая верификация.** Бот общается с новичком голосом и анализирует живую речь (защита от саундпадов).
- **Наказания и автомодерация.** История наказаний, автомод ников, жалобы, тикеты помощи.
- **Наборы в стафф.** Отпуска модераторов, саппорта и ивентеров, статистика модераторов.
- **Приватные комнаты.** Аренда за монеты, срок действия, права владельца.
- **Журнал сервера.** Все события в одном канале.

### Музыка
Отдельный музыкальный бот: Яндекс Музыка, YouTube через прокси, UI на кнопках.

### Стек
Node.js 18+ · discord.js v14 · @discordjs/voice · MySQL · canvas · TTS · node-schedule.

---

## English

**Lumi** is a large all-in-one bot for a Discord community: economy, games, clans, marriages, moderation, voice verification, private rooms, music and events. It runs as several processes (main bot, music, rooms, verification) sharing one MySQL database.

### Economy & shop
- **Currency.** Coins and gold, a bank, transfers and leaderboards.
- **Shop.** Roles, profile backgrounds and custom personal roles.
- **Profile.** The card is rendered with `canvas`: level, stats and the purchased background.
- **Referrals.** Rewards are paid at milestones: voice verification, hours in voice, two weeks on the server. That way only real people are rewarded.

### Games & fun
- **Casino.** "Dragon" multipliers, a door grid and a dungeon.
- **Duels, tic-tac-toe, snake, 2048.**
- **Mafia with an AI host.** The bot narrates the game by voice (TTS), recognizes players' speech and tracks fouls.
- **Karaoke battles.** The bot records performances in a voice channel, mixes in the backing track, posts the recordings and runs a vote.
- **Clans.** Levels, buildings, invites and colors.
- **Marriages & dating.** Profiles with photos and a marriage history.

### Moderation & server
- **Voice verification.** The bot talks to newcomers by voice and analyzes live speech (anti-soundboard).
- **Punishments & automod.** Punishment history, nickname automod, reports and help tickets.
- **Staff management.** Staff recruitment, vacations for moderators, support and event staff, and moderator stats.
- **Private rooms.** Rented for coins, with expiry and owner permissions.
- **Server journal.** Every event logged in one channel.

### Music
A separate music bot: Yandex Music, YouTube via proxy, and a button-based UI.

### Stack
Node.js 18+ · discord.js v14 · @discordjs/voice · MySQL · canvas · TTS · node-schedule.

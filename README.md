# Emotion Wheel Add-on (PAYDAY 3)

Adds 28 dances to the PAYDAY 3 emote wheel.

Mod page: https://modworkshop.net/mod/59822

## EN

### What it does

You get 28 extra dances on the normal emote wheel. They're on extra pages, so your own emotes stay where they were. It works in multiplayer, but only teammates who also have the mod installed will see you dance.

### Install

Put the three files (`DanceEmotes_P.pak`, `DanceEmotes_P.ucas`, `DanceEmotes_P.utoc`) into:

```
Steam\steamapps\common\PAYDAY3\PAYDAY3\Content\Paks\~mods
```

If there's no `~mods` folder, just create it. To uninstall, delete the three files.

### How to use

Open the wheel with your usual emote key, then scroll the mouse wheel to flip pages. Page 1 is your normal emotes, and pages 2 to 6 are the dances. The page counter (`< 1/6 >`) shows where you are, and scrolling past the last page wraps back to the first. Pick a dance like any other emote.

### Compatibility

- The mod replaces three game files: the emote wheel widget (`WBP_UI_HUD_CircularCallWidget`), the emote list (`DA_PlayerEmoteDatabase`), and `Config/Windows/WindowsEngine.ini`. Any other mod that touches one of these will conflict.
- A game update that changes any of these files can break the mod until I update it.

### Credits

- This started from **The Emote Wheel Mod** (https://modworkshop.net/mod/45169). I ported it to the current game version and kept working on it.
- Most of the animations come from Fortnite, PUBG and POSTAL 4. They aren't mine.

## RU

### Что делает мод

Добавляет 28 танцев в стандартное колесо эмоций. Они лежат на отдельных страницах, так что ваши обычные эмоции остаются на месте. В мультиплеере тоже работает, но танцы видят только напарники, у которых стоит этот же мод.

### Установка

Положите три файла (`DanceEmotes_P.pak`, `DanceEmotes_P.ucas`, `DanceEmotes_P.utoc`) в папку:

```
Steam\steamapps\common\PAYDAY3\PAYDAY3\Content\Paks\~mods
```

Если папки `~mods` нет, создайте её. Чтобы удалить мод, просто удалите эти три файла.

### Как пользоваться

Откройте колесо своей обычной клавишей эмоций и листайте страницы колесом мыши. Первая страница — ваши обычные эмоции, со второй по шестую — танцы. Счётчик страниц (`< 1/6 >`) показывает, где вы сейчас, а после последней страницы список начинается сначала. Танец выбирается как любая другая эмоция.

### Совместимость

- Мод заменяет три файла игры: виджет колеса эмоций (`WBP_UI_HUD_CircularCallWidget`), список эмоций (`DA_PlayerEmoteDatabase`) и `Config/Windows/WindowsEngine.ini`. С другими модами, которые меняют эти же файлы, будет конфликт.
- Если обновление игры затронет какой-то из этих файлов, мод может сломаться, пока я его не обновлю.

### Благодарности

- Основа взята из **The Emote Wheel Mod** (https://modworkshop.net/mod/45169). Я перенёс его на текущую версию игры и доработал.
- Большинство анимаций взято из Fortnite, PUBG и POSTAL 4, они не мои.

## What's in this repo

- `PAYDAY3/` holds the mod files laid out the way the game expects (cooked assets, tags, config).
- `docs/` has the dance list and a few notes on how the wheel works.

Built `.pak/.ucas/.utoc` files aren't kept here. Grab them from the mod page.

MIT license, see `LICENSE`. That only covers my own work here, not the animations or music.

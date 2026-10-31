# How the wheel works

The dances live in the game's own emote wheel (`/Game/UI/Widgets/HUD/Chat/WBP_UI_HUD_CircularCallWidget`). I took the game's widget and added pages to it, because the stock wheel only fits your equipped emotes.

- Mouse wheel up/down flips pages and wraps around at the ends. There are 6 pages: your normal emotes, then 5 pages of dances.
- A text block under the wheel (`Text_DancePage`) shows `< page/6 >`.
- The wheel has 9 slots, but on dance pages I only use 6 of them (the top one, three going down the right side, and two on the left). The other 3 stay empty.
- The dance list is just one string inside the widget with all 28 emote paths separated by `;`, split at runtime. To add a dance you add its path there (and to the emote database, see below).
- When you pick a dance, the widget drops it into an emote loadout slot and starts it the normal way (`StartEmote`), so the game plays it like any other emote. Your own loadout gets saved first and put back after.

## Emote database

The game only plays emotes it knows about, so the mod also ships an edited copy of `/Game/DLCs/00217-Emotes/Gameplay/Data/DA_PlayerEmoteDatabase`. It's the stock list (19 emotes, including the two from the Western DLC) with my 28 dances added at the end, 47 total.

If a game update adds new emotes to this file, this copy needs updating, otherwise the new emotes will go missing while the mod is installed.

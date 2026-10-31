# Dance list

All 28 dances, in the order they show up on the wheel. Page 1 is your normal emotes, so the dances start on page 2. Each page has 6, and the last one has 4.

**Page 2**
- 2 Phut Phon
- Best Mates
- Billy Bounce
- Blinding Lights
- Boots 'N' Cats
- Crackdown

**Page 3**
- Dance Moves
- Distraction Dance
- Freestylin'
- Fresh
- Gangnam Style
- Hand Signals

**Page 4**
- Infinite Dab
- JayWalking
- Llama Bell
- Marsh Walk
- Nana Nana
- Neo's Crazy Night

**Page 5**
- Never Gonna
- Paws & Claws
- Pumpernickel
- Rambunctious
- Reanimated
- See Tinh

**Page 6**
- Swipe It
- The Robot
- Twerk Dance
- Zany

Every dance has music. The track is cut into short pieces (one per loop of the dance) that play while you're dancing.

## Where the files are

Everything for a dance is under `PAYDAY3/Content/Mods/DanceEmotes/` and named after the dance, e.g. for Gangnam Style:

- `Emotes/DA_Emote_NEWv2_Gangnam_Style` - the emote itself (name, icon, animations)
- `Collections/DA_DanceCol_Gangnam_Style` - animation set
- `Montages/AM_Dance_Gangnam_Style` and `AM_DancePreview_Gangnam_Style` - in-game and menu preview montages
- `UI/Icons/T_UI_Emote_DM_Gangnam_Style` (+ `_Sprite`) - wheel icon
- `Audio/Gangnam_Style/` - the music pieces (`SW_*`) and their spawn blueprints (`BP_Music_SW_*`, `DA_MusicSpawn_SW_*`)

All the music shares one attenuation setting, `Audio/ATT_DanceMusic`.

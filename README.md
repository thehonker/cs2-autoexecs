# cs2-autoexecs

goos's CS2 autoexec setup. Themed config files loaded by a single dispatcher.

## Structure

```
cfg/
  autoexec.cfg      # Dispatcher — execs everything below
  goos/
    binds.cfg       # Core gameplay binds (movement, weapons, menus)
    crosshair.cfg   # Crosshair cvars
    settings.cfg    # Viewmodel, mouse, HUD, radar, network, misc
    shitpost.cfg    # All say binds and chat cycles
    dick.cfg        # 47-stage dick typewriter (= / -)
    faces.cfg       # 209 kaomoji cycle (F2)
```

## Install

Copy `cfg/` contents into your CS2 `game/csgo/cfg/` directory. The game auto-runs `autoexec.cfg` on launch.

## Keybind Reference

### Gameplay (`binds.cfg`)

| Key | Action |
|---|---|
| W A S D | Move |
| SPACE / MWHEELUP / MWHEELDOWN | Jump |
| SHIFT | Duck |
| CTRL | Sprint |
| MOUSE1 | Attack |
| MOUSE2 | Attack 2 |
| MOUSE3 | Player ping |
| MOUSE4 | Quick-switch (lastinv) |
| Q | Lastinv |
| R | Reload |
| E | Use |
| 1-5 | Weapon slots 1-5 |
| 6 | Slot 9 |
| B | Slot 5 |
| C | Slot 10 |
| F | Slot 7 |
| G | Slot 8 |
| V | Slot 6 |
| X | Slot 12 |
| N | Drop |
| M | Buymenu |
| . | Buy ammo 2 |
| Y | Chat (team) |
| ` | Toggle console |
| , | Team menu |
| TAB | Scores |
| F3 | Switch hands |
| F4 | Autobuy |
| F11 | Clutch mode toggle |
| F14 | Look at weapon |
| F16 | Voice record |

### Crosshair (`crosshair.cfg`)

Style 2, size 8, gap -0.8, thickness 1, magenta (255/0/255), no dot, no outline. Sniper width 2.

### Settings (`settings.cfg`)

Sensitivity 1.0, raw input, viewmodel FOV 60, radar centered off, HUD scale 0.7, rate 196608.

### Shitpost (`shitpost.cfg`)

#### Static binds

| Key | Says |
|---|---|
| H | you sound upset |
| I | ¯\\_(ツ)_/¯ |
| J | i saw that blood |
| O | !r |
| P | you talk a lot of shit for someone within cumshot distance |
| ; | y u no peek |
| / | ༼◯ل͟◯༽COCAINE༼◯ل͟◯༽ |
| F6 | ヽ( ｡ ヮﾟ)ノ |
| F7 | Snip alias (lenny → scissors on release) |
| U | ヽ( ｡ ヮﾟ)ノ ︻デ 一 |

#### Cycle aliases

Each alias can be invoked from console (e.g. `scout` to fire the current entry) or bound to a key.

#### Cycle keybinds

| Key | Alias |
|---|---|
| K | `scout` |
| L | `roast` |
| [ | `dismiss` |
| ] | `counter` |
| \\ | `unread` |
| ' | `compliment` |
| 7 | `cope` |
| 8 | `accuse` |
| 9 | `gg` |
| 0 | `brand` |
| CAPSLOCK | `honk` |
| F12 | `shot` (also takes screenshot) |

##### `scout` — scout complaints (K)

| Alias | Says |
|---|---|
| `scout1` | scout is love, scout is life, scout is 1700$ of pure strife |
| `scout2` | i hate my fucking sniper rifle its so stupid |
| `scout3` | scout more like scoutless |
| `scout4` | 1700 dollars and you still miss |
| `scout5` | the ssg is for people with skill |
| `scout6` | scout is a poverty awp |

##### `roast` — devastation (L)

| Alias | Says |
|---|---|
| `roast1` | log off |
| `roast2` | 13-3 when |
| `roast3` | difference: skill |
| `roast4` | you have negative kills |
| `roast5` | ｇｏｏｓ diff |
| `roast6` | 14 rounds and you still haven't won one |

##### `dismiss` — quick reactions ([)

| Alias | Says |
|---|---|
| `dismiss1` | skill issue |
| `dismiss2` | 1 |
| `dismiss3` | bro. |
| `dismiss4` | ight |
| `dismiss5` | who asked |
| `dismiss6` | not this again |
| `dismiss7` | here we go |
| `dismiss8` | cope harder |

##### `counter` — counter-reactions (])

| Alias | Says |
|---|---|
| `counter1` | reported. |
| `counter2` | ok |
| `counter3` | that's crazy |
| `counter4` | sure buddy |
| `counter5` | 0/10 |
| `counter6` | bro thinks he's him |

##### `unread` — not reading that (\\)

| Alias | Says |
|---|---|
| `unread1` | i'm not reading all that. i'm not reading all that. i'm not reading all that. |
| `unread2` | i didn't read that but i'm sure it was wrong |
| `unread3` | tl;dr but i disagree |
| `unread4` | you wrote a whole essay and still lost the argument |
| `unread5` | i see you typed a lot so i'll just say no |
| `unread6` | paragraph warriors never win |

##### `compliment` — nice things (')

| Alias | Says |
|---|---|
| `compliment1` | nice |
| `compliment2` | nt |
| `compliment3` | good effort |
| `compliment4` | genuine play |
| `compliment5` | you actually cooked that round |
| `compliment6` | respect |

##### `cope` — bad team energy (7)

| Alias | Says |
|---|---|
| `cope1` | my team is so bad |
| `cope2` | 5stack btw |
| `cope3` | 4v5 btw |
| `cope4` | i'm carrying so hard my back hurts |
| `cope5` | how are we losing to these bots |
| `cope6` | my teammates are playing a different game |

##### `accuse` — accusations (8)

| Alias | Says |
|---|---|
| `accuse1` | that was not luck that was skill (mine) |
| `accuse2` | are you cheating or are you just like this |
| `accuse3` | whiff |
| `accuse4` | you're not good you're just lucky |
| `accuse5` | smurfing is a cry for help |
| `accuse6` | i've seen aimbots with more personality |

##### `gg` — endgame (9)

| Alias | Says |
|---|---|
| `gg1` | ｇｇ ｗｐ |
| `gg2` | gg no re |
| `gg3` | easy game easy life |
| `gg4` | that was rough for you |
| `gg5` | uninstall when |
| `gg6` | see you never |

##### `brand` — goos name drops (0)

| Alias | Says |
|---|---|
| `brand1` | ｇｏｏｓ is typing... |
| `brand2` | ｇｏｏｓ has entered the chat |
| `brand3` | ｇｏｏｓ was here |
| `brand4` | ｇｏｏｓ diff |
| `brand5` | ｇｏｏｓ gaming |
| `brand6` | ｇｏｏｓ approved |

##### `honk` — loud honkers (CAPSLOCK)

| Alias | Says |
|---|---|
| `honk1` | VERY NORMAL THING TO SAY, CALL A FAMILY MEMEMBER AND READ WHAT YOU TYPED OUT LOUD TO THEM WHEN YOU GET THE CHANCE |
| `honk2` | I AM GOING TO SAY THE H WORD |
| `honk3` | AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA |
| `honk4` | HELLO POLICE? YES THIS MAN IS BAD AT COUNTER STRIKE |
| `honk5` | I'D LIKE TO FILE A POLICE REPORT FOR THE CRIME OF BEING DOGSHIT AT THIS GAME |
| `honk6` | I AM HONKING AT YOU THROUGH THE SCREEN CAN YOU FEEL IT |

##### `shot` — screenshot + raunchy (F12)

Each press takes a screenshot (`jpeg`) then says the next entry.

| Alias | Says |
|---|---|
| `shot1` | that's what she said |
| `shot2` | ( . Y . ) |
| `shot3` | i'd hit that |
| `shot4` | screenshot or it didn't happen |
| `shot5` | caught in 4k |
| `shot6` | this one's going on the fridge |

#### Ouch escalation (control layer)

| Key | Says |
|---|---|
| F8 | ｇｏｏｓ |
| F9 | ouch ouch ouch |
| F10 | ouch ×10 |

### Dick typewriter (`dick.cfg`)

| Key | Action |
|---|---|
| = | Grow (8D → 8==============================================D) |
| - | Shrink |

47 stages, max 48 chars (chat box limit).

### Faces (`faces.cfg`)

| Key | Action |
|---|---|
| F2 | Cycle through 209 kaomoji |

## Keyboard

Designed for the [gamebad MK3](https://github.com/thehonker/gamebad) custom ZMK keyboard. F1-F12 are on a control layer (hold MO(CTRL) in bottom-right). F14-F16 are direct-access on the bottom row.

![ZORK I](zork1-logo.png)

# Zork I — Instruction Manual

*Infocom, 1987. Transcribed from the original printed manual.*

> If you've never played Infocom's interactive fiction before, you should read this entire instruction manual. If you're an experienced Infocom game player, you may only want to read **Section I: About Zork I**.

## Table of Contents

**Before You Begin**

- [Playing the Caldwell Z-Machine for Browsers Edition](#playing-the-caldwell-z-machine-for-browsers-edition) — The screen · Function keys · Saving · The map · Hints

**Section I: About Zork I**

- [Preface to the Story](#preface-to-the-story)
- [Hints](#hints)
- [Sample Transcript and Map](#sample-transcript-and-map)
- [About the Authors](#about-the-authors)

**Section II: About Infocom's Interactive Fiction**

- [An Overview: What Is Interactive Fiction?](#an-overview-what-is-interactive-fiction)
- [Starting and Stopping](#starting-and-stopping) — "Booting up" · Saving and restoring · Quitting and restarting
- [Communicating with Infocom's Interactive Fiction](#communicating-with-infocoms-interactive-fiction) — Basic sentences · Complex sentences · Talking to characters in the story
- [Special Commands](#special-commands)
- [Tips for Novices](#tips-for-novices) — Eleven useful pointers about interactive fiction
- [Common Complaints](#common-complaints)
- [We're Never Satisfied](#were-never-satisfied)
- [If You Have Technical Problems](#if-you-have-technical-problems)
- [Copyright and Warranty Information](#copyright-and-warranty-information)
- [Quick Reference Guide](#quick-reference-guide) — The most important things to know about interactive fiction

**This Edition's Extras**

- [Enhanced Language Features](#enhanced-language-features) — Everyday English, GO TO, questions about the world, typing help, and Infocom's own slips mended (optional)

**Appendix**

- [Every Wording the Enhanced Language Layer Understands](#appendix-every-wording-the-enhanced-language-layer-understands)

---

# Before You Begin: Playing in Your Browser

## Playing the Caldwell Z-Machine for Browsers Edition

This edition of *Zork I* is Infocom's original game file, unchanged, running in your web browser on the Caldwell Z-Machine for Browsers. There is nothing to install. Open **zork-i-game.html** in any modern browser and the story begins. Everything this manual says about talking to the game still applies. The parts about disks, reference cards, printers and Infocom's old addresses and phone numbers are kept for history only.

### The screen

- **Status line**: the room you are in, your score and the number of moves you have made.
- **Story window**: everything the game has said so far.
- **Button panel** (hidden at first; press `F4` to show it): commands that make sense where you are right now, built from the game's own rooms and objects. Click one instead of typing. Cyan buttons move you (including **Go back**, which takes you back to the place you just came from when one step gets you there), green ones act on things around you, orange ones use what you are carrying, and red ones fight or answer "yes". Gray ones are general commands such as LOOK AROUND and INVENTORY. The buttons only offer what you can plainly see and carry; buttons that would solve a puzzle (the right magic word, the trick with an object) appear only with hints turned on, and buttons for directions only with the map on.
- **Function-key bar**: the keys listed below, and on the right the time you have spent playing this game (hours, minutes and seconds, with days in front once a day has passed). It counts only while the game is open and in view, carries on where it left off when you come back, and goes back to zero when you restart or quit. You can hide it in Settings (F2). While a transcript is being recorded (SCRIPT), a red **• REC** pulses next to the time.

### Typing

Type at the prompt (`>`) and press Enter, in the game's own style: a verb and a thing (TAKE LAMP, OPEN THE MAILBOX, READ THE LEAFLET), compass directions (NORTH, or just N), and so on. [Communicating with Infocom's Interactive Fiction](#communicating-with-infocoms-interactive-fiction) explains everything the game understands. The Up and Down arrow keys bring back commands you typed before. Shift+Up and Shift+Down, Page Up and Page Down, or the mouse wheel scroll back through the story.

This edition can also understand everyday English, such as WHERE AM I?, if you want it to: see [Enhanced Language Features](#enhanced-language-features), near the end of this manual.

### The function keys

The bar along the bottom of the screen shows five keys. You can press them, or click (or tap) their names on the bar. Each of these, and every menu item, also has a command you can type instead, shown in the menu and in the tables below.

| Key | What it does |
|---|---|
| `F1` | **Help**: a short guide, with a link that opens this manual. Typing HELP does the same. |
| `F2` | **Settings**: switches for how the game looks and which extras are on. Press the number to flip one. Typing SETTINGS does the same. |
| `F3` | **Menu**: a numbered list of the things you can ask for. Press the number, or click the line. Typing MENU does the same. |
| `F4` | **Buttons On / Buttons Off**: shows whether the command buttons under the story are showing; press it to bring them up or hide them again. They start hidden, so the game begins the way Infocom made it: just you and the prompt. With them hidden, the story fills the space. When command buttons are switched off in Settings, F4 is gone from the bar and does nothing. |
| `F5` | **About**: the edition, copyright and credits, and the game's own release number. Typing ABOUT does the same. |

**The menu (F3)**

| Item | What it does |
|---|---|
| **1. Show score** | Your score and rank, without using a move. You can also type SCORE. |
| **2. Show map** | The places you have been (see [The map](#the-map)). You can also type MAP. |
| **3. Show hints** | Hints about the places you have been (see [Getting hints](#getting-hints)). You can also type HINT. |
| **4. Undo last move** | Takes back your last move, after asking first (No is the default, so a stray key press changes nothing). Do it again to go back further, up to 100 moves; the last 20 are kept even if you close or reload the page. Only real moves count: commands such as SCORE, HELP or MENU, questions such as WHERE AM I?, or a word the game didn't understand are never what UNDO takes back; they disappear from the story along with the move. Turning the enhanced language layer on or off makes no difference to UNDO. You can also type UNDO. |
| **5. Restart game** | Starts the story over from the beginning, after asking first (No is the default). Your current game is lost; the map, the hints you have read and the time played start again from nothing, and the command buttons go back to hidden (`F4` shows them). Your SAVE position is kept. You can also type RESTART. |

**The settings (F2)**

| Setting | What it changes |
|---|---|
| **1. Screen color** | The classic blue screen, or a plain black one. |
| **2. Border** | The animated border around the screen, or none, so the game fills the whole window. |
| **3. Command buttons** | Off takes the buttons away completely, along with F4, for players who would rather type everything themselves. On brings them back. (With the map off, the buttons don't offer directions; with hints off, they don't offer puzzle solutions.) |
| **4. Map** | Turns the map on or off. MAP ON and MAP OFF do the same. Off is for players who keep their own map: it also turns off everything the edition works out from its notes on where you have been and what you have seen (EXITS, WHERE HAVE I BEEN?, GO BACK, HOW DO I GET TO …?, GO TO, WHERE IS …?, WHAT DID I DROP?, WHERE ARE MY TREASURES? and the direction buttons). Those then say *"That isn't available because the map is turned off."* The notes are still kept, so turning the map back on picks up as if it had never been off. |
| **5. Hints** | Turns hints on or off. Hints are **off when you first start**, so the game never gives anything away unless you ask it to. Off also turns off GIVE ME A HINT, I'M STUCK, WHAT CAN I DO HERE? and puzzle questions, which then say *"Hints aren't available because hints are turned off."*, and the command buttons that would solve a puzzle. |
| **6. Undo** | Turns undo on or off. |
| **7. Time played** | Shows or hides the time played in the bottom right corner. Hidden, it still keeps count, so turning it back on shows the true time. |
| **8. Enhanced language** | Turns this edition's optional [Enhanced Language Features](#enhanced-language-features) on or off. Off leaves only the original game's own parser, exactly as Infocom wrote it. |
| **9. Reset to defaults** | Puts every setting back to how the game first starts: blue screen, animated border, command buttons allowed but hidden (`F4` shows them), hints off, and map, undo, time played and enhanced language on. |

Settings are kept for each game separately, and a restart doesn't change them. Something you switch off stays in the menu, dimmed, and if you type its command the game tells you it is turned off and how to turn it back on.

On a narrow window some labels are left off the bar to save room (About first, then Buttons), but every key still works.

### Saving your place

- Your game is saved automatically after every move. Close the page and open it again, and you carry on where you left off.
- SAVE puts this moment aside as a bookmark, and RESTORE goes back to it, as the original game's SAVE and RESTORE did with a disk. Use it before something risky: if it goes badly, RESTORE and try another way. There is one bookmark, so SAVE again replaces it. The map and everything this edition remembers come back with it.
- Saved games are kept in this browser on this computer. Each Zork game keeps its own, separate from the others. Clearing your browser's site data erases them.
- The story window keeps the last 3,000 lines (several hundred moves), where you can scroll back through them, and the same 3,000 lines come back when you return to the game. On the original computers, text that scrolled off the top of the screen was gone for good. To keep a whole session as a file, see [Transcripts](#transcripts-script-and-unscript).

### Transcripts: SCRIPT and UNSCRIPT

On the original computers, SCRIPT sent the story to your printer as you played, and UNSCRIPT stopped it. Here, they make a text file instead:

- **SCRIPT** starts recording a transcript: every command you type and every reply, exactly as the story window shows them. While it records, a red **• REC** pulses in the bottom bar, next to the time played (just **REC** on a phone).
- **UNSCRIPT** stops recording and saves the transcript as a text file, named with the date and time, such as *Zork I transcript 2026-11-12_13-29.txt*. Your browser puts it wherever it keeps downloads.
- **Click REC** to see how long it has been recording, or to stop and save straight away.
- **It keeps recording** if you close the page and come back later, along with the rest of your game. UNDO, SAVE and RESTORE don't stop it.
- **Starting a new game stops it.** If you RESTART or QUIT while recording, you are asked whether to save the transcript first. The new game always starts with recording off.
- **It holds about 1 MB of text**, roughly 3,000 moves; a whole game of *Zork I* is a few hundred. You are warned when it is nearly full, and when it is full it stops recording, keeps everything so far, and waits for UNSCRIPT.
- **If your browser can't save a file** (for example, when the game is shown inside another web page), UNSCRIPT shows the transcript in a window instead, with a **Copy** button so you can paste it wherever you like.

### The map

Choose Map from the menu (F3, then 2) or type MAP to open the map. It is built from the moves you have actually made, so its list of places holds only rooms you have been in.

- **The top** names the room you are in. Under **Directions** it lists each way out and where it leads, for example *East or out → Behind House*. When two directions lead to the same place, they share a line, and either word works. A direction the game hasn't shown you yet says *not explored yet*. For ordinary exits, the destination comes straight from the game itself, so it can name a room you haven't walked to.
- **Places you have been** lists every room you have explored. Your own room is marked *(you are here)*. Click a place, or move to it with the arrow keys and press Enter, to see its directions and the way there from where you are now, such as *Way there from Kitchen: east, south*. Each route is tried out on a copy of your game before it is shown. If there is no sure way there, for example through a door that closed behind you, the map says so. The map never moves you; you walk the route yourself. Backspace takes you back to your own room.
- Rooms that share a name, such as the rooms of a maze, are numbered (*Maze 1*, *Maze 2* …). A room you were only ever in without a light appears as *Dark place*. A direction that has taken you to different places is marked *varies*. Special trips, such as one made with a magic word, are listed by the command that made them.
- When the list is longer than the screen, it scrolls: use the scroll bar on the right, the mouse wheel, or the arrow, Page Up, Page Down, Home and End keys. The top part stays in place.
- You can turn the map off in Settings (F2), or by typing MAP OFF. Typing MAP ON turns it back on.
- The map is saved with your game and stays in step with UNDO, SAVE and RESTORE.

Press Esc or click OK to close the map.

### Getting hints

Hints are off when you first start, so nothing is given away unless you want it. To use them, turn **Hints** on in Settings (F2, then 5).

Stuck? Type HINT, or choose Hint from the menu (F3, then 3). A pop-up lists questions about the places you have been, with questions about the room you are in at the top. Pick one, and its hints appear one at a time, from a gentle nudge to the full answer. Press Enter for the next hint, Backspace to go back to the questions, and Esc to close. A long list or a long answer scrolls, the same way as the map. These hints were written for this edition, since the game files themselves have none. Each game keeps track of the hints you have read, and starting a new game clears them.

# Section I: About Zork I

## Preface to the Story

Welcome to *Zork!* You are about to experience a classic interactive fantasy, set in a magical universe. *The Zork Trilogy* is set in the ruins of an ancient empire lying far underground. You, a dauntless treasure-hunter, are venturing into this dangerous land in search of wealth and adventure. Because each part of the *Zork* saga is a completely independent story, you can play them in any order. However, because *Zork I* is the least difficult, it is usually the best place to begin.

Many strange tales have been told of the fabulous treasure, exotic creatures, and diabolical puzzles in the Great Underground Empire. As an aspiring adventurer, you will undoubtedly want to locate these treasures and deposit them in your trophy case. You'd better equip yourself with a source of light (for the caverns are dark) and weapons (for some of the inhabitants are unfriendly — especially the thief, a skilled pickpocket and ruthless opponent).

## Hints

Your version of *Zork I* includes hints right on the disk! If you ever get stuck, just type `HINT` and press the RETURN (or ENTER) key. Then follow the instructions on your screen.

## Sample Transcript and Map

This transcript is not from *Zork*, but it does show most of the usual things you can do in the story. It contains several simple puzzles and their solutions, and it will give you a good idea of how interactive fiction works. The player's sentences appear in capital letters after each prompt (`>`). The map represents the terrain in the sample transcript.

![Map of the sample transcript: Monster's Lair, Orange Grove, Carpentry Shop, Foreman's Office, Lumber Yard and Moss-Lined Tunnel](zork1-sample-map.png)

```
>APPLY THE BRAKES
The Frobozz Magic Go-Cart coasts to a stop.

Moss-Lined Tunnel, in the Go-Cart
This is a long east-west tunnel whose walls are covered with green and
yellow mosses.
There is a jewel-studded monkey wrench here. (outside the Go-Cart)
A bent and rusted monkey wrench is lying here. (outside the Go-Cart)

>TAKE THE WRENCH
Which wrench do you mean, the jeweled monkey wrench or the rusty monkey
wrench?

>JEWELED
You can't reach it from inside the Go-Cart.

>WEST
You're not going anywhere until you stand up.

>GET OUT OF THE GO-CART
You are on your own feet again.

>TAKE THE JEWELED WRENCH
Taken.

>WEST
Lumber Yard
This is a huge room lined with metal shelves. There are exits to the
east, northeast, and west.
There is a small cardboard box here.
Piled on one of the shelves is a supply of lumber.

>TAKE THE BOX AND THE LUMBER
small cardboard box: Taken.
supply of lumber: Your load is too heavy.

>INVENTORY
You are carrying:
  a lamp (providing light)
  a glass jar
  The glass jar contains:
    a quantity of pomegranate juice
  a jeweled monkey wrench
  a dart gun
  a small cardboard box

>DROP THE DART GUN
Dropped.

>TAKE THE LUMBER
Taken.

>LOOK INSIDE THE BOX
The small cardboard box is closed.

>OPEN IT
Opening the small cardboard box reveals a bunch of two-inch nails.

>EXAMINE THE LUMBER
It consists of two rectangular pieces of wood, about ten feet long, and
perhaps a dozen shorter dowel-shaped pieces.

>WALK NORTHEAST
Foreman's Office
This is the office of the lumber yard foreman. The only exit is to the
southwest.

>SW
Lumber Yard
There is a dart gun here.

>WALK WEST
Carpentry Shop
You are in a room furnished with wooden shelves, cabinets, mantels and
moldings, all gracefully carved out of fine wood. An array of precision
tools adorn the walls. The only exit is south....unless you want to
count the opening in the roof. A carpenter gnome is sitting here,
twiddling his thumbs.

>UP
The opening is too high to reach.

>GNOME, BUILD A LADDER
"I'd be glad to, but not for free!"

>GIVE THE JEWELED MONKEY WRENCH TO THE GNOME
The gnome examines the jeweled monkey wrench carefully. "Thank you," he
exclaims, adding it to his collection of tools.

>GNOME, BUILD A LADDER
"Oh, yes, your ladder. Unfortunately, I have no lumber."

>GIVE THE LUMBER TO THE GNOME
The gnome accepts the supply of lumber.

>GNOME, BUILD LADDER
"Darn it! I'm fresh out of nails."

>GIVE NAILS
(to the gnome)
The gnome accepts the bunch of nails.

>GIVE THE LAMP TO THE GNOME
The gnome attempts to build a beautiful set of kitchen cabinets out of
the lamp. Finally, he gives up and hands it back to you.

>GNOME, BUILD LADDER
The gnome grumbles but constructs a handsome wooden ladder. He admires
his handiwork, and hands you the ladder.

>PUT THE LADER THROUGH THE HOLE
I don't know the word "lader".

>OOPS LADDER
The ladder is now resting against the rim of the hole.

>UP
You're carrying too much to climb a ladder.

>I
You are carrying:
  a lamp (providing light)
  a glass jar
  The glass jar contains:
    a quantity of pomegranate juice
  a small cardboard box

>DROP ALL BUT THE LAMP
glass jar: Dropped.
small cardboard box: Dropped.

>LOOK
Carpentry Shop
You are in a room furnished with wooden shelves, cabinets, mantels and
moldings, all gracefully carved out of fine wood. An array of precision
tools adorn the walls. The only exit is south....unless you want to
count the handsome wooden ladder leading through a hole in the roof.
A carpenter gnome is sitting here, twiddling his thumbs.
There is a glass jar here.
The glass jar contains:
  a quantity of pomegranate juice.
There is a small cardboard box here.

>UP
Monster's Lair
This is the den of the dreaded Seven-Headed Snow Monster of Snurth. It
is quite chilly in here, and ice covers the floor and walls. A ladder
protrudes from a hole in the ground, and sunlight comes from the cave
entrance to the east.
The Snow Monster, bellowing loudly, blocks the eastern exit.

>DOWN.SOUTH.TAKE DART GUN.WEST.UP
Carpentry Shop
A carpenter gnome is sitting here, twiddling his thumbs.
There is a glass jar here.
The glass jar contains:
  a quantity of pomegranate juice.
There is a small cardboard box here.

Lumber Yard
There is a dart gun here.

Taken.

Carpenty Shop
A carpenter gnome is sitting here, twiddling his thumbs.
There is a glass jar here.
The glass jar contains:
  a quantity of pomegranate juice.
There is a small cardboard box here.

Monster's Lair
The Snow Monster, bellowing loudly, blocks the eastern exit.

>SHOOT MONSTER
What do you want to shoot the monster with?

>DART GUN
The Snow Monster clutches at the dart, and then keels over. His body
vanishes in a cloud of acrid black smoke.

>EAST
Orange Grove
A path leads northeast through this small grove of orange trees. A dark
cave lies to the west. A sign is posted near the grove.

>READ THE SIGN
"Warning! These are poisonous oranges, not meant for human
consumption. — Farmer Bozbar"

>EAT AN ORANGE
Aaarrrrr! It burns your tongue and your throat!

    *** You have died ***

A forest sprite appears, looking concerned. "You've done it again,"
says the sprite, with a mixture of sympathy and disgust. "I'll give you
only one more chance." She sprinkles some fairy dust on you...

Wooden Bridge
There is a lamp here.

>LOOK
Wooden Bridge
You are on a sturdy bridge leading northeast to southwest. The river
below flows quickly amongst pointy rocks. There is a lamp here.
```

## About the Authors

**Dave Lebling** was born in Washington, D.C., in a hospital that was torn down soon thereafter. He grew up in suburban Maryland. He attended the Massachusetts Institute of Technology, and worked at MIT's Laboratory for Computer Science, where he developed an interest in computer entertainments. He co-authored the original mainframe *Zork* as well as *The Zork Trilogy* and *Enchanter*, and wrote *Starcross*, *Suspect*, *Spellbreaker*, and *The Lurking Horror* on his own. He is married and lives in a suburb of Boston. His long-range ambition is to have a library with room enough for all his books to be taken out of storage. His short-range ambition is to keep the squirrels out of his birdseed.

**Marc Blank**, a graduate of MIT and the Albert Einstein College of Medicine, is one of the original founders of Infocom. He co-authored the original mainframe version of *Zork* at MIT, and went on to become one of the pioneers in the field of interactive fiction. At Infocom, he co-authored *The Zork Trilogy* and *Enchanter*, and was sole author of *Deadline*, the first interactive mystery. Marc also wrote *Border Zone*, Infocom's first tale of intrigue. Marc now lives with his wife, Cezanne, and child, Puer, in Agua Dulce, California. His mother still wishes that he would practice medicine, preferably on the East Coast.

---

# Section II: About Infocom's Interactive Fiction

## An Overview: What Is Interactive Fiction?

Interactive fiction is a story in which *you* are the main character. Your own thinking and imagination determine the actions of that character and guide the story from start to finish.

Each work of interactive fiction, such as the three *Zork* games, presents you with a series of locations, items, characters, and events. You can interact with these in a variety of ways.

To move from place to place, type the direction you want to go. When you begin playing, it's a good idea to become familiar with your surroundings by exploring every location and reading each description carefully. (You may notice that *Zork* occasionally refers to a location as a "room", even if you are outdoors.) As you explore the Empire, it is helpful to make a map of the geography.

An important element of interactive fiction is puzzle-solving. You should think of a locked door or a ferocious beast not as a permanent obstacle, but merely as a puzzle to be tackled. Solving puzzles will frequently involve bringing a certain item with you, and then using it in the proper way.

In *Zork*, time passes only in response to your input. You might imagine a clock that ticks once for each sentence you type, and the story progresses only at each tick. Nothing happens until you type a sentence and press the RETURN (or ENTER) key, so you can plan your turns as slowly and carefully as you want.

To measure your progress, *Zork* keeps track of your score. You'll get points for solving puzzles, acquiring treasures, performing certain actions, and visiting certain locations. You will also get points for putting treasures into the trophy case. There may be a penalty for getting "killed."

## Starting and Stopping

### Starting the story ("booting up")

To load *Zork*, follow the instructions on the Reference Card in your game package.

Following the copyright notice and the release number of the game, you will see a description of the place where the story begins. Then you will see the prompt (`>`), indicating that *Zork* is ready for your first input.

Here are a few inputs for you to try at the first several prompts. After typing each input, don't forget to press the RETURN (or ENTER) key:

```
>LOOK AT THE MAILBOX
>OPEN THE MAILBOX
>INVENTORY
>LOOK AT THE HOUSE
```

### Saving and restoring

It will probably take you many days to complete *Zork*. Using the `SAVE` command, you can continue at a later time without having to start over from the beginning, just as you can place a bookmark in a book you are reading. `SAVE` puts a "snapshot" of your place in the story onto another diskette. You may want to save your place before (or after) trying something dangerous or tricky. That way, you can go back to that position later, even if you have gotten lost or "killed" since then.

To save your place in the story, type `SAVE` at the prompt (`>`), and then follow the instructions for saving and restoring on your Reference Card. Some systems require a blank diskette, initialized and formatted, for saves. Using a disk with data on it (not counting other *Zork* saves) may result in the loss of that data, depending on your system. You can save your position as often as you like by using additional blank disks.

You can restore a saved position any time you want. To do so, type `RESTORE` at the prompt (`>`), and follow the instructions on your Reference Card. You can then continue the story from the point where you used the `SAVE` command. You can type `LOOK` for a description of where you are.

### Quitting and restarting

If you want to start over from the beginning of the game, type `RESTART`. (This is usually faster than re-booting.) Just to make sure, *Zork* will ask if you really want to start over. If you do, type `Y` or `YES`.

If you want to stop playing, type `QUIT`. Once again, *Zork* will ask if this is really what you want to do.

Remember when you `RESTART` or `QUIT`: if you want to be able to return to your current position, you must first use the `SAVE` command.

## Communicating with Infocom's Interactive Fiction

### Basic sentences

In *Zork*, you type your sentence in plain English each time you see the prompt (`>`). *Zork* usually acts as if your sentence begins "I want to....", although you shouldn't actually type those words. You can use words like "THE" if you want, and you can use capital letters if you want; *Zork* doesn't care either way.

When you have finished typing a sentence, press the RETURN (or ENTER) key and *Zork* will then respond, telling you whether your request is possible at this point in the story, and what happened as a result.

*Zork* recognizes your words by their first six letters, and all subsequent letters are ignored. Therefore, CANDLE, CANDLEs, and CANDLEstick would all be treated as the same word by *Zork*.

To move around, just type the desired direction: NORTH, SOUTH, EAST, WEST, NORTHEAST, NORTHWEST, SOUTHEAST, and SOUTHWEST. You can abbreviate these to N, S, E, W, NE, NW, SE, and SW, respectively. You can use UP (or U) and DOWN (or D). IN and OUT will also work in certain places.

*Zork* understands many different kinds of sentences. Here are some examples. (Note some of these objects do not actually appear in *Zork*.)

```
>WALK NORTH
>DOWN
>NE
>GO SOUTH
>U
>TAKE BOX
>PICK UP THE WOODEN BOX
>DROP IT
>PUSH BUTTON
>OPEN THE WOODEN DOOR
>EXAMINE THE SCUBA GEAR
>LOOK BEHIND STATUE
>LOOK UNDER THE ROCK
>LOOK INSIDE THE BUBBLING CAULDRON
>KILL THE BEAR WITH THE GUN
>SHOOT BEAR WITH LARGE RIFLE
```

### Complex sentences

You can use multiple objects with certain verbs if you separate them by the word AND or by a comma. Some examples:

```
>TAKE LAMP, JAR, FLUTE
>DROP THE DAGGER, LANCE, AND MACE
>PUT THE GOLD BAR AND THE PEARL IN THE TROPHY CASE
```

You can also use ALL...

```
>TAKE ALL
>TAKE ALL THE BOOKS
>TAKE ALL FROM THE DESK
>GIVE ALL BUT THE PENCIL TO THE NYMPH
>DROP ALL EXCEPT THE DART GUN
```

The word ALL refers to every visible object except those inside something else. If there was an apple on the ground and an orange inside a cabinet, TAKE ALL would take the apple but ignore the orange.

You can include several sentences in one input line if you separate them by the word THEN or by a period. (Note that each sentence will still count as a turn.) You don't need a period at the end of the input line. For example, you could type all of the following at once, before pressing the RETURN (or ENTER) key:

```
>NORTH. READ THE BOOK. DROP IT THEN BURN IT WITH TORCH
```

If *Zork* doesn't understand one of the sentences in your input line, or if something unusual happens, it will ignore the rest of your input line (see [Common Complaints](#common-complaints)).

There are only two kinds of questions that *Zork* understands: WHAT and WHERE. Here are two examples that you can actually try in the game:

```
>WHAT IS A GRUE?
>WHERE IS THE ZORKMID?
```

### Talking to characters in the story

You will meet other people and creatures as you play *Zork*. You can "talk" to some of these beings by typing their name, then a comma, then whatever you want them to do. Here are some examples:

```
>GNOME, GIVE ME THE KEY
>TREE SPRITE, OPEN THE SECRET DOOR
>JOEL, WAIT HERE
>WARLOCK, TAKE THE SPELL SCROLL THEN FOLLOW ME
>MIKE, NORTH.GET THE BRAN MUFFIN.THROW IT AT THE DWARF
```

Notice that in the last two examples, you are giving more than one command to the person on the same input line.

You can use quotes to answer a question or say something "out loud." For example:

```
>SAY "HELLO SAILOR"
>ANSWER "A ZEBRA"
>INCANT "FROBOZZ FROBIZZLE"
```

### When Zork has to guess

*Zork* tries to guess what you really mean when you don't give enough information. For example, if you say that you want to do something, but not what you want to do it to or with, *Zork* will sometimes decide that there was only one possible object that you could have meant. When it does so, it will tell you. For example:

```
>BURN THE KINDLING
(with the torch)
The kindling catches fire and is consumed.
```

or

```
>GIVE THE SWORD
(to the gnome)
The gnome, a sworn pacifist, refuses to take it.
```

If your sentence is ambiguous, *Zork* will ask what you really meant. You can answer most of these questions briefly by supplying the missing information, rather than typing the entire input again. You can do this only at the very next prompt. Some examples:

```
>TIE THE ROPE
What do you want to tie the rope to?
>THE MAST
The rope is now tied to the mast.
```

or

```
>HIT THE NAIL WITH THE HAMMER
Which nail do you mean, the shiny nail or the rusty nail?
>SHINY
The shiny nail is driven halfway into the piece of wood.
```

*Zork* uses many words in its descriptions that it will not recognize in your sentences. For example, you might read, "Above you, moonlit clouds flit across the evening sky." However, if *Zork* doesn't recognize the words SKY or CLOUDS in your input, you can assume that the sky and clouds are not important to your completion of the story, except to provide you with a more vivid description of where you are or what is going on. *Zork* recognizes over 600 words, nearly all that you are likely to use in your sentences. If *Zork* doesn't know a word you used, or any of its common synonyms, you are almost certainly trying something that is not important in continuing your adventure.

## Special Commands

There are a number of one-word commands which you can type instead of a sentence. You can use them over and over as needed. Some count as a turn, others do not. Type the command after the prompt (`>`) and press the RETURN (or ENTER) key.

| Command | What it does |
|---|---|
| `AGAIN` (`G`) | *Zork* will usually respond as if you had repeated your previous sentence. Among the cases where AGAIN will not work is if you were just talking to another character. |
| `BRIEF` | Gives you the full description of a location only the first time you enter it. On subsequent visits, *Zork* will tell you only the name of the location and the objects present. This is how *Zork* will normally act, unless you tell it otherwise using the VERBOSE or SUPERBRIEF commands. |
| `DIAGNOSE` | *Zork* will give you a medical report of your physical condition. This is particularly useful if you have just survived a dangerous battle or if you are under the effects of a magical spell. |
| `HINT` | If you have difficulty while playing the game, and you can't figure out what to do, just type HINT. Then follow the instructions at the top of your screen to read the hint of your choice. |
| `INVENTORY` (`I`) | *Zork* will list what you are carrying. |
| `LOOK` (`L`) | Tells *Zork* to describe your location in full detail. |
| `OOPS` | If you accidentally mistype a word, such that *Zork* doesn't understand the word, you can correct yourself on the next line by typing OOPS and the correct word. Suppose, for example, you typed HIT THE TROLL WITH THE SORWD and were told "I don't know the word 'sorwd'." You could type OOPS SWORD rather than retyping the entire sentence. |
| `QUIT` (`Q`) | Lets you stop playing. If you want to save your position before quitting, follow the instructions in [Starting and Stopping](#starting-and-stopping). |
| `RESTART` | Stops the story and starts over from the beginning. |
| `RESTORE` | Restores a game position made using the SAVE command. See [Starting and Stopping](#starting-and-stopping) for more details. |
| `SAVE` | Makes a "snapshot" of your current game position onto your storage diskette. You can return to a saved position in the future using the RESTORE command. See [Starting and Stopping](#starting-and-stopping) for more details. |
| `SCORE` | *Zork* will show your current score and the number of turns you have taken. It will also tell you your rank, which is based on your score. |
| `SCRIPT` | Tells your printer to begin making a transcript of the story as you play. A transcript may aid your memory but is not necessary to play the game. It will work only on certain computers; read your Reference Card for details. |
| `SUPERBRIEF` | Displays only the name of a place you have entered, even if you have never been there before. In this mode, *Zork* will not even mention which objects are present. Of course, you can always get a description of your location, and the items there, by typing LOOK. In SUPERBRIEF mode, the blank line between turns will be eliminated. This mode is meant for adventurers who are already very familiar with the geography. Also see VERBOSE and BRIEF. |
| `UNSCRIPT` | Tells your printer to stop making a transcript. |
| `VERBOSE` | Tells *Zork* that you want a complete description of each location, and the objects in it, every time you enter a location, even if you've been there before. Also see BRIEF and SUPERBRIEF. |
| `VERSION` | *Zork* responds by showing you the release number and the serial number of your copy of the game. Please include this information if you ever report a "bug" in the game. |
| `WAIT` (`Z`) | Causes time in the story to pass. Normally, between turns, nothing happens in the story. You could leave your computer, take a nap, and return to the game to find that nothing has changed. You can use WAIT to make time pass in the story without doing anything. For example, if you encounter an alien being, you could WAIT to see what it will do. Or, if you are in a moving vehicle, you could WAIT to see where it will go. |

## Tips for Novices

*Eleven useful pointers about interactive fiction.*

1. You may want to draw a map showing each location and the directions connecting it to adjoining locations. When you find yourself in a new location, make a note of any interesting objects there. (See the small sample map that goes along with the [sample transcript](#sample-transcript-and-map).) Some puzzles, such as the Maze in *Zork I*, are almost impossible to solve without completely mapping the area. There are 10 possible directions (NORTH, SOUTH, EAST, WEST, NORTHEAST, NORTHWEST, SOUTHEAST, SOUTHWEST, UP, and DOWN) plus IN and OUT. Drawing a map isn't essential in *Zork*, but you might find it useful.
2. EXAMINE all objects you come across in the story.
3. If you find an object that you think you can use, TAKE IT. Some objects will help you solve some of the puzzles.
4. Save your place often. That way, if you mess up or get "killed," you won't have to start over from the beginning. See [Starting and Stopping](#starting-and-stopping) for instructions.
5. Read the story carefully! There are often clues in the descriptions of locations and objects.
6. Try everything you can think of — even strange or dangerous actions may provide clues, and might prove to be fun! You can always save your position first if you want. Here's a silly example:

   ```
   >PUT ON THE GREEN CALICO HAT
   The munchkins giggle, but remain unconvinced that you're a witch.
   ```

   You've just learned there is something which might convince the munchkins that you're a witch. They might even give you their enchanted broom. Perhaps if you put on that blue calico dress you saw earlier in the game...
7. Unlike other "adventure games" you may have played, there are many possible routes to the end of *Zork*. If you get stuck on one puzzle, move on to another. Some puzzles have more than one solution; other puzzles don't need to be solved at all. Sometimes you will have to solve one puzzle in order to obtain the item(s) or information you need to solve another puzzle.
8. You may find it helpful to go through *Zork* with another person. Different people may find different puzzles easy and can often complement each other.
9. If you really have difficulty, you can type HINT. The screen will then show you a list of questions to which you can get answers. (Simply follow the directions at the top of your screen to see the hint of your choice.) You don't *need* to use the hints to enjoy the story, but it will make solving the puzzles easier.
10. Read the [sample transcript](#sample-transcript-and-map) to get a feel for how Infocom's interactive fiction works.
11. You can word a command in many different ways. For example, if you wanted to take a blue jacket, you could type in any of the following:

    ```
    >GET JACKET
    >TAKE THE JACKET
    >PICK UP THE BLUE JACKET
    ```

    If you type in a command that *Zork* doesn't understand, try rephrasing the command or using synonyms. If *Zork* still doesn't understand your command, you are almost certainly trying something that is not important in continuing your adventure.

## Common Complaints

*Zork* will complain if you type a sentence that confuses it completely. *Zork* will then ignore the rest of the input line. (Unusual events, such as being attacked, may also cause *Zork* to ignore the rest of the sentences you typed, since the event may have changed your situation drastically.) Some of *Zork*'s complaints:

**I don't know the word "\_\_\_\_\_".** The word you typed is not in the game's vocabulary. Sometimes using a synonym or rephrasing will help. If not, *Zork* probably doesn't know the idea you were trying to get across.

**You used the word "\_\_\_\_\_" in a way that I don't understand.** *Zork* knows the word you typed, but couldn't use it in that sense. Usually this is because *Zork* knows the word as a different part of speech. For example, if you typed PRESS THE LOWER BUTTON, you are using LOWER as an adjective, but *Zork* might know LOWER only as a verb, as in LOWER THE BOOM.

**There was no verb in that sentence!** Unless you are answering a question, each sentence must have a verb (or a command) in it somewhere.

**There seems to be a noun missing in that sentence!** This usually means that your sentence was incomplete, such as EAT THE BLUE.

**There were too many nouns in that sentence.** An example is PUT THE SOUP IN THE BOWL WITH THE LADLE, which has three noun "phrases," one more than *Zork* can digest in a single action.

**I beg your pardon?** You pressed the RETURN (or ENTER) key without typing anything.

**It's too dark to see.** In the story, there was not enough light to perform your action.

**I don't see what you are referring to.** You used HIM, HER or IT, but *Zork* isn't sure what person or object you meant.

**You can't see any "\_\_\_\_\_" here!** The item you referred to was not visible. It may be somewhere else, inside a closed container, and so on.

**The other object(s) that you mentioned isn't (aren't) here.** You referred to two or more items in the same sentence, and at least one of them wasn't visible to you in your present location.

**You can't go that way.** There was no passage or exit in the direction you tried to move.

**You can't use multiple (in)direct objects with "\_\_\_\_\_".** You can refer to several items at the same time only with certain verbs. Among the more useful of these verbs are TAKE, DROP, and PUT. This restriction also applies to the use of ALL, as in DROP ALL. For example, ATTACK will not work with multiple objects; you couldn't say ATTACK ALL or ATTACK THE WARLOCK AND THE ENCHANTER.

**That sentence isn't one I recognize.** The sentence you typed may have been gibberish, such as GIVE TROLL WITH SWORD. Or, you may have typed a reasonable sentence but used a syntax that *Zork* does not recognize, such as SMELL UNDER THE ROCK. Try rephrasing the sentence.

## We're Never Satisfied

Here at Infocom, we take great pride in the quality of our games. Even after they're "out the door," we're constantly improving, honing and perfecting.

Your feedback is important. No matter how much testing we do, it seems that some bugs never crawl into view until thousands of you begin doing all those wild and crazy things to the story. If you find a bug, or if you think a certain puzzle was too hard or too easy, or if you have some other suggestion, or if you'd just like to tell us your opinion of the story, drop us a note! We love every excuse to stop working, and a letter from you is just such an excuse! Write to:

> Infocom, Inc.  
> 125 CambridgePark Drive  
> Cambridge, MA 02140  
> Attn: Dimwit Flathead

## If You Have Technical Problems

You can call the Infocom Technical Support Team to report bugs and technical problems, but *not* for hints to solve puzzles, by calling (617) 576-3190. If your diskette develops a problem within 90 days after purchase, we will replace it at no charge. Otherwise, there is a replacement fee of $5 (U.S. funds). If you call to report a bug, please provide your release number, which you can find by typing VERSION. Please return your registration card if you'd like to be on our mailing list and receive our newsletter.

*(These 1987 addresses and phone numbers are historical; Infocom closed in 1989.)*

## Copyright and Warranty Information

### Limited Warranty

This software product and the attached instructional materials are sold "AS IS," without warranty as to their performance. The entire risk as to the quality and performance of the computer software program is assumed by the user.

However, to the original purchaser of a disk prepared by Infocom and carrying the Infocom label on the disk jacket, Infocom, Inc. warrants the medium on which the program is recorded to be free from defects in materials and faulty workmanship under normal use and service for a period of ninety (90) days from the date of purchase. If during this period a defect on the medium should occur, the medium may be returned to Infocom, Inc. or to an authorized Infocom, Inc. dealer, and Infocom, Inc. will replace the medium without charge to you. Your sole and exclusive remedy in the event of a defect is expressly limited to replacement of the medium as provided above. This warranty gives you specific legal rights and you may also have other rights which vary from state to state.

THE ABOVE WARRANTIES FOR GOODS ARE IN LIEU OF ALL WARRANTIES, EXPRESS, IMPLIED, OR STATUTORY, INCLUDING, BUT NOT LIMITED TO, ANY IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE AND OF ANY OTHER WARRANTY OBLIGATION ON THE PART OF INFOCOM, INC. SOME STATES DO NOT ALLOW LIMITATIONS ON HOW LONG AN IMPLIED WARRANTY LASTS, SO THE ABOVE LIMITATION MAY NOT APPLY TO YOU. IN NO EVENT SHALL INFOCOM, INC. OR ANYONE ELSE WHO HAS BEEN INVOLVED IN THE CREATION AND PRODUCTION OF THIS COMPUTER SOFTWARE PROGRAM BE LIABLE FOR INDIRECT, SPECIAL, OR CONSEQUENTIAL DAMAGES, SUCH AS, BUT NOT LIMITED TO, LOSS OF ANTICIPATED PROFITS OR BENEFITS RESULTING FROM THE USE OF THIS PROGRAM, OR ARISING OUT OF ANY BREACH OF THIS WARRANTY. SOME STATES DO NOT ALLOW THE EXCLUSION OR LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THE ABOVE LIMITATION MAY NOT APPLY TO YOU.

N.B. After the warranty period, a defective Infocom disk may be returned to Infocom, Inc. with a check or money order for $5.00 U.S. funds for replacement.

### Copyright

The enclosed software product is copyrighted and all rights are reserved by Infocom, Inc. It is published exclusively by Infocom, Inc. The distribution and sale of this product are intended for the use of the original purchaser only and for use only on the computer system specified. Lawful users of this program are hereby licensed only to read the program from its medium into memory of a computer solely for the purpose of executing the program. Copying (except for one backup copy on those systems which provide for it — see Reference Card), duplicating, selling, or otherwise distributing this product is a violation of the law.

This manual and all other documentation contained herein are copyrighted and all rights reserved by Infocom, Inc. These documents may not, in whole or in part, be copied, photocopied, reproduced, translated, or reduced to any electronic medium or machine-readable form without prior consent, in writing, from Infocom, Inc.

Willful violations of the Copyright Law of the United States can result in civil damages of up to $50,000 in addition to actual damages, plus criminal penalties of up to one year imprisonment and/or $10,000 fine.

*Zork* is a registered trademark of Infocom, Inc.  
© 1987 Infocom, Inc. Printed in U.S.A.

## Quick Reference Guide

*The most important things to know about interactive fiction.*

The object of *Zork I* is to find the treasures of the Great Underground Empire and put them in your trophy case.

1. To start the story ("boot up"), see the separate Reference Card in your *Zork* package.
2. When you see the prompt (`>`) on your screen, *Zork* is waiting for your input. There are four kinds of sentences or commands that *Zork* understands:
   - **A. Direction commands:** To move from place to place just type the direction you want to go: N, E, S, W, NE, SE, NW, SW, UP, DOWN, IN, OUT.
   - **B. Actions:** Just type whatever you want to do. Some examples: READ THE BOOK, OPEN THE DOOR, LOOK THROUGH THE WINDOW. Once you're familiar with simple commands, you'll want to use more complex ones as described in [Communicating with Infocom's Interactive Fiction](#communicating-with-infocoms-interactive-fiction).
   - **C. Commands given to people:** To talk to characters in the game, type their name, then a comma, then what you want to say to them. For example: TROLL, GIVE ME THE AXE or OLD MAN, GO NORTH.
   - **D. Special one-word commands** such as INVENTORY or DIAGNOSE. A list of these appears in [Special Commands](#special-commands).
3. **Important!** After typing your sentence or command you must press the RETURN (or ENTER) key before *Zork* will respond.
4. On most computers, your screen will have a special line called the "Status Line." It tells you the name of your current location, your score, and the number of turns you have taken.
5. You can pick up and carry many of the items you'll find in the story. For example, if you type TAKE THE NECKLACE, you will be carrying it. Type INVENTORY to find out what you have.
6. When you want to stop, save your place for later, or start over, read [Starting and Stopping](#starting-and-stopping).
7. If you have trouble, refer to the specific section of the manual for more detailed instructions.

# This Edition's Extras: Enhanced Language

## Enhanced Language Features

*An optional addition of this edition, not part of the original game. It is on when you first start; turn **Enhanced language** off in Settings (F2, then 8) to play with the original game's own parser alone, exactly as Infocom wrote it.*

The original game understands a lot, but it was written in 1980 and expects commands in its own style. The enhanced language layer lets you also type everyday English, such as WHERE AM I?, WHAT AM I CARRYING? or GO BACK. It sits on top of the original game and never changes it:

- **Zork comes first.** If the original game understands what you typed, it answers exactly as it always has, and the layer does nothing. The layer only helps when *Zork* would otherwise reply "I don't know the word…" or "That sentence isn't one I recognize". So everything the original game understands, including its jokes and its own answers to questions like WHAT IS A GRUE?, works as it always did.
- **Answers from the game look like the game.** WHERE AM I? is passed to the game as LOOK, so you get *Zork*'s own room description. Answers written for this edition, such as WHO AM I? and EXITS, appear in the same color as hints, so you can always tell them apart.
- **Questions to this edition cost nothing.** WHO AM I?, EXITS, WHERE IS THE … ? and the like take no move and are not recorded as a move for UNDO. Anything passed to the game counts as a move only if the original command would.
- **Capitals, question marks and polite words don't matter.** PLEASE, CAN YOU, COULD YOU, I WANT TO, I'D LIKE TO, LET'S, OK, NOW, FOR ME and a question mark or exclamation mark at the end are all set aside, and the original game still gets the first try at what is left, so adding PLEASE never changes who answers. PLEASE OPEN THE MAILBOX becomes OPEN THE MAILBOX.
- **Whole sentences work.** Words such as MY, THAT, THIS, QUICKLY, CAREFULLY or JUST are set aside wherever they appear, and each part of a sentence joined with AND, THEN or a full stop is understood on its own, then handed to the game the same way (GRAB THE LAMP AND SWITCH IT ON becomes TAKE LAMP AND TURN ON IT). Commands addressed to someone, with a comma (TROLL, HELLO), go to the game exactly as typed.
- **It remembers what you have seen, and only that.** The edition notes where you last saw each thing, in a lit place you were in, and what you were carrying. That memory answers questions such as WHERE IS THE ROPE? and lets GO TO take you back. It never knows anything you haven't seen yourself, it is saved with your game, kept by UNDO, and forgotten when you restart.

- **The map and hints settings switch their parts off.** Everything here that uses the edition's notes on where you have been and what you have seen (EXITS, WHERE HAVE I BEEN?, GO BACK, HOW DO I GET TO, GO TO, WHERE IS, WHAT DID I DROP and the treasures) needs **Map** on in Settings; with it off, they say so instead. Hint questions and puzzle questions need **Hints** on. Turning either back on picks up where it would have been.

To use the original game's parser alone, turn **Enhanced language** off in Settings (F2, then 8).

The tables below show a few wordings for each thing you can do. Every wording the layer understands, hundreds of them, is listed in full in [the appendix at the end of this manual](#appendix-every-wording-the-enhanced-language-layer-understands).

### About you

| You can type | What happens |
|---|---|
| WHO AM I?<br>WHOAMI<br>WHO AM I PLAYING?<br>WHAT'S MY NAME? | A short description of your character in this game, without spoilers |
| WHERE AM I?<br>WHERE ARE WE?<br>WHAT IS THIS PLACE?<br>WHAT'S HERE?<br>WHAT DO I SEE?<br>WHAT'S AROUND ME?<br>DESCRIBE THIS PLACE | The game's own LOOK: the room's name and description |
| WHAT AM I CARRYING?<br>WHAT AM I HOLDING?<br>WHAT DO I HAVE?<br>WHAT HAVE I GOT?<br>WHAT'S IN MY BAG?<br>SHOW MY INVENTORY<br>CHECK MY POCKETS<br>MY STUFF | The game's own INVENTORY |
| HOW AM I?<br>AM I HURT?<br>AM I OK?<br>HOW'S MY HEALTH? | The game's own DIAGNOSE |
| WHAT'S MY SCORE?<br>HOW AM I DOING?<br>HOW MANY POINTS DO I HAVE? | The game's own SCORE |
| WHAT TIME IS IT?<br>HOW LONG HAVE I BEEN PLAYING? | How long you have played this game (the original has no clock). This works even when the time is hidden in Settings. |

### Finding your way

*EXITS, WHERE HAVE I BEEN? and GO BACK need the map on (Settings, F2, then 4).*

| You can type | What happens |
|---|---|
| EXITS<br>DIRECTIONS<br>WHERE CAN I GO?<br>WHERE TO GO?<br>WHICH WAY?<br>WHICH WAY DO I GO?<br>WHERE SHOULD I GO?<br>WHAT ARE THE EXITS?<br>WHERE DOES THIS LEAD? | The directions from this room, the same list the map shows: where each one leads, or "not explored yet" |
| WHERE HAVE I BEEN?<br>WHERE DID I COME FROM? | How many places you have been, and the place you just came from |
| BACK<br>GO BACK<br>RETURN<br>RETRACE MY STEPS<br>GO BACK THE WAY I CAME | Takes you back to the place you just came from, using the way the map knows works. *(Back the way you came: north.)* is shown first. If the way back is longer than one step, you are told the way instead of being moved; if no way is known, you are told so. |
| HEAD NORTH<br>MOVE SOUTH<br>GO TO THE EAST<br>WALK WESTWARD | The plain direction: NORTH, SOUTH, EAST, WEST |
| GO NORTH-EAST<br>GO NORTH EAST<br>(and the other diagonals) | NORTHEAST and so on. (The original game reads NORTH-EAST as just NORTH.) |
| GO UPSTAIRS<br>CLIMB UP THE STAIRS<br>GO DOWNSTAIRS | UP or DOWN |
| CLIMB DOWN<br>CLIMB UP (with nothing after them) | DOWN or UP, wherever the original game would answer with a broken sentence ("The&nbsp;&nbsp;doesn't lead downward."), a bug in Infocom's original that appears in all three games. Elsewhere the game's own answer is kept. |
| GO INSIDE<br>STEP INSIDE<br>GO OUTSIDE<br>LEAVE<br>EXIT | IN or OUT, where the game itself doesn't understand the words |

### Questions about the world

*WHERE IS, WHAT DID I DROP, the treasures and HOW DO I GET TO need the map on (Settings, F2, then 4). WHAT CAN I DO HERE? needs hints on (Settings, F2, then 5), and with the map off it leaves out the ways to go.*

These are answered from what you have seen (see above). When the thing is right in front of you or in your hands, *Zork* answers WHERE IS itself, in its own words ("It's right here."), which takes a move as any command does.

| You can type | What happens |
|---|---|
| WHERE IS THE ROPE?<br>WHERE DID I LEAVE THE ROPE?<br>WHERE'S MY SWORD?<br>FIND THE LAMP<br>HAVE I SEEN A KEY? | Where you last saw it and how long ago: "You dropped the rope in the Dome Room, 19 moves ago." "You last saw the brass lantern in the trophy case in the Living Room." If you had it and it went without your seeing where: "…but you didn't see where it went." Never seen: "You haven't seen anything called "egg" yet." |
| WHAT DID I DROP?<br>WHAT HAVE I PUT DOWN? | Everything you have put down, where, and when |
| WHERE ARE MY TREASURES?<br>HOW MANY TREASURES DO I HAVE? | In *Zork I*: the treasures you have found, what is in the trophy case, what you are carrying, and where the rest are. (*Zork II* and *III* don't mark which things are treasures, so use WHERE IS.) |
| IS IT DARK?<br>IS THERE ANY LIGHT HERE? | Yes or no |
| IS THERE ANYTHING HERE?<br>WHAT CAN I TAKE? | Everything you can see here, by name |
| SEARCH THE ROOM<br>LOOK AT EVERYTHING<br>EXAMINE EVERYTHING | The game's own LOOK, then everything you can see here, by name. Nothing hidden is found this way: to search one thing, use the game's own SEARCH, or LOOK UNDER, IN or BEHIND it. |
| WHAT CAN I DO HERE?<br>ANY SUGGESTIONS? | The same suggestions as the command buttons, as sentences: ways to go, things to do here, and things to do with what you carry. Because these can point toward a solution, they need hints on, as well as command buttons. |
| HOW DO I GET TO THE KITCHEN?<br>WHICH WAY TO THE DAM?<br>HOW DO I GET TO THE ROPE? | The way there, through places you have been: "From here to the Kitchen: west, then up (2 moves)." For a thing, the way to where you last saw it. If no way is known (a one-way passage, or exits that change), you are told so. |

### Going somewhere: GO TO

*GO TO needs the map on (Settings, F2, then 4).*

GO TO THE KITCHEN walks you there, one real move at a time, through places you have already been. GO TO THE ROPE walks you to where you last saw the rope. It saves typing, not game time: every step costs a move, your lamp keeps burning and the game goes on around you.

- **Trips of more than 5 moves ask first** ("The Cellar is 9 moves away by the ways you know."), with **No** as the default. Shorter trips just go.
- **It shows the trip, not every room.** The story shows one line for the walk, then the full description of where you arrive:

```
>go to kitchen
(Walking to the Kitchen, 3 moves: north to North of House, east to Behind House, west to Kitchen.)
Kitchen
You are in the kitchen of the white house. …
```

- **It stops the moment anything happens**, and shows you everything the game said: anything you haven't seen in that place before (something dropped, or someone wandering about), anything the game says that a plain LOOK there wouldn't (a warning, a noise, your sword glowing), darkness, a change in your score, or a step that didn't lead where it should. Type the same GO TO again to carry on.
- **It never does anything for you.** It only walks, through ways it has checked on a copy of the game. If the way needs something done first, or you have no light where it's dark, it tells you it doesn't know a way right now instead.
- **One UNDO takes back the whole walk.**
- On arrival it reminds you of things you already knew were lying in the places you passed ("On the way you passed: the rope in the Dome Room."), and if you went to a thing that is no longer there, it says so.

GO TO is part of the enhanced language layer, so it is on and off with **Enhanced language** in Settings (F2, then 8).

### Typing mistakes

If the game doesn't know a word you typed, and it is close to the name of something here (or in your hands), to a direction, or to one of the game's everyday verbs, the edition reads it as that word and always says so:

```
>opne the mialbox
(I took "opne" to mean OPEN, and "mialbox" to mean MAILBOX.)
Opening the small mailbox reveals a leaflet.
```

This only happens when exactly one word is close, and only if the corrected command is one the game understands. A word the game knows is never changed, and nothing is corrected into the name of something that isn't here. *Zork*'s own OOPS still works as well.

### Left and right

*Zork* describes every place by compass directions and has no idea which way you are facing. In its mazes and twisting passages, left and right would mean nothing at all, so this edition doesn't use them either. GO LEFT, TURN AROUND, KEEP GOING, WHAT'S AHEAD? and the like get a short reminder instead, and take no move:

```
>go left
Zork uses compass directions, not left and right: try NORTH, SOUTH, EAST or WEST (or UP, DOWN, IN and OUT). Type WHICH WAY CAN I GO? to see the ways out, or GO BACK to return the way you came.
```

To find your way, use EXITS (WHICH WAY CAN I GO?), GO BACK, GO TO and the map. In a maze, do what players have always done: drop something in each place so you can tell them apart (WHERE DID I DROP … reminds you where), and let the map record which way leads where.

### Doing things

| You can type | What happens |
|---|---|
| X LAMP<br>CHECK THE LAMP<br>INSPECT LAMP<br>LOOK CLOSELY AT THE LAMP | EXAMINE LAMP |
| GRAB LAMP | TAKE LAMP |
| TAKE EVERYTHING<br>GET IT ALL<br>DROP EVERYTHING | TAKE ALL or DROP ALL |
| REPEAT<br>DO THAT AGAIN | AGAIN: your last command once more |
| REST<br>RELAX | WAIT |
| SWITCH ON THE LAMP<br>FLIP IT ON<br>SWITCH THE LAMP OFF | TURN ON LAMP, TURN ON IT, TURN OFF LAMP |
| PICK THE LAMP UP<br>GET RID OF THE LAMP<br>PUT DOWN THE LAMP | TAKE LAMP or DROP LAMP |
| TOSS THE KNIFE<br>CHUCK IT | THROW KNIFE, THROW IT |
| STAB THE TROLL<br>PUNCH IT<br>FIGHT THE TROLL | ATTACK TROLL, ATTACK IT |
| PEEK INSIDE THE BOX<br>LOOK INSIDE IT | LOOK IN BOX |
| EXAMINE THE BRASS THING<br>TAKE THE SMALL OBJECT | The one thing here or in your hands that the description fits, by a word in its name or one of the game's own adjectives ("the brass thing" is the brass lantern). If several things fit, you are asked which; if nothing fits, you are told. |
| USE LAMP<br>USE KEY ON DOOR | *Zork* has no USE, because it wants to know exactly what you mean. You are reminded to try a specific verb such as LIGHT, OPEN, UNLOCK, READ, WAVE or PUT … IN. The layer never guesses, because guessing could solve puzzles for you. |

### Talking to characters

*Zork* has its own ways of speaking to the characters you meet: TALK TO TROLL, HELLO TROLL, ASK TROLL ABOUT something, and the name, a comma and an order (TROLL, GIVE ME THE AXE). The layer puts everyday ways of saying it into those forms. Whatever comes back is the game's own reply: nothing is made up, and a character who wouldn't talk to you still won't.

| You can type | What happens |
|---|---|
| SPEAK TO THE TROLL<br>CHAT WITH THE TROLL<br>TALK WITH THE TROLL | TALK TO TROLL |
| SAY HELLO TO THE TROLL<br>GREET THE TROLL<br>SAY HI | HELLO TROLL or HELLO |
| ASK THE TROLL TO …<br>GET THE TROLL TO … | TROLL, … (the game's own way of telling someone to do something) |
| ASK THE TROLL WHERE …?<br>ASK THE TROLL FOR HELP | *Zork* can't take questions put that way, so you are shown the ways it does understand |

### Mending Infocom's own slips

A few replies in the original games come out wrong because of small bugs in Infocom's code. With the layer on, these are put right; with it off, you see them exactly as Infocom shipped them.

| What you do | Infocom's original (buggy) reply | Fixed reply (layer on) |
|---|---|---|
| CLIMB DOWN or CLIMB UP with nothing after them, in all three games | "The&nbsp;&nbsp;doesn't lead downward." | You climb down (or up), as DOWN or UP would |
| Mentioning a wall in Zork I, almost anywhere | "Which wall do you mean, the granite wall or the surrounding wall?" even where there is no granite wall | The wall that is actually there is used |
| Answering a "Which … do you mean?" question with the same word again (THE SWORD), in all three games | The same question, over and over | You're told to type the full name, such as ELVISH SWORD or NICKED SWORDS |
| Replies that call you "the you" in Zork I (PUT WATER IN ME, for example) | "The water leaks out of the you…" | "The water leaks out of you…" |
| SMELL ROSES in the gardens of Zork II | "It smells like a roses." | "It smells like roses." |
| NORTHWARD or SOUTHWARD, in all three games | You go northwest or southwest: the original reads only the first six letters of a word, so NORTHWARD is NORTHW | You go north or south |
| Ending a command with FOR ME, in all three games | Odd replies such as "You hit your head against you." | FOR ME is set aside, as PLEASE is |

### Getting help

*Hint questions, puzzle questions and WHAT CAN I DO HERE? need hints on (Settings, F2, then 5). Hints are off when you first start.*

| You can type | What happens |
|---|---|
| HOW DO I PLAY?<br>WHAT CAN I TYPE?<br>COMMANDS | Opens Help (F1) |
| GIVE ME A HINT | Opens the hints, as HINT does |
| I'M STUCK<br>WHAT SHOULD I DO? | Reminds you that HINT is there |
| WHAT DOES THE LEAFLET DO?<br>HOW DO I OPEN …?<br>HOW DO I GET PAST THE TROLL?<br>HOW DO I WIN? | Not answered, because the answer would solve a puzzle for you. You are pointed to HINT instead. |
| THANKS<br>THANK YOU | You're welcome. |

A few everyday words already mean something to the original game, and those stay as Infocom wrote them. For example, SIT DOWN is read as DOWN, and WHAT IS A GRUE? gets the game's own answer. The layer never changes the game's own housekeeping words (SAVE, RESTORE, RESTART, QUIT, SCRIPT, BRIEF, VERBOSE and SUPERBRIEF).

## Appendix: Every Wording the Enhanced Language Layer Understands

This is the complete list of what the enhanced language layer understands, in every wording it accepts. The chapter [Enhanced Language Features](#enhanced-language-features) explains what each one does; this list is for looking up whether a way of saying something will work.

Two things to keep in mind:

- **Zork comes first.** A few of these wordings already mean something to the original game, and then the game's own answer is the one you get. For example, WHAT IS A GRUE? gets the game's own answer, SIT DOWN is read as DOWN, STAY gets the game's own reply and, in *Zork I*, TREASURE is a magic word. When the game only asks a question back or misreads you ("What do you want to search?"), the layer answers instead.
- **An ellipsis (…) stands for a name**, such as the lamp, the rope or a place: GRAB … means GRAB THE LAMP, GRAB LAMP and so on.

#### Ways to start or end any command

These words are set aside, so they can go with anything on this list or anything the original game understands:

- At the start: PLEASE, OK, OKAY, NOW, SO, WELL, HEY, ALRIGHT, UM
- Asking: CAN YOU, COULD YOU, WOULD YOU, WILL YOU, CAN I, COULD I
- Saying what you mean to do: I WANT TO, I WANNA, I WOULD LIKE TO, I'D LIKE TO, I WILL, I'LL, LET ME, LET'S, LET US, TRY TO, I TRY TO, I AM GOING TO, I'M GONNA, I NEED TO, GO AHEAD AND, and I before a verb (I GO NORTH, I TAKE THE LAMP)
- At the end: PLEASE, FOR ME, NOW, RIGHT NOW, RIGHT AWAY, AT ONCE, and a question mark or full stop
- Anywhere: PLEASE, KINDLY, JUST, SIMPLY, QUICKLY, SLOWLY, CAREFULLY, GENTLY, QUIETLY, SOFTLY, REALLY, ACTUALLY, BASICALLY, IMMEDIATELY, FOR ME, RIGHT NOW, IF YOU CAN, IF POSSIBLE, AT ONCE, REAL QUICK, GO AHEAD AND
- Before a name: MY, YOUR, THAT, THIS, THESE, THOSE, OUR (GRAB THAT LAMP is GRAB LAMP)
- Short forms: WHAT'S, WHERE'S, WHO'S, HOW'S, THAT'S, THERE'S, I'M and I'VE are read as their long forms, with or without the apostrophe

So PLEASE COULD YOU JUST GRAB THAT LAMP FOR ME? is read as TAKE LAMP.

#### Saying several things at once

Join the parts with AND, THEN, AND THEN, or a full stop. Each part is read on its own, using everything on this list:

- TAKE THE LAMP AND GO NORTH
- OPEN THE DOOR THEN GO IN
- GO NORTH AND THEN GRAB THE SWORD
- GO BACK AND THEN LOOK

#### Typing mistakes

A misspelled word is corrected when it is close to exactly one name of something here or in your hands, a direction, or an everyday verb, and you are always told what was changed (see [Typing mistakes](#typing-mistakes)). This works inside every wording here too: PLEASE GRAB THE LAMPP is read as TAKE LAMP when the lamp is in front of you.

#### About you

*Means:* Who your character is in this game.

- WHO AM I?
- WHOAMI
- WHO AM I PLAYING?
- WHO AM I SUPPOSED TO BE?
- WHO IS MY CHARACTER?
- WHO IS THE HERO?
- WHO IS THE PLAYER?
- WHAT IS MY NAME?
- WHAT AM I?

#### Where you are

*Means:* The game's own LOOK.

- WHERE AM I?
- WHERE AM I NOW?
- WHERE ARE WE?
- WHERE IS THIS?
- WHAT IS THIS PLACE?
- WHAT PLACE IS THIS?
- WHAT IS HERE?
- WHAT IS AROUND?
- WHAT IS AROUND ME?
- WHAT IS AROUND HERE?
- WHAT DO I SEE?
- WHAT CAN I SEE?
- WHAT CAN I SEE HERE?
- LOOK AROUND ME
- DESCRIBE THIS PLACE
- DESCRIBE THE ROOM
- DESCRIBE THIS ROOM
- DESCRIBE WHERE I AM
- DESCRIBE MY SURROUNDINGS
- WHAT IS GOING ON?

#### What you're carrying

*Means:* The game's own INVENTORY.

- WHAT AM I CARRYING?
- WHAT AM I CARRYING AROUND?
- WHAT AM I HOLDING?
- WHAT DO I HAVE?
- WHAT HAVE I GOT?
- WHAT STUFF DO I HAVE?
- WHAT ITEMS DO I HAVE?
- WHAT THINGS DO I HAVE?
- WHAT IS IN MY INVENTORY?
- WHAT IS IN MY BAG?
- WHAT IS IN MY PACK?
- WHAT IS IN MY BACKPACK?
- WHAT IS IN MY POCKET?
- WHAT IS IN MY POCKETS?
- WHAT IS IN MY HAND?
- WHAT IS IN MY HANDS?
- SHOW / CHECK / LIST / SEE / OPEN MY INVENTORY
- SHOW MY BAG, PACK, BACKPACK, POCKETS, STUFF, ITEMS or THINGS (also with CHECK, LIST, SEE or OPEN)
- MY INVENTORY
- MY STUFF
- MY ITEMS
- MY THINGS
- MY BAG

#### Your health

*Means:* The game's own DIAGNOSE.

- HOW AM I?
- AM I HURT?
- AM I OK?
- AM I OKAY?
- AM I ALRIGHT?
- AM I ALL RIGHT?
- AM I INJURED?
- AM I WOUNDED?
- AM I DYING?
- AM I HEALTHY?
- HOW IS MY HEALTH?
- WHAT IS MY HEALTH?
- CHECK MY HEALTH
- MY HEALTH
- HEALTH
- HOW DO I FEEL?
- HOW BADLY AM I HURT?

#### Your score

*Means:* The game's own SCORE.

- WHAT IS MY SCORE?
- HOW AM I DOING?
- HOW MANY POINTS DO I HAVE?
- HOW MANY POINTS?
- MY SCORE
- SHOW SCORE
- SHOW MY SCORE
- CHECK SCORE
- CHECK MY SCORE
- POINTS

#### Time played

*Means:* How long you have played this game.

- WHAT TIME IS IT?
- WHAT IS THE TIME?
- TIME
- TIME PLAYED
- PLAY TIME
- PLAYTIME
- HOW LONG HAVE I BEEN PLAYING?
- HOW LONG HAVE I PLAYED?
- HOW MUCH TIME HAS PASSED?

#### Which way can I go

*Means:* The ways out of this place and where each leads. Needs the map on.

- EXITS
- DIRECTIONS
- WHERE CAN I GO?
- WHERE CAN I GO NOW?
- WHICH WAY?
- WHICH WAY CAN I GO?
- WHICH WAYS?
- WHICH WAY DO I GO?
- WHICH WAY SHOULD I GO?
- WHICH WAY NOW?
- WHAT WAY?
- WHAT ARE THE EXITS?
- WHERE ARE THE EXITS?
- SHOW EXITS
- LIST EXITS
- SHOW DIRECTIONS
- LIST DIRECTIONS
- WHERE DOES THIS LEAD?
- WHERE DO THE EXITS GO?
- WHAT DIRECTIONS CAN I GO?
- WHICH DIRECTIONS?
- WHICH DIRECTIONS CAN I GO?
- WAYS OUT
- WHERE TO?
- WHERE TO GO?
- WHERE NOW?
- WHERE DO I GO?
- WHERE SHOULD I GO?

#### Where you've been

*Means:* How many places you've been, and where you just came from. Needs the map on.

- WHERE HAVE I BEEN?
- WHERE DID I COME FROM?
- WHERE DID I JUST COME FROM?
- WHERE WAS I?
- WHERE WAS I BEFORE?
- HOW MANY PLACES HAVE I BEEN?
- HOW MANY PLACES HAVE I VISITED?
- PLACES I HAVE BEEN

#### Left and right

*Means:* A reminder that *Zork* uses compass directions, with WHICH WAY CAN I GO? and GO BACK. Takes no move.

LEFT, RIGHT, GO LEFT, GO RIGHT, TURN LEFT, TURN RIGHT, TURN AROUND, LOOK LEFT, AHEAD, FORWARD, STRAIGHT AHEAD, KEEP GOING, CONTINUE, CARRY ON, GO ON, BACKWARD, BEHIND ME, WHAT'S BEHIND ME?, WHAT'S AHEAD?, WHAT'S TO MY LEFT?, FACING, WHICH WAY AM I FACING?

#### Going back the way you came

*Means:* A move back to the place you just came from. Needs the map on.

- BACK
- GO BACK
- TURN BACK
- HEAD BACK
- WALK BACK
- RUN BACK
- RETURN
- RETRACE
- RETRACE MY STEPS
- GO BACK THE WAY I CAME
- BACK THE WAY I CAME
- GO BACK THE WAY I CAME IN
- GO BACK WHERE I CAME FROM
- GO BACK TO WHERE I WAS
- GO BACK TO WHERE I CAME FROM

#### Compass directions, said any way

*Means:* The plain direction. Works for NORTH, SOUTH, EAST, WEST, NORTHEAST, NORTHWEST, SOUTHEAST and SOUTHWEST.

GO NORTH, WALK, RUN, MOVE, HEAD, TRAVEL, PROCEED, STEP, JOURNEY or WANDER NORTH, GO ON NORTH, GO TO THE NORTH, HEAD TOWARD THE NORTH, WALK TOWARDS THE EAST, GO NORTHWARD, NORTHWARD, NORTHWARDS (also SOUTHWARD, EASTWARD, WESTWARD), GO NORTH-EAST, GO NORTH EAST (and the other diagonals)

#### Up and down

*Means:* UP or DOWN.

- GO UP / GO DOWN
- WALK, CLIMB, HEAD, RUN or MOVE UP (or DOWN)
- GO UP THE STAIRS
- CLIMB DOWN THE LADDER
- WALK UP THE STEPS
- GO UP THE STAIRCASE
- GO DOWN THE STAIRWAY
- UPSTAIRS
- DOWNSTAIRS
- GO UPSTAIRS
- WALK DOWNSTAIRS
- CLIMB UPSTAIRS
- HEAD DOWNSTAIRS

#### In and out

*Means:* IN or OUT, where the game itself doesn't understand the words.

- GO INSIDE
- WALK INSIDE
- HEAD INSIDE
- STEP INSIDE
- GET INSIDE
- GO IN THERE
- WALK IN
- STEP IN
- GO OUTSIDE
- WALK OUTSIDE
- HEAD OUTSIDE
- STEP OUTSIDE
- GO OUT
- GO OUT THERE
- GET OUT
- HEAD OUT
- WALK OUT
- STEP OUT
- LEAVE
- EXIT

#### Looking at things

*Means:* EXAMINE. Put the thing's name after any of these.

LOOK CLOSELY AT …, LOOK CAREFULLY AT …, TAKE A LOOK AT …, HAVE A LOOK AT …, EXAMINE CLOSELY …, CHECK …, CHECK OUT …, LOOK OVER …, INSPECT …, STUDY …, INVESTIGATE …, OBSERVE …, VIEW …, DESCRIBE …, SCRUTINIZE …, SCAN …, X …

#### Looking inside, under and behind

*Means:* LOOK IN, LOOK UNDER or LOOK BEHIND.

LOOK INSIDE …, PEEK IN …, PEEK INTO …, PEEK INSIDE …, PEER IN …, PEER UNDER …, PEER BEHIND …, GLANCE INTO …, GLANCE UNDER …, GLANCE BEHIND …

#### Picking things up

*Means:* TAKE.

GRAB …, SNATCH …, NAB …, COLLECT …, SEIZE …, TAKE HOLD OF …, PICK … UP, GRAB … UP, LIFT … UP

#### Putting things down

*Means:* DROP.

PUT DOWN …, GET RID OF …, LET GO OF …, DISCARD …, DITCH …

#### Taking or dropping everything

*Means:* TAKE ALL or DROP ALL.

- TAKE EVERYTHING
- GRAB EVERYTHING
- GET EVERYTHING
- PICK UP EVERYTHING
- TAKE IT ALL / GET IT ALL
- TAKE ALL OF IT
- TAKE ALL THE STUFF
- TAKE ALL ITEMS / ALL THINGS
- TAKE ALL OF THEM / THEM ALL
- TAKE ALL MY STUFF / MY STUFF
- DROP EVERYTHING
- PUT DOWN EVERYTHING
- DROP IT ALL

#### Turning things on and off

*Means:* TURN ON or TURN OFF.

SWITCH ON …, FLIP ON …, POWER ON …, SWITCH … ON, FLIP … ON, POWER … ON, SWITCH OFF …, FLIP OFF …, POWER OFF …, SWITCH … OFF, FLIP … OFF, POWER … OFF

#### Throwing

*Means:* THROW.

TOSS …, CHUCK …, HURL …, FLING …, LOB …

#### Fighting

*Means:* ATTACK.

STAB …, PUNCH …, SLASH …, FIGHT …, SLAY …, SMACK …, WHACK …, BASH …

#### Calling something by how it looks

*Means:* The one thing here or in your hands that fits the description. Use a word from its name, or one of the game's own adjectives for it, then THING, OBJECT or ITEM.

- EXAMINE THE BRASS THING
- TAKE THE SMALL OBJECT
- DROP THE RUSTY ITEM

#### Doing it again

*Means:* AGAIN: your last command once more.

REPEAT, REPEAT THAT, DO THAT AGAIN, DO IT AGAIN, SAME AGAIN, ONE MORE TIME, REDO, DO THE SAME

#### Waiting

*Means:* WAIT.

REST, RELAX, SLEEP, NAP, TAKE A NAP, TAKE A REST, HAVE A REST, WAIT A BIT, WAIT A MOMENT, WAIT A WHILE, WAIT A MINUTE, PAUSE, HANG ON, DO NOTHING, STAND STILL

#### Using things

*Means:* A reminder of the real verbs to try (LIGHT, OPEN, UNLOCK, READ, WAVE, PUT … IN). The game has no USE, and the layer never guesses.

- USE …
- USE … ON …
- USE … WITH …
- USE … IN …

#### Treasures

*Means:* The treasures you have found, what is in the trophy case, what you are carrying, and where the rest are. Needs the map on.

- WHERE ARE MY TREASURES?
- WHERE ARE ALL THE TREASURES?
- WHERE ARE THE TREASURES?
- WHAT TREASURES DO I HAVE?
- WHAT TREASURES HAVE I FOUND?
- MY TREASURES
- LIST MY TREASURES
- SHOW THE TREASURES
- HOW MANY TREASURES DO I HAVE?
- HOW MANY TREASURES HAVE I FOUND?
- HOW MANY TREASURES ARE THERE?

#### What you've dropped

*Means:* Everything you have put down, where and when. Needs the map on.

- WHAT DID I DROP?
- WHAT HAVE I DROPPED?
- WHAT DID I LEAVE?
- WHAT DID I LEAVE BEHIND?
- WHAT HAVE I LEFT BEHIND?
- WHAT DID I PUT DOWN?
- WHAT HAVE I PUT DOWN?
- SHOW WHAT I DROPPED
- LIST DROPPED THINGS
- SHOW MY DROPS

#### Light and dark

*Means:* Yes or no.

- IS IT DARK?
- IS IT DARK HERE?
- IS IT DARK IN HERE?
- AM I IN THE DARK?
- IS THERE LIGHT?
- IS THERE ANY LIGHT HERE?
- IS IT LIGHT HERE?
- IS IT LIT?
- IS IT LIT HERE?
- IS THIS ROOM DARK?
- CAN I SEE?
- CAN I SEE ANYTHING?

#### What's lying here

*Means:* Everything you can see here, by name.

- IS THERE ANYTHING HERE?
- IS ANYTHING HERE?
- ANYTHING HERE?
- WHAT OBJECTS ARE HERE?
- WHAT THINGS ARE AROUND?
- WHAT ITEMS ARE HERE?
- WHAT CAN I TAKE?
- WHAT CAN I TAKE HERE?
- WHAT CAN I PICK UP?
- WHAT CAN I GRAB?
- WHAT IS LYING HERE?
- WHAT IS LYING AROUND?
- WHAT DO I SEE LYING AROUND?

#### Suggestions

*Means:* The same suggestions as the command buttons, as sentences. Needs hints on; with the map off, the ways to go are left out.

- WHAT CAN I DO?
- WHAT CAN I DO HERE?
- WHAT CAN I DO NOW?
- WHAT COULD I DO?
- WHAT COULD I DO HERE?
- WHAT COULD I TRY?
- WHAT SHOULD I TRY?
- WHAT ARE MY OPTIONS?
- WHAT ARE MY CHOICES?
- ANY SUGGESTIONS?
- SUGGESTIONS
- SUGGEST SOMETHING
- GIVE ME IDEAS
- GIVE ME SOME IDEAS
- GIVE ME SOME SUGGESTIONS

#### Searching the room

*Means:* The game's own LOOK, then everything you can see here, by name.

- SEARCH THE ROOM
- SEARCH
- SEARCH HERE
- LOOK AT EVERYTHING
- EXAMINE EVERYTHING
- CHECK OUT THE ROOM
- EXPLORE THE AREA
- INSPECT THE PLACE
- WHAT IS HERE TO LOOK AT?

#### Finding things

*Means:* Where you last saw it and how long ago. Put the thing's name after any of these. Needs the map on.

- WHERE IS …?
- WHERE ARE …?
- WHERE DID I LEAVE …?
- WHERE DID I PUT …?
- WHERE DID I DROP …?
- WHERE DID I LOSE …?
- WHERE HAVE I LEFT …?
- WHERE HAVE I PUT …?
- WHERE HAVE I DROPPED …?
- WHERE CAN I FIND …?
- WHERE MIGHT I FIND …?
- FIND …
- LOCATE …
- HAVE I SEEN …?
- WHERE IS … NOW?

#### The way to somewhere

*Means:* The way there, through places you have been, for you to walk yourself. Put a place or a thing after any of these. Needs the map on.

- HOW DO I GET TO …?
- HOW DO I GET BACK TO …?
- HOW CAN I GET TO …?
- HOW CAN I GET BACK TO …?
- HOW TO GET TO …?
- HOW TO GET BACK TO …?
- HOW DO I REACH …?
- HOW DO I FIND MY WAY TO …?
- HOW DO I FIND MY WAY BACK TO …?
- WHICH WAY TO …?
- WHICH WAY IS IT TO …?
- WHICH WAY IS …?
- WHAT IS THE WAY TO …?
- THE WAY TO …
- WAY TO …
- DIRECTIONS TO …
- ROUTE TO …
- HOW FAR IS …?
- HOW FAR IS IT TO …?

#### Going somewhere

*Means:* GO TO: walks you there one real move at a time (see [Going somewhere: GO TO](#going-somewhere-go-to)). Put a place you have been, or a thing you have seen, after any of these. Needs the map on.

- GO TO …
- WALK TO …
- RUN TO …
- HEAD TO …
- TRAVEL TO …
- TAKE ME TO …
- GET ME TO …
- BRING ME TO …
- LEAD ME TO …
- NAVIGATE TO …
- GOTO …
- GO OVER TO …
- WALK OVER TO …
- HEAD OVER TO …
- MAKE MY WAY TO …
- RETURN TO …
- GO BACK TO …
- WALK BACK TO …
- HEAD BACK TO …
- GO FIND …

#### Talking to characters

*Means:* The game's own TALK TO, HELLO or NAME, ORDER. Put a character's name after any of these.

- SPEAK TO …
- CHAT WITH …
- TALK WITH …
- CONVERSE WITH …
- SAY HELLO TO …
- SAY HI TO …
- GREET …
- SAY HELLO
- SAY HI
- ASK … TO … (becomes …, …)
- GET … TO …
- ORDER … TO …

#### Questions Zork can't take

*Means:* How to talk to characters in *Zork*.

- ASK … WHERE …?
- ASK … FOR HELP
- ASK … HOW …?
- ASK … WHAT …?

#### Getting help

*Means:* Opens Help (F1).

- HOW DO I PLAY?
- HOW TO PLAY
- HOW DOES THIS WORK?
- WHAT CAN I TYPE?
- WHAT CAN I SAY?
- WHAT DO I TYPE?
- COMMANDS
- LIST COMMANDS
- SHOW COMMANDS
- WHAT ARE THE COMMANDS?
- HELP COMMANDS
- CONTROLS
- KEYS
- INSTRUCTIONS PLEASE

#### Asking for a hint

*Means:* Opens the hints, as HINT does. Needs hints on.

- GIVE ME A HINT
- HINT PLEASE
- CAN I HAVE A HINT?
- I NEED A HINT
- A HINT
- HELP ME

#### Being stuck

*Means:* A reminder that HINT is there. Needs hints on.

- I AM STUCK
- I'M STUCK
- STUCK
- I'M LOST
- I AM LOST
- WHAT SHOULD I DO?
- WHAT DO I DO?
- WHAT DO I DO NOW?
- WHAT NOW?
- NOW WHAT?
- I NEED HELP
- GIVE ME A CLUE
- CLUE
- ANY IDEAS?

#### Puzzle questions

*Means:* Not answered, because the answer would solve a puzzle. You are pointed to HINT instead. Needs hints on.

- WHAT DOES … DO?
- WHAT IS … FOR?
- WHAT DO I DO WITH …?
- HOW DO I OPEN …?
- HOW DO I GET PAST …?
- HOW DO I KILL …?
- HOW DO I GET …?
- HOW DO I WIN?
- WHAT IS THE ANSWER?
- HOW DOES … WORK?
- WHY CAN'T I …?

#### Thanks

*Means:* You're welcome.

THANKS, THANK YOU, THANK YOU VERY MUCH, THANKS A LOT, THANKS SO MUCH, TY, CHEERS

*INFOCOM · Proof of Purchase · Zork I · G-IZ1-03A*

## Copyright

### The Original Game

ZORK™ is a trademark of Infocom, Inc. © 1987 Infocom, Inc. Infocom's own copyright and warranty notice is kept, as printed, in [Copyright and Warranty Information](#copyright-and-warranty-information).

### This Edition

**Caldwell Z-Machine for Browsers Edition**  
Copyright © 2026 Jason Caldwell [zork.czm@fastmail.com]  
MIT License: free to use, copy, modify and distribute.

Game by Marc Blank and Dave Lebling of Infocom. Game file released by Microsoft under the MIT License. *Zork* is a trademark of its owner; this is an unofficial fan edition. IBM VGA font by VileR (int10h.org), CC BY-SA 4.0. The original manual text and pictures remain the work of Infocom, Inc.

---

*ZORK™ is a trademark of Infocom, Inc. © 1987 Infocom, Inc. The separate Reference Card that came in the game package (loading, disk and printer instructions) is not included here.*

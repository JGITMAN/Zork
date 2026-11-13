![ZORK II](zork2-cover.png)

# Zork II: The Wizard of Frobozz — Instruction Manual

*Infocom, 1981–1982. An INTERLOGIC™ prose adventure: "The next step downward to danger." Transcribed from the original printed manual (Commodore edition).*

---

# Before You Begin: Playing in Your Browser

## Playing the Caldwell Z-Machine for Browsers Edition

This edition of *Zork II* is Infocom's original game file, unchanged, running in your web browser on the Caldwell Z-Machine for Browsers. There is nothing to install. Open **zork-ii-game.html** in any modern browser and the story begins. Everything this manual says about talking to the game still applies. The parts about disks, reference cards, printers and Infocom's old addresses and phone numbers are kept for history only.

### The screen

- **Status line**: the room you are in, your score and the number of moves you have made.
- **Story window**: everything the game has said so far.
- **Button panel** (hidden at first; press `F4` to show it): commands that make sense where you are right now, built from the game's own rooms and objects. Click one instead of typing. Cyan buttons move you (including **Go back**, which takes you back to the place you just came from when one step gets you there), green ones act on things around you, orange ones use what you are carrying, and red ones fight or answer "yes". Gray ones are general commands such as LOOK AROUND and INVENTORY. The buttons only offer what you can plainly see and carry; buttons that would solve a puzzle (the right magic word, the trick with an object) appear only with hints turned on, and buttons for directions only with the map on.
- **Function-key bar**: the keys listed below, and on the right the time you have spent playing this game (hours, minutes and seconds, with days in front once a day has passed). It counts only while the game is open and in view, carries on where it left off when you come back, and goes back to zero when you restart or quit. You can hide it in Settings (F2). While a transcript is being recorded (SCRIPT), a red **• REC** pulses next to the time.

### Typing

Type at the prompt (`>`) and press Enter, in the game's own style: a verb and a thing (TAKE SWORD, TURN ON THE LAMP, EXAMINE THE SWORD), compass directions (NORTH, or just N), and so on. [Talking to ZORK](#talking-to-zork) explains everything the game understands. The Up and Down arrow keys bring back commands you typed before. Shift+Up and Shift+Down, Page Up and Page Down, or the mouse wheel scroll back through the story.

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
- **UNSCRIPT** stops recording and saves the transcript as a text file, named with the date and time, such as *Zork II transcript 2026-11-12_13-29.txt*. Your browser puts it wherever it keeps downloads.
- **Click REC** to see how long it has been recording, or to stop and save straight away.
- **It keeps recording** if you close the page and come back later, along with the rest of your game. UNDO, SAVE and RESTORE don't stop it.
- **Starting a new game stops it.** If you RESTART or QUIT while recording, you are asked whether to save the transcript first. The new game always starts with recording off.
- **It holds about 1 MB of text**, roughly 3,000 moves; a whole game of *Zork II* is a few hundred. You are warned when it is nearly full, and when it is full it stops recording, keeps everything so far, and waits for UNSCRIPT.
- **If your browser can't save a file** (for example, when the game is shown inside another web page), UNSCRIPT shows the transcript in a window instead, with a **Copy** button so you can paste it wherever you like.

### The map

Choose Map from the menu (F3, then 2) or type MAP to open the map. It is built from the moves you have actually made, so its list of places holds only rooms you have been in.

- **The top** names the room you are in. Under **Directions** it lists each way out and where it leads, for example, at the Foot Bridge, *North → Narrow Tunnel*. When two directions lead to the same place, they share a line, and either word works. A direction the game hasn't shown you yet says *not explored yet*. For ordinary exits, the destination comes straight from the game itself, so it can name a room you haven't walked to.
- **Places you have been** lists every room you have explored. Your own room is marked *(you are here)*. Click a place, or move to it with the arrow keys and press Enter, to see its directions and the way there from where you are now, such as *Way there from Foot Bridge: north, north*. Each route is tried out on a copy of your game before it is shown. If there is no sure way there, for example through a door that closed behind you, the map says so. The map never moves you; you walk the route yourself. Backspace takes you back to your own room.
- Rooms that share a name, such as the rooms of a maze, are numbered (*Maze 1*, *Maze 2* …). A room you were only ever in without a light appears as *Dark place*. A direction that has taken you to different places is marked *varies*. Special trips, such as one made with a magic word, are listed by the command that made them.
- When the list is longer than the screen, it scrolls: use the scroll bar on the right, the mouse wheel, or the arrow, Page Up, Page Down, Home and End keys. The top part stays in place.
- You can turn the map off in Settings (F2), or by typing MAP OFF. Typing MAP ON turns it back on.
- The map is saved with your game and stays in step with UNDO, SAVE and RESTORE.

Press Esc or click OK to close the map.

### Getting hints

Hints are off when you first start, so nothing is given away unless you want it. To use them, turn **Hints** on in Settings (F2, then 5).

Stuck? Type HINT, or choose Hint from the menu (F3, then 3). A pop-up lists questions about the places you have been, with questions about the room you are in at the top. Pick one, and its hints appear one at a time, from a gentle nudge to the full answer. Press Enter for the next hint, Backspace to go back to the questions, and Esc to close. A long list or a long answer scrolls, the same way as the map. These hints were written for this edition, since the game files themselves have none. Each game keeps track of the hints you have read, and starting a new game clears them.

# The Original Manual: About Zork II

## Welcome to ZORK!

Until you've entered the world of ZORK, you've never truly adventured underground.

Both ZORK I and ZORK II are designed so that you'll experience their challenges in the most realistic sense. You can communicate in complete sentences rather than two-word commands, with the largest vocabulary and widest range of command options in the genre. Because ZORK's mysteries are the most intricate you'll ever encounter, it will take all your intellectual abilities to survive and emerge victorious from the underground. And because the challenges change with every move you make, each time you re-enter ZORK you'll face new intrigues.

**ZORK I: The Great Underground Empire** confronts you with perils and predicaments ranging from the mystical to the macabre, as you strive to discover the Twenty Treasures of ZORK and escape with them and your life!

**ZORK II: The Wizard of Frobozz** takes you into new depths of the subterranean realm. There you'll meet the Wizard who will attempt to confound your quest with his capricious powers.

## Starting ZORK

The copyright notice and the serial number will appear, followed by a description of the starting location of the game:

```
Inside the Barrow
You are inside an ancient barrow hidden deep within a dark forest.
The barrow opens into a narrow tunnel at its southern end. You can
see a faint glow at the far end.
A sword of Elvish workmanship is on the ground.
A strangely familiar brass lantern is lying on the ground.
```

Whenever you see the prompt (`>`), ZORK is waiting for you to type in your instructions. When you have finished typing in your instructions, press the RETURN key. ZORK will respond and then the prompt (`>`) will reappear.

Next to the prompt (`>`), try typing the following:

```
>LOOK AT THE LAMP
```

and press the RETURN key. ZORK responds with this:

```
The lamp is turned off.
```

You may respond to ZORK by typing:

```
>TURN IT ON
```

and press the RETURN key. ZORK cooperates and tells you:

```
(Taken)
The lamp is now on.
```

Read the [Rules and Strategies](#rules-and-strategies) section for further directions and hints.

## Talking to ZORK

When you play a ZORK game, you talk to ZORK in plain English, typing in all your requests on your keyboard when you see the prompt (`>`). When you have finished typing a line, press the RETURN key and ZORK will digest your request.

ZORK usually acts as though your sentence begins with "I want to . . ." although you should not type those words explicitly. ZORK then displays a response that tells you whether what you want to do is possible in the current situation, and if it is, whether anything interesting happens as a result.

All words you type are distinguished by their first six letters and all subsequent letters are ignored.

ZORK understands many different types of sentences. Some examples:

```
>TAKE THE GOLD. DROP GOLD. PICK UP GOLD. PUT DOWN THE GOLD.
>GO NORTH. NORTH. WALK NORTH. N. WALK AROUND THE HOUSE.
>PUSH BUTTON. PUSH THE RED BUTTON. OPEN WOODEN DOOR.
>LOOK AT THE WALL. LOOK UNDER ROCK. LOOK BEHIND CURTAIN.
>LOOK IN BAG. READ A BOOK. READ ALL OF THE BOOKS.
>DROP ALL. TAKE ALL. DROP ALL BUT THE KNIFE.
```

You must separate multiple objects of a verb by the word AND or a comma. For example:

```
>TAKE ALL BUT THE KNIFE AND THE LAMP.
>PUT THE GOLD AND JEWELS IN THE TROPHY CASE.
>THROW THE NEWSPAPER, THE RED BOOK, AND THE MAGAZINE IN THE CHASM.
```

You can include several sentences in one input line if you separate them by the word THEN or a period. You don't need to type a period at the end of an input line. For example:

```
>TAKE BOOK. N. DROP BOOK AND CANDLE.
>TAKE THE BOOK THEN N. DROP BOOK AND CANDLE.
```

There are only two kinds of questions that ZORK understands: WHAT and WHERE. For example:

```
>WHERE IS THE GOLD?
>WHAT IS A GRUE?
```

You can tell or ask various characters to do something by surrounding the request in double quotes. For example:

```
>TELL COMPUTER "SPIN THE DISK"
>TELL THE GNOME "READ THE NEWSPAPER. TURN ON THE LIGHT"
```

It is also possible to answer a question or say something "out loud" in a similar manner. For example:

```
>SAY "HELLO SAILOR"
>ANSWER "A ZEBRA"
```

ZORK tries to be clever about what you really mean when you don't give enough information. If you say that you want to do something, but don't say what to do it with or to, ZORK will sometimes decide that there was only one possible object you could have meant. When it does so, it will tell you, by displaying, for example, (WITH THE ROPE). If your sentence is ambiguous, ZORK will ask what you really meant. Most such questions (for example: WITH WHAT?) can be answered briefly (for example: ROPE).

ZORK uses many more words than it "understands." ZORK's vocabulary consists of several hundred words which are nearly all you are likely to use when conversing with ZORK. However, ZORK's responses may tend toward "purple prose" at times, and ZORK will display English descriptions that it couldn't possibly analyze. Indeed, ZORK's response may refer to something to which you cannot refer (perhaps to your dismay). In that case, it is not essential to the story, and appears in ZORK's response only to enhance your mental imagery.

Completely mystifying sentences will cause ZORK to complain in one way or another. After making the complaint, ZORK will ignore the rest of the input line. Unusual events, such as being attacked, will also make ZORK ignore the rest of the sentences you typed, since the event may have changed your situation drastically.

*Note: the printed Zork II manual breaks off in the middle of the paragraph above, after "English descriptions". The rest of the paragraph and the one after it are restored from the Zork III manual, which uses the same text.*

## Rules and Strategies

### ZORK II: The Wizard of Frobozz

In ZORK II, you are placed at the entrance to a long-hidden region of the empire, a region under the control of the Wizard of Frobozz. The Wizard, formerly the personal sorcerer of Lord Dimwit Flathead the Excessive, still rules the cavern with an iron (though somewhat absent-minded) will. His great age has not impaired his magical skills (at least not too much).

Many strange tales have been told of fabulous treasures, exotic creatures, and diabolical puzzles to be found here. The aspiring adventurer had best equip himself with light (for the caverns are dark and gloomy) and weapons (for some of the inhabitants are unfriendly). Other tools and equipment may well be found (with luck) and used (with cleverness). Ancient manuscripts and other printed matter may well offer clues.

ZORK keeps track of your score as a rough measure of your skill in exploring. Points are gained by finding treasures and by gaining entrance to certain places. There is a penalty for dying.

In this story, time passes only in response to your input. You might imagine a giant clock that ticks once per move and the story progresses only at each tick. Nothing happens in the story while you are thinking and planning your next move, so you can plan your moves slowly and carefully if you so choose.

### Concepts for Exploring

Some things that you can do with objects in the story are not immediately obvious.

**Containment:** Some objects, called containers, can contain other objects. Some containers can be opened or closed, and some are always open. Some are transparent, and some are not. Most containers have a limited capacity, and all objects have sizes, so that it is possible to fill up containers. Similarly, some objects have surfaces on which other objects can be placed.

**Characters:** Some of the characters in the story can be talked to or even ordered around in a simple manner. See the section [Talking to ZORK](#talking-to-zork) for details. Characters in the story will also, as a rule, fight back when attacked. They may, in some cases, attack you unprovoked.

**Vehicles:** There are objects in the story that have the ability to transport you to mysterious regions that are inaccessible on foot. Needless to say, you face great personal peril in venturing into such regions.

**Directions:** The passages connecting rooms in the Great Underground Empire sometimes twist and turn unpredictably. You cannot always expect that, after going north, you can return to where you started by going south.

### Commands for Exploring

The best way to move from place to place is to type the direction you want to go. Acceptable directions are NORTH or N, SOUTH or S, EAST or E, WEST or W, NE, SE, SW (or NORTHEAST, NORTHWEST, SOUTHEAST or SOUTHWEST respectively), and also U or UP, and D or DOWN.

When you enter a particular place (ZORK calls any kind of place a "room") for the first time, ZORK usually displays the name of the room, a description of it, and then descriptions of any interesting objects in the room with which you might want to interact. When you return to a room, ZORK normally displays just the name of the room and the names of the objects in it.

The VERBOSE command tells ZORK to show the descriptions of rooms and objects every time you go there, not just the first time. The BRIEF command tells ZORK to fully describe only newly encountered rooms and objects, as it did initially. For moving through areas you already know well, the SUPERBRIEF command tells ZORK to show only the name of the room (even on your first visit there), and not even to mention objects in the room. You can always get a description of the room you are in and the objects in it by typing LOOK (or the abbreviation L).

### Suggestions for More Successful ZORK Playing

It is essential that you draw a map. Some of the problems in the game (the Maze in ZORK I, for one example) cannot be solved without mapping. Remember that there are 10 possible directions. In certain circumstances ENTER, EXIT (or IN, OUT) apply.

Read everything carefully. There are clues in some of the descriptions, labels, engravings, and books, etc.

Most objects in the game which can be taken are important, either as treasures or for solving problems. Sometimes treasures are also needed to solve problems.

Unlike other games with which you may be familiar, there are many possible routes to the successful completion of ZORK. There is no "correct" order for solving problems. Some problems have more than one solution, or don't need to be solved at all.

It is often helpful to play ZORK with another person. Different people find different problems easy, and can often complement each other.

Don't be afraid to try something bold or strange — you can always save your state first if you want. Trying the bizarre can be fun and often will give you a clue. A nonsense example:

```
>GIVE THE CATERPILLAR TO THE CHRISTMAS-TREE MONSTER.
The Christmas-Tree Monster is revolted at the thought of adorning
its branches with a caterpillar.
```

You have just learned that there is probably something which would be a decoration pleasing to the monster and possibly a solution to the problem.

## How to Quit

If you want to stop playing, and never continue from this particular position again, type QUIT. ZORK will respond:

```
Your score would be [score] (total of 400 points), in [number] moves.
This score gives you the rank of [rank].
Do you wish to leave the game? (Y is affirmative):
```

Type Y next to the prompt (`>`) and press the RETURN key.

If you never want to continue from this particular position again, but you want to keep playing, type RESTART after the prompt (`>`). ZORK responds by starting the game over from the beginning.

If you want to continue playing from this particular position, but at a later time, follow the [Saving a Game Position](#saving-a-game-position) instructions.

## Saving a Game Position

It will take you some time to play ZORK through to the end, just as it takes you some time to finish a good book. You will almost certainly not finish in one sitting. ZORK allows you to continue playing at a later time without having to start over from the beginning, just as you can place a bookmark in a book you are reading. There is a ZORK command, called SAVE, that makes a "snapshot" of your position in the game. If you are a cautious or prudent player, you may want to save your position before you embark upon (or after you finish) any particularly tricky or dangerous part of the journey. Having taken a snapshot, you can go back to that position even though you may get lost or killed afterward.

When the prompt (`>`) appears, type SAVE, then press the RETURN key.

## Restoring a Saved Game Position

When you want to continue playing from where you made a snapshot, follow the RESTORE procedure. You can RESTORE a saved snapshot at any time during play.

When the prompt (`>`) appears, type RESTORE and press the RETURN key. ZORK will now let you continue playing from your restored position. You can type LOOK for a description of where you are.

## List of ZORK Commands

To simplify your adventuring, you may order ZORK to give you information by typing specific commands. These commands can be used over and over again as needed, but they are each considered one complete move. Type your command as a sentence to ZORK after the prompt (`>`) appears.

| Command | What it does |
|---|---|
| `AGAIN` | ZORK will respond as if you had repeated your previous sentence. |
| `BRIEF` | Commands ZORK to fully describe only newly encountered rooms and objects. Rooms already visited and objects already seen will be described by printing the room name and the object names only. |
| `DIAGNOSE` | ZORK gives you a medical report of your physical condition. This is particularly useful if you have just survived a dangerous battle. |
| `INVENTORY` (`I`) | ZORK lists your possessions. |
| `LOOK` (`L`) | ZORK describes your surroundings in detail. |
| `QUIT` (`Q`) | Gives you the option to quit playing. If you want to save your position, first read the instructions under [Saving a Game Position](#saving-a-game-position). |
| `RESTART` | Ends the game and starts the game over from the beginning. |
| `RESTORE` | Restores a game position you saved with the SAVE command. See [Restoring a Saved Game Position](#restoring-a-saved-game-position). |
| `SAVE` | Saves a game position. See [Saving a Game Position](#saving-a-game-position). |
| `SCORE` | ZORK shows your current potential and the number of moves you have made. |
| `SCRIPT` | Assumes you have a printer. Commands the printer to begin printing a transcript of your game session. |
| `SUPERBRIEF` | Tells ZORK to show you only the name of the room you have entered, and no other information. It is briefer than BRIEF. |
| `UNSCRIPT` | Stops your printer from printing. |
| `VERBOSE` | Tells ZORK to show you a long description of the room and the objects in it whenever you enter a room. |
| `VERSION` | ZORK responds by showing you the release number and serial number of your copy of the game. |
| `WAIT` (`Z`) | Causes time in the game to pass. Normally, between moves, no time is passing as far as ZORK is concerned — you could leave your computer, take a nap, and return to the game to find that nothing has changed. WAIT is used when you want to find out what will happen in the game if you do absolutely nothing while time passes. For example, if you encounter an alien being, you could WAIT and see what it will do. |

## The Status Line

At the top of the screen, you will see a status line. This line is updated after every move to show your current whereabouts in the game.

**Score:** In games that keep a score, such as the ZORK underground adventures, the right side of the status line will show something like this:

```
SCORE: 245/920
```

The first number is your score and the second is the total number of moves you have made. In the example, you have 245 points in 920 moves.

## Appendix: ZORK's Responses

ZORK may occasionally have a few words for you when it wants you to clarify your instruction. Some of ZORK's responses are:

**I don't know the word [your word].** The word you typed is not in the game's vocabulary. Sometimes a synonym or rephrasing will be "understood." If not, ZORK probably doesn't know the idea you were trying to get across.

**I can't use the word [your word] here.** ZORK knows the word you typed, but the word made no sense where you put it in the sentence. "Open the take," for example.

**You must supply a verb!** Unless you are answering a question, each sentence must have a verb (or a command) in it somewhere.

**There is a noun missing in that sentence.** This usually indicates an incomplete sentence such as "Put the lamp in the," where ZORK expected another noun and couldn't find one.

**Too many noun clauses.** An example is "Put the troll in the basket with the shovel." A valid ZORK sentence has, at most, one direct object and one indirect object.

**Beg pardon?** You did not type anything after the prompt (`>`) and before you pressed the RETURN key on your keyboard.

**It's too dark to see.** In the story there was no light to see objects in the room.

**I can't see any [object] here.** In the story the object you referred to was not accessible to you.

**Multiple objects cannot be used with [your verb].** It is legal for you to use multiple objects (that is, nouns or noun phrases separated by "and" or a comma) only with certain verbs. Among the more useful of these verbs are "take," "drop," and "put."

**I don't understand that sentence.** You typed a sentence that is gibberish, for example: "Give troll with sword." You might try rephrasing the sentence.

## Command Summary

The following commands can be entered when the prompt (`>`) has appeared on the screen (for explanations, see [List of ZORK Commands](#list-of-zork-commands)):

AGAIN · BRIEF · DIAGNOSE · INVENTORY · LOOK · QUIT · RESTART · RESTORE · SAVE · SCORE · SCRIPT · SUPERBRIEF · UNSCRIPT · VERBOSE · VERSION · WAIT

## Sentence Syntax

- A ZORK sentence must contain at least a verb or a command (e.g. AGAIN).
- Separate multiple objects of the verb by the word "AND" or a comma (,).
- Several sentences typed to ZORK at one time must be separated by a period (.) or by the word "THEN". A period is not needed at the end of a line of input.
- Only two kinds of questions may be asked.
- Directions may be abbreviated to N, E, S, W, NE, NW, SW, SE, and UP and DOWN may be abbreviated to U and D, respectively.
- The letter "L" may be used to abbreviate the LOOK command.
- The letter "I" may be used to abbreviate the INVENTORY command.

# This Edition's Extras: Enhanced Language

## Enhanced Language Features

*An optional addition of this edition, not part of the original game. It is on when you first start; turn **Enhanced language** off in Settings (F2, then 8) to play with the original game's own parser alone, exactly as Infocom wrote it.*

The original game understands a lot, but it was written in 1980 and expects commands in its own style. The enhanced language layer lets you also type everyday English, such as WHERE AM I?, WHAT AM I CARRYING? or GO BACK. It sits on top of the original game and never changes it:

- **Zork comes first.** If the original game understands what you typed, it answers exactly as it always has, and the layer does nothing. The layer only helps when *Zork* would otherwise reply "I don't know the word…" or "That sentence isn't one I recognize". So everything the original game understands, including its jokes and its own answers to questions like WHAT IS A GRUE?, works as it always did.
- **Answers from the game look like the game.** WHERE AM I? is passed to the game as LOOK, so you get *Zork*'s own room description. Answers written for this edition, such as WHO AM I? and EXITS, appear in the same color as hints, so you can always tell them apart.
- **Questions to this edition cost nothing.** WHO AM I?, EXITS, WHERE IS THE … ? and the like take no move and are not recorded as a move for UNDO. Anything passed to the game counts as a move only if the original command would.
- **Capitals, question marks and polite words don't matter.** PLEASE, CAN YOU, COULD YOU, I WANT TO, I'D LIKE TO, LET'S, OK, NOW, FOR ME and a question mark or exclamation mark at the end are all set aside, and the original game still gets the first try at what is left, so adding PLEASE never changes who answers. PLEASE TAKE THE SWORD becomes TAKE THE SWORD.
- **Whole sentences work.** Words such as MY, THAT, THIS, QUICKLY, CAREFULLY or JUST are set aside wherever they appear, and each part of a sentence joined with AND, THEN or a full stop is understood on its own, then handed to the game the same way (GRAB THE LAMP AND SWITCH IT ON becomes TAKE LAMP AND TURN ON IT). Commands addressed to someone, with a comma (ROBOT, GO NORTH), go to the game exactly as typed.
- **It remembers what you have seen, and only that.** The edition notes where you last saw each thing, in a lit place you were in, and what you were carrying. That memory answers questions such as WHERE IS THE SWORD? and lets GO TO take you back. It never knows anything you haven't seen yourself, it is saved with your game, kept by UNDO, and forgotten when you restart.

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
| WHERE IS THE SWORD?<br>WHERE DID I LEAVE THE SWORD?<br>WHERE'S MY LAMP?<br>FIND THE TEAPOT<br>HAVE I SEEN A KEY? | Where you last saw it and how long ago: "You dropped the elvish sword in the Dark Tunnel, 3 moves ago." If you had it and it went without your seeing where: "…but you didn't see where it went." Never seen: "You haven't seen anything called "princess" yet." |
| WHAT DID I DROP?<br>WHAT HAVE I PUT DOWN? | Everything you have put down, where, and when |
| WHERE ARE MY TREASURES?<br>HOW MANY TREASURES DO I HAVE? | In *Zork I*: the treasures you have found, what is in the trophy case, what you are carrying, and where the rest are. (*Zork II* and *III* don't mark which things are treasures, so use WHERE IS.) |
| IS IT DARK?<br>IS THERE ANY LIGHT HERE? | Yes or no |
| IS THERE ANYTHING HERE?<br>WHAT CAN I TAKE? | Everything you can see here, by name |
| SEARCH THE ROOM<br>LOOK AT EVERYTHING<br>EXAMINE EVERYTHING | The game's own LOOK, then everything you can see here, by name. Nothing hidden is found this way: to search one thing, use the game's own SEARCH, or LOOK UNDER, IN or BEHIND it. |
| WHAT CAN I DO HERE?<br>ANY SUGGESTIONS? | The same suggestions as the command buttons, as sentences: ways to go, things to do here, and things to do with what you carry. Because these can point toward a solution, they need hints on, as well as command buttons. |
| HOW DO I GET TO THE BARROW?<br>WHICH WAY TO THE GAZEBO?<br>HOW DO I GET TO THE SWORD? | The way there, through places you have been: "From here to the Dark Tunnel (where you last saw the elvish sword): southwest, then south (2 moves)." For a thing, the way to where you last saw it. If no way is known (a one-way passage, or exits that change), you are told so. |

### Going somewhere: GO TO

*GO TO needs the map on (Settings, F2, then 4).*

GO TO THE BARROW walks you there, one real move at a time, through places you have already been. GO TO THE SWORD walks you to where you last saw the sword. It saves typing, not game time: every step costs a move, your lamp keeps burning and the game goes on around you.

- **Trips of more than 5 moves ask first** ("Inside the Barrow is 6 moves away by the ways you know."), with **No** as the default. Shorter trips just go.
- **It shows the trip, not every room.** The story shows one line for the walk, then the full description of where you arrive:

```
>go to the barrow
(Walking to Inside the Barrow, 3 moves: northeast to Foot Bridge, north to Narrow Tunnel, north to Inside the Barrow.)
Inside the Barrow
You are inside an ancient barrow hidden deep within a dark forest. …
```

- **It stops the moment anything happens**, and shows you everything the game said: anything you haven't seen in that place before (something dropped, or someone wandering about), anything the game says that a plain LOOK there wouldn't (a warning, a noise, your sword glowing), darkness, a change in your score, or a step that didn't lead where it should. Type the same GO TO again to carry on.
- **It never does anything for you.** It only walks, through ways it has checked on a copy of the game. If the way needs something done first, or you have no light where it's dark, it tells you it doesn't know a way right now instead.
- **One UNDO takes back the whole walk.**
- On arrival it reminds you of things you already knew were lying in the places you passed ("On the way you passed: the elvish sword in the Dark Tunnel."), and if you went to a thing that is no longer there, it says so.

GO TO is part of the enhanced language layer, so it is on and off with **Enhanced language** in Settings (F2, then 8).

### Typing mistakes

If the game doesn't know a word you typed, and it is close to the name of something here (or in your hands), to a direction, or to one of the game's everyday verbs, the edition reads it as that word and always says so:

```
>drop the swrod
(I took "swrod" to mean SWORD.)
Dropped.
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
| TOSS THE SWORD<br>CHUCK IT | THROW SWORD, THROW IT |
| STAB THE LIZARD<br>PUNCH IT<br>FIGHT THE LIZARD | ATTACK LIZARD, ATTACK IT |
| PEEK INSIDE THE BUCKET<br>LOOK INSIDE IT | LOOK IN BUCKET |
| EXAMINE THE BRASS THING<br>TAKE THE SMALL OBJECT | The one thing here or in your hands that the description fits, by a word in its name or one of the game's own adjectives ("the brass thing" is the lamp). If several things fit, you are asked which; if nothing fits, you are told. |
| USE LAMP<br>USE KEY ON DOOR | *Zork* has no USE, because it wants to know exactly what you mean. You are reminded to try a specific verb such as LIGHT, OPEN, UNLOCK, READ, WAVE or PUT … IN. The layer never guesses, because guessing could solve puzzles for you. |

### Talking to characters

*Zork* has its own ways of speaking to the characters you meet: TALK TO ROBOT, HELLO ROBOT, ASK ROBOT ABOUT something, and the name, a comma and an order (ROBOT, GO NORTH). The layer puts everyday ways of saying it into those forms. Whatever comes back is the game's own reply: nothing is made up, and a character who wouldn't talk to you still won't.

| You can type | What happens |
|---|---|
| SPEAK TO THE ROBOT<br>CHAT WITH THE ROBOT<br>TALK WITH THE ROBOT | TALK TO ROBOT |
| SAY HELLO TO THE ROBOT<br>GREET THE ROBOT<br>SAY HI | HELLO ROBOT or HELLO |
| ASK THE ROBOT TO …<br>GET THE ROBOT TO … | ROBOT, … (the game's own way of telling someone to do something) |
| ASK THE ROBOT WHERE …?<br>ASK THE ROBOT FOR HELP | *Zork* can't take questions put that way, so you are shown the ways it does understand |

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
| WHAT DOES THE TEAPOT DO?<br>HOW DO I OPEN …?<br>HOW DO I GET PAST THE LIZARD?<br>HOW DO I WIN? | Not answered, because the answer would solve a puzzle for you. You are pointed to HINT instead. |
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

*Means:* In *Zork I* this lists your treasures. This game doesn't mark which things are treasures, so use WHERE IS … instead. Needs the map on.

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

## Copyright

### The Original Game

ZORK™ and INTERLOGIC™ are trademarks of Infocom, Inc. © 1981, 1982 Infocom, Inc.

### This Edition

**Caldwell Z-Machine for Browsers Edition**  
Copyright © 2026 Jason Caldwell [zork.czm@fastmail.com]  
MIT License: free to use, copy, modify and distribute.

Game by Marc Blank and Dave Lebling of Infocom. Game file released by Microsoft under the MIT License. *Zork* is a trademark of its owner; this is an unofficial fan edition. IBM VGA font by VileR (int10h.org), CC BY-SA 4.0. The original manual text and pictures remain the work of Infocom, Inc.

---

*ZORK™ and INTERLOGIC™ are trademarks of Infocom, Inc. © 1981, 1982 Infocom, Inc. The Commodore 64 reference card (loading, disk, printer and troubleshooting instructions) and the French-language half of this bilingual manual are not included here.*

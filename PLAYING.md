# OTT — playing the game

OTT is a WW1 trench-warfare game. You are one soldier in one attack on the
western front, east across no-man's-land into the German line. There are five
battles to choose from, between December 1914 and September 1915, and you go
over once. There are no levels, no treasure, no experience points. The run
ends when your part in the attack is over — you get home, you are carried
back, you are relieved, you are taken prisoner, or you are killed — and the
next run is a new soldier. Death is permanent: there is no reloading an
earlier save to undo what happened.

## Starting the game on Windows

Unzip the whole OTT-windows folder anywhere you like (Desktop or
Documents is fine — keep `OTT.exe` and the `lib` folder together).
Double-click **Play OTT.bat** to play in letters, or
**Play OTT (Tiles).bat** to play with the WW1 tiles (see *Pictures
instead of letters*, below). A game window opens; choose
**New soldier**, type any name for them, and press Enter.

If Windows shows a "protected your PC" warning the first time (it does
that for any downloaded program it doesn't recognise), click
**More info**, then **Run anyway**.

You can also run `.\OTT.exe` from Windows Terminal in the unzipped
folder, if you prefer: `.\OTT.exe -t` starts it with the tiles and
`.\OTT.exe -c` in letters. With neither, it starts the way it was when
you last quit.

## Starting the game on macOS

Unzip `OTT-macos` and keep the folder wherever you like. Open
**OTT.app** to play in letters, or **OTT (Tiles).app** to play with the
WW1 tiles. They are the same app under two names — the word "Tiles" in
the second name is what starts it with the tiles, so keep it if you
rename that one. They share everything: your soldiers are kept in the
folder `OTT` in your Documents, and the window, font and graphics
settings in the app's own preferences.

The first time you open each of them, macOS stops it, because OTT is not
signed by a developer Apple has checked:

1. Double-click the app. macOS says it could not verify that "OTT" is
   free of malware (on macOS 14 and older: that "OTT" cannot be opened
   because the developer cannot be verified). Click **Done** — on
   macOS 14 and older, **Cancel** — and never **Move to Trash**.
2. Open **System Settings ▸ Privacy & Security** (on macOS 12 and older,
   **System Preferences ▸ Security & Privacy ▸ General**), scroll down to
   **Security**, and click **Open Anyway** beside the line about OTT;
   confirm with your password. On macOS 14 and older you can instead
   Control-click the app, choose **Open**, and then **Open** again.
3. The game starts. When macOS asks whether OTT may use your Documents
   folder, allow it: that is where it keeps your soldiers.

If you use both apps, do this once for each. Or, if you are happy in
Terminal, type `xattr -dr com.apple.quarantine ` (with the space), drag
the unzipped OTT-macos folder into the window, and press Return: that
clears both at once.

## Choosing your battle

A new soldier starts by choosing his battle, on a menu built like the one
Sil uses to choose a house. Each battle is listed by its date, and has a
few lines under it in the men's own words: the hour, the ground in front,
and what they have been told. Two battles can fall on the same day, so the
second says which ("10 March 1915 -- the village"); the Strongpoint and the
Sector each have two dates, and the menu shows the one this battle will be
fought on. Press a
battle's letter (`a` to `e`), or move the cursor with the arrow keys and
press Enter. `*` picks one at random. Escape stays on the menu; `O` opens the
game options and `q` quits. The cursor starts on the battle you chose last,
for as long as the game stays open. Then you give the soldier a name; Escape
at the name prompt brings you back to the menu. The character sheet (`@`)
says which battle he is in, and the ending screen has the battle's name over
it.

## The five battles

Every battle has its own ground, its own order and its own goal. What they
share: you start in our own trench at the far west edge of the field, the
attack goes east, and the battle ends the same ways (see *The goal, and
afterwards*, below). None of them is meant to be won easily, and which part of
it kills the most men changes from game to game: some crossings are cheap and
the attack breaks on the second or third trench instead.

### a) The Diversion — 25 September 1915

The morning of Loos. Further north, at Bois Grenier, Pietre and
Bellewaarde, attacks go in the same morning to keep the enemy's guns and
reserves where they are; yours is one of them. The battalion is ordered to
take the trenches in front of it, to the last line. Its order is issued at
2.40 a.m. and gives zero hour as 5.20 a.m. — the only battle whose order
says "zero".

*The ground.* Our trench and wire in the west, then no-man's-land: craters,
the old dead from earlier attacks, a rise or two. Their system is several
lines deep, wired in front of each line, with machine guns behind the
trenches (some of them up on a rise) and deep dugouts on the last lines.

*The goal.* Any part of their last line, the whole length of it, which is
marked on your map from the start. The first square of it you stand on
fires the flare. After that the second half of the game begins, and the
order to fall back comes only when the line has been held for a while.

### b) The Strongpoint — 9 May or 15 March 1915

Two companies of the battalion go over against one strong place in the
enemy's front line. On most days it is a moated Flemish farm, by Aubers
Ridge on 9 May 1915; the order names it, and gives its times the way the
Army wrote them in 1915. On the others it is the Mound, the spoil heap at
St Eloi, retaken at first light on 15 March 1915.

*The ground.* The farm is house, barn and byre round a yard, brick-walled and
loopholed on our side, with machine guns behind two of the loopholes and
mined cellars under the house. A moat runs round it with one causeway, to the
gateway on the enemy's side; there is an orchard and hedges on its flanks
and wire in front, with two lanes cut through it, shown on your map at the
start. The Mound has a trench round its foot, wire on its slope and two
machine guns in a covered emplacement on top; their crews come up to it from
the far side, and two lanes are cut through the wire in front of it. It is
high ground.

*The goal.* Stand in the farm's yard with nobody of theirs left on his feet
inside the walls, or on top of the Mound with neither gun in action — and
the flare goes up. Then a counterattack comes out of their support line; once
it has failed their heavy guns shell the place one round at a time, another
counterattack follows, and so does the order to fall back.

Some days the bombardment has broken the place: walls down, the farm's guns
buried or one of the Mound's hit, and more gaps cut in their wire along the
front. Then the crossing is cheaper, but the men inside are all still there.
On other days the shells bounced off, and the crossing is what kills. The
order does not say which.

### c) The Sector — 10 March or 16 May 1915

Neuve Chapelle. A short, heavy bombardment, and the whole frontage goes over
at once at 8.05 a.m. The battalion is ordered to take the enemy's front line
from one end of its sector to the other, and to hold it until relieved after
dark.

Or, in about half of the battles, Festubert, 16 May 1915: the same order, but
the whole frontage goes over at 3.15 a.m., in the dark, along tapes laid out
at dusk. At first you can see only four squares, and so can everyone else —
the machine guns too; the light comes slowly as the fight goes on, and by
about the hundred and thirtieth turn it is full day. The menu shows which
date this battle will be.

*The ground.* The Diversion's kind of field, with three lines of theirs: the
front line, the support line and the reserve. The guns did not cut the wire
everywhere. On the left — the north end of the line, a different length each
battle — the wire is whole (the map shows no lanes through it), and the
machine guns and the men holding that stretch were not touched.

*The goal.* Their front line, the whole length of it, with nobody of theirs
left on his feet in it — and you in it, on your feet, when that comes true.
There is no flare: word comes along the trench, and then the line has to be
held. Their guns find it, and their counterattacks come down the
communication trenches from the support line, how soon and how heavy
differing from battle to battle, each heavier than the last; a few more of
ours come up now and then. If enough of ours are still in their front line
when it is dark, the relief comes up and the battle ends with a roll call. The
relief does not come out past their front line: if you are out beyond it,
among their support and reserve lines, you are ordered back instead. If too
few are left, or nobody of ours is left in the line at all, the order is to
get back.

### d) The Village — 10 March 1915

Neuve Chapelle again: the battalion goes over at 8.05 a.m. as the guns lift
off their trench onto the village, and is ordered to clear the village house
by house, as far as its eastern edge, where the road leaves it.

*The ground.* Ruined brick houses along a main street and two or three cross
streets, gardens and hedges behind them, cellars under some of the houses,
and the church near the middle with its churchyard. Inside a house the roof is
gone: the floor is open ground, and the walls are the cover — many of them
knocked down to rubble you can see and shoot over but not climb through. The
houses are held, and some of the cellars too, and the garrison has joined
them with saps dug across the gardens and the streets. The main street is
barricaded, with a machine gun behind each barricade firing down it. The
church tower is climbed from inside the church; from up it you see three
times as far, over the whole village, and they have a gun up it. Sometimes the bombardment has knocked flat the houses on the village's
western edge — a cheap way in, with the fight in the streets beyond it at full
strength; sometimes they are still standing, loopholed, and the open ground
in front of them is the worst of it. The battalion order says which.

*The goal.* The village's eastern edge, the road out. It is marked on your map
from the start, with the village's streets and the church. Reach it and the
flare goes up; once their counter-wave has failed, their heavy guns go for the
tower first, and a shell that finds it brings it down with whoever is in it.
The rest of the battalion follows the first wave over in more waves, by the
timetable.

### e) The Wood — 19 December 1914

Ploegsteert Wood. The battalion goes into the wood from its trench along the
western edge at half past two in the afternoon, to clear it of the enemy as
far as its eastern edge.

*The ground.* Too wet to dig, so the enemy holds the wood from breastworks —
a firing position behind a bank of earth and sandbags — with an abatis of
felled trees and wire in front of each, and communication breastworks running
back between them; his support line is out in the fields beyond the wood. The
wood is trees, undergrowth, stumps and fallen trees, clearings and shell holes,
many of them full of water. Straight rides are cut through it: one east-west
through the middle, one north-south behind each breastwork. His machine guns
are laid down the rides, and where they cross there is a strongpoint: a gun,
and riflemen in pits round it. Snipers lie out in the wood behind his first
breastwork, in the undergrowth and among the stumps. Most days the guns have
shredded the wood: most of the trees are down, and the ground is open and
deadly to cross. Some days they have left it thick: you see a few yards, the
trees come right up to his wire, and the fight is close. The rides, the
eastern edge and his first breastwork are on your map from the start, and so
are the lanes through his first abatis.

*The goal.* The eastern edge of the wood. Reach it and the flare goes up;
their heavy guns come down on the edge one shell at a time, and their supports
come at you across the fields.

## Your first minutes

Before the first turn you are shown the lines as the battalion goes in —
when the order came up, when the battalion goes and after what, the
objective — and then the battalion order: the hour of the assault, the
objective, the barrage, the waves, and what is to be done with the ground if
you take it, in the words and on the clock of the day. It is the plan. Plans
of this kind were written the night before by men who would not be crossing.
(On a window as short as an 80x24 terminal the order is shown a page at a
time; the prompt says when there is more.)

Then you are on the map in your own trench, at the far WEST edge — the `@`
is you. Everything happens eastwards from there. Your briefing is on the map
from the start: the enemy front trench, the cut gaps in their wire, the high
ground (the grey `o` and `O`: see *High ground*), and the goal — whatever
the battle's order says it is. You know nothing else about the ground ahead;
in The Diversion the enemy system runs several lines deep, wired in front of
each one. Every trench and every communication trench is at least two tiles
wide, so one man standing in it does not block it; the trenches back there
are wider still in places. The men of your own side step round you, or
change places with one another, as you can with them.

Dugouts (`D`) are cut into the back wall of a
trench: most are a single square, some are chambers of two to six.  You can
only step into one from the trench itself or from another
dugout square, and the only way out is the same way you came in. Inside
one you are safe from almost anything and can see nothing but the chamber
you are standing in. Stepping onto a dugout from open ground is another
matter: that puts you on its roof, in the open, seen and seeing like anywhere
else on the surface, with no cover from it. Some of their dugouts still have
men in them, sitting it out: they make no sound and take no part in the
battle until somebody comes to the mouth of their own dugout, and then they
come up fighting. Where their system has them, the dugouts in its last two
lines are mined, deep enough that no shelling touches them, and each has a
squad of bombers below, which comes up when you reach its mouth, when you get
as far as their second-to-last line (all of them at once), or in its own time
late in a long battle. Other letters are soldiers, yours and theirs — many of your own have
names. You see your own men the way you see the enemy: in your line of sight,
and not otherwise.

Walls of text are messages; press Enter when `-more-` appears.

**Your job is to reach the goal of your battle.** In four of the five that
sends up the flare, and what happens after that is the second half of the
game, and it is not the easier half. In the fifth, the Sector, you take a
line and hold it.

Do not linger. An officer keeps the jumping-off trench moving: stay in it
too long and you will be warned twice, and then you will not be warned
again. Stepping out in front of our wire and back in counts as staying; only
going on past it does not. With nobody of ours near you, the warnings come
from one of our own snipers on the parapet, and so does the shot. A shell
hole is no place to hide, either: lie up unhurt in a deep one where one of
ours is near enough to see you and you are warned twice, and then the
officer's revolver comes out. If nobody is near, nobody minds. Nobody is
going to call you back — there is no recall in any battle. Short of the
officer's revolver and that sniper, our own side cannot hurt you: no rifle,
machine gun, grenade or bayonet of ours will ever wound you, however close you
stand to the men working them.

The whole game is played with the keyboard.

## Keys

Movement: the arrow keys or the number pad, in eight directions. `5` or
`z` waits a turn; hold shift to keep walking. Move into an enemy to fight hand to hand. Any blow may stun the man it
lands on. Men beside you count for a lot in a bay fight. From a shallow
trench it is awkward to reach a man standing on the lip above you; from a
deep one it cannot be done — shoot him instead. A wounded man's legs do
not always do as they are told: a step may fail, and the turn is gone.

| Key | Action |
|-----|--------|
| `C` | dash — `C` and a direction: one quick step, half a turn, not into anybody; whatever you do next takes half a turn too, unless it is another step |
| `f` | aimed rifle fire — a target, or just a direction (or work the machine gun, if you are on one); `z` instead of firing aims |
| `b` | work the bolt — a turn, after a shot (`B` too; `w` with the hjkl keys) |
| `R` | reload — a charger of five rounds into the rifle |
| `g` | ready a grenade — a turn; held four turns more, it bursts in your hand (`G` too) |
| `t` | throw the readied grenade (move the cursor, `t` throws, `ESC` stops) |
| `H` | apply a field dressing — press it three turns running (`h` too; `d` with the hjkl keys) |
| `s` | search a dead man's pockets (your tile or next to you) |
| `p` | lift or set down a wounded man |
| `,` | lift or set down an abandoned machine gun (`8`, yellow) |
| `M` | work a machine gun standing on your own square |
| `S` | shout — the men behind you come up to you; or call for help if you are hurt |
| `U` | surrender — once you have been overrun and told so, once the order to fall back has come, or when you are the last of us alive (`^U` with the hjkl keys) |
| `i` / `e` | your kit |
| `l` | look around (`^L` with the hjkl keys) |
| `x` | examine something |
| `W` | the whole battlefield at once |
| `@` | your record |
| `?` | help — four pages: the keys, the soldier, the attack |
| `^S` | save (Ctrl+S) |
| `^X` | save and exit (Ctrl+X) |

The keys are the same in every keyset (the options menu has two switches for
them: movement on `hjkl` and a keyset closer to Angband's), with one exception.
With the hjkl keys `b`, `B`, `h`, `H`, `U` and `l` are steps and runs, so the
bolt is worked with `w` (or `^B`), a wound is dressed with `d`, you surrender
with `^U`, and you look around with `^L`. `W` shows the whole field there too.

Any of these can be put on another key: the options menu (`O`, or `=` in the
Angband keyset), then **Key Bindings**, lists them with the keys that do them
now. Pick one and press the new key; the old one goes on working unless it is
the key you moved. `r` there puts every keyset back as it was. The bindings
are kept in `ott-keys.prf`, in the same folder as `ott-debug.txt` (see *Debug
mode*).

Saving is for stopping and coming back later. When the run ends, it ends.

## Firing

`f` asks for a direction: `f` again takes the closest man you can shoot,
`*` cycles through them, `ESC` puts the rifle down. Only the enemy is ever
offered — your own battalion is advancing all around you and the game will
not aim at them for you. Your rifle reaches twenty-five squares, and on open
ground you see as far as it reaches; theirs reach twenty. A shot straight
after a dash (`C`) falls off with the range twice as fast.

**Taking aim.** At the same prompt `z` aims instead of firing: it takes the
same man `f` would and spends the turn laying the sights on him, with no
round fired. The next shot at him is twice as likely to hit — or half as
likely to miss, whichever is less — and a second aim does it again (a 20%
shot becomes 40%, then 70%). `z` inside the `*` targeting picks a man and
aims at him. The left of the screen says `Aim` or `Aim 2` beside the bolt.
Do anything else with the turn, or lose sight of him, and the aim is gone.

You can also just give it a direction. `f` and then a movement key fires
down that line: the first of theirs on it is the man you were shooting at,
and if there is nobody on it the round goes off down the trench anyway. It
still costs the turn and the round. So does pulling the trigger on an empty
magazine — you find out it is empty by finding out, and that takes as long
as anything else does.

**The bolt.** The rifle is a bolt-action. Every shot leaves the spent case in
the chamber, and the rifle will not fire again until you work the bolt with
`b`, which takes a turn. Pull the trigger with the bolt still open and the
turn is wasted. The left of the screen says `Bolt open` or `Bolt shut`, just
above your rounds. A charger (`R`) goes in with the bolt back and leaves it
shut; working the bolt on an empty magazine closes it on nothing. Every other
round you fire needs a shut bolt too — the point-blank shot at a man who
rushes you, the round you put into a man as you step back from him — and
leaves it open. A shot that kills a man, or very nearly does, leaves the
bolt shut: you have worked it before he is down. There is no free second
shot. Everybody else works the same bolt, and gets the same free bolt.
Ours and theirs alike spend a turn on it between shots, so there is less
rifle fire on the field than there might be.
Machine guns are belt-fed and fire as they always did.

The closer he is, the worse it is for him: an aimed shot gets steadily more
accurate and more likely to kill outright as the range closes, and into the
next bay it is very nearly certain. That cuts both ways. A trench is ninety
percent cover from fire coming across the open, but not from a man down in
the same ditch as you — between two bays there is nothing in the way.

You go over the top with a dozen grenades and one field dressing. That is
the first-line assault load: the men of the first wave are being sent into
a trench, and the trench is fought with the bomb. The waves of ours that
follow carry two apiece. One dressing is what was sewn into the tunic — if
you want another you take it off a body. You can carry no more than twelve
grenades and two dressings: what you find past that stays where it is.

A grenade is readied before it is thrown: `g` lights it, or pulls the pin,
and takes the turn, and from then on it is going to go off. `t` throws the one
in your hand, and only that one; four turns after you readied it, if it is
still in your hand, it bursts there. You cannot put it back. The left of the
screen counts it down beside your rounds, `Fuse 4` to `Fuse 1`. Everybody
else readies his first too, so a bomber spends a turn before his grenade
comes over.

Grenades (`t`) are thrown at a place, not at a man, and they do not care
whose side is standing there — though you will not throw one where it
could only hurt our own. A grenade that bursts in a trench stays in the
trench: it does not touch the open ground beside the ditch, and the blast
runs further along the bay instead. A deep trench is proof against a
bomb bursting on the ground above it. Only a few of theirs carry grenades:
the bombers, a dozen each, and any party of four or more of them has one
at least. The rest are riflemen with none, and in their front line they
keep their fire on the lanes through the wire. Ours, and their bombers,
keep one grenade back for a stalemate round a traverse; nobody finds more.

A trench with men in it is fought for along the trench. Both sides bomb
round a traverse at somebody they cannot see in their own ditch and come on
after the grenade, up the bay, north or south along the line. Being under
fire slows that down; it does not stop it, because a trench is cover the
whole way and there is nothing to leave. A man two paces up the ditch from
an enemy, with no round ready, does not stand there working his bolt: he
dashes in with the bayonet. What that means for you: a bay you
have taken is never quiet for long, and the men round the corner are coming.

## Ammunition

The rifle holds five rounds and you carry thirty chargers of five. The
sidebar reads `Rds 5/30`: rounds in the rifle, then chargers left. `R`
thumbs a charger in — it costs a turn, it cannot be done with a full
magazine, and it leaves the bolt shut. Firing at somebody costs a round.
Their riflemen work the same bolt: five in the rifle, ten chargers on them,
and a turn to reload when it runs dry.

Only our own dead carry ammunition that fits. Theirs is a different
calibre.

## What matters

There are no hit points. A hit strikes a part of the body, lightly or
badly. Wounds bleed; a dressing stops or slows it, and getting one on
takes three turns of standing still. Pain slows you and spoils your aim,
and being wounded at all slows you further. A man too badly hurt to move
can be carried.

Some light hits are only grazes and bruises: a spent fragment, a round that
glances off. They hurt like any light wound but do not bleed, and there is
nothing to dress. Severe wounds hurt, as well as bleeding. For a while after
the first hit you hardly feel it: pain costs you half what it will, and you
are told once when it turns. Enough pain at once — a severe wound and a light
one, say — can black you out for a few turns, and it gets likelier with every
step of pain past that.

**Losing blood does not finish you at once.** When your blood loss reaches the
point where a man goes down, you faint instead — for anything from a few
minutes to a long while — and then you come to, as hurt as your wounds make
you. While you are out you are down in every way that matters: you can be
dragged in, nobody takes aim at you any more (though the guns and the shells
sweeping the ground can still find you), and if it happens in our own trench
you are carried back. But as long as you have lost that much blood you may go
under again at any moment, and it does not get better. It takes a good deal
more blood again to kill you outright. A severe wound to the head or the
body still puts you down for good.

While you are down the messages stop waiting for a key. After the first one,
which waits so that you see you have gone down, each line stands for a moment
and goes on by itself, and the battle is shown going on without you. Keys
you press while you are down are thrown away at the next line that goes by on
its own, so none is left over to answer that first message or to move you when
you come to; the line that says you are dead, and the screens after it, still
wait.

The sidebar lists every part that is hurt, one to a line and in plain
words: `Left arm: severe, bleeding`, `Right leg: light, stopped`. Light
wounds are yellow, bad ones red; a bleed that has been stopped or dressed
goes blue. Above the list are the state you are in, and `P:` pain and
`B:` blood lost against what you can afford to lose.

**A bayonet that goes in properly kills.** In a trench fight a clean hit
-- yours or theirs, and between two of them as readily -- is not a wound
to be dressed later. It is over, and you are told what did it.

**Aimed rifle fire is the deadliest thing you own, and it gets worse the
closer you are.** At arm's length it will very often kill outright; the
edge falls away with every yard until, at six squares and beyond, it
settles at three times what it once was. Two men in the same trench get
no cover from it at all — down in a bay, the ditch is not between you.

Shooting at a man makes him look for you next turn, unless one of ours is
already on top of him.

**Running the last few yards is its own decision.** Come onto a square
next to a man at a run — four steps in much the same direction and you are
sprinting, whether you meant to or not — and three times in four you get
the bayonet in first, before he can do anything about it. But every one of
them you have just come alongside gets a quarter chance of putting a round
into you at arm's length, and that is per man, every time. Closing on one
is worth it. Closing on three is how people die.

**What a man happens to be.** Nobody in this game learns anything. What
you are was settled before the whistle went, and so was what the man in
front of you is. Beside the small innate differences in eye and nerve,
about a third of everyone on the field — you, our men, theirs — can put a
man off his feet with the weight of a blow; half of them steady onto a man
they have already swung at once; a quarter have the knack of setting the
bayonet to receive somebody coming at them, which is what waiting (`z` or
`5`) does; one in ten is hard to hit having just moved; half will put a
round into a man as they step back out of his reach, which costs them a
round like any other shot; and one man in a hundred gets steadier the worse
his wounds get. You are never told which of these you have and you cannot
change any of it. It is the difference between two privates.

Setting the bayonet works round a corner: a man who comes into reach from
somewhere you could not see gets jabbed at just the same. It is also a good
way to be noticed. A bomber who can see what you are doing, and has a
grenade left, may throw it at you.

Time in the open kills. Machine guns fire on anyone in their sight every
turn; a barrage does the same wherever it is falling. Their guns stand
behind their trenches, firing over them — up on a rise where there is one — so
they cannot be rushed at the wire: the trench in front of them has to be taken
first. A trench is cover.
A shell hole is cover from bullets, less so from shells. Wire holds you
in place under fire — the cut gaps are marked, and they are watched. The
guns and the wiring parties cut more lanes than they used to, and the
battalion goes through them rather than at the wire; a lane is the fast
way across and the obvious place to be shot, both at once. Our own wire is
another matter: you know the lanes through it.

Standing hard against a parapet, a wall or a gun emplacement puts it between
you and the fire coming from the far side of it — whichever side of it you
are on, north, south, east or west. That pocket of dead ground is as deep as
the thing casting it, and it shelters you only from a man who is actually
beyond the obstacle: one standing level with it, or in the gap between you
and it, has you in the open. A crater is a hole to lie in, not a wall, and
casts none.

Rubble (`&`) is low. You cannot walk through a heap of it, but you can see and
shoot over it — except into the dead ground right behind it: each piece hides
the one to three squares at its foot from anyone on the far side, and a man
lying there cannot see over it either. That pocket is also its cover against
rifle and machine-gun fire.

**High ground.** Some fields have rises on them, drawn `o` (a slope) and `O`
(a crest) in light grey — a shell hole's letters are brown — and your map
shows you where they are from the start. You can walk over them. A rise hides
whatever is behind it from anyone lower than it, for sight and for fire alike:
from the flat you cannot see past a hill, from a slope you cannot see over the
crest, and from the crest you see down every side. Anyone on high ground sees
three times as far, and picks a man out of a shallow trench at three times the
distance; weapons reach no further than before. A shallow trench running
through a hill is high ground too. In The Diversion and The Sector one rise
always stands behind one of their lines, with that line's machine guns on it,
and another lies out in no-man's-land, dead ground for the men crossing behind
it. The Mound is a hill of its own, and the Village has its church tower; the
farm, the Village's streets and the Wood have no rises.

The big craters have a bottom to them. A shell hole (`o`, brown) is a scrape
to lie in; the middle of a really big one is a hole with sides, drawn `O`, and
down in it you can see the rest of your own hole and its rim, and nothing
else at all — which also means nothing beyond the rim can see you. It is
as good as a trench against bullets. Some of them have water standing in
the bottom (blue `~`): wading in costs you double, and a man who goes down
wounded in one is face down in the water and has about six turns. Grenades
still arc in.

There are two kinds of trench. A deep one (`=`) is blind: from the bottom
of it you see the lip, the trench itself, and its edge a few yards along,
and that is all — and nothing sees you either. A shallow one (`-`) sees
out like open ground, and a man in it can be shot from the open — but
past four squares he is a head above a parapet, and the further off the
less likely anyone picks him out. None of that applies down the trench
itself: if the ground between you and him runs trench the whole way, you
are two men in the same ditch and you see each other plainly, however far
along it he is — and so does he see you. A gun emplacement, and any
machine gunner wherever he is dug in, counts as a shallow trench. From a
crater you see into a trench only across other craters and trench.

Smoke and morning fog (`~`) hide whatever is behind them, both ways, and
there is more of it than there was: banks of mist drift slowly across the
whole field all battle. Shells throw up smoke and dig new craters as they
fall. Within two squares of you the fog hides nothing: you see the ground
and the men there, and they see you — but a man further off still cannot see
you in it, nor you him.

Every shot fired marks where it came from with a silver dot, a little off
if it came from far away; a machine gun's dot flickers. Every wound marks
the man who took it with a red dot, or a yellow one if it was only a
scratch — if he is within forty squares of you. The dots stand until you
next spend a turn, and then they all go. A man who has just fired at you is
drawn in violet for your next two or three turns (not with pictures instead
of letters). A dot is never drawn over a man: if
somebody is standing on the square you see him, not the mark. A man of either
side who is badly hurt and has stopped moving is
drawn as `w`; look at him (`l`) and you will be told what is wrong with
him, plainly. A shell landing close enough deafens you, and then the dots
are only what you can see.

**Blasts leave men stupid.** A grenade or a shell that reaches you at all
usually leaves you *stunned*; on the square the thing actually burst on it
is a *heavy stun*, and so is a shell that comes into the bay with you.
A blow to the head does the same — a bad one almost always. Stunned, you
are two points worse at hitting anything and two points easier to hit;
heavily stunned, four. It wears off over a handful of turns and you are
told when it does. The word for it is at the top of the left-hand column,
under your name, with `Fast` or `Slow` beside it when you are either.

It works the same way on everybody else, which is what grenades are for.
Look at a man (`l`) and you will be told if he is stunned or heavily
stunned. A stunned soldier will not throw a bomb and will not get up and
run at you; a heavily stunned one does nothing at all until it passes.
A man deep in a dugout is proof against a blast, and so against the
concussion of it.

**Concussed.** A knock on the head, a bomb going off at your feet or a heavy
shell bursting close can leave you *concussed* for the rest of the battle: the
word in the left-hand column says so, and the stun never wears off below a
heavy stun. You can fight on — one step in five goes wrong — but you are
worse at hitting and easier to hit for the rest of it. A shell that bursts right
beside you does far worse: you are hit in several places at once and you will
not get up again.

The dead (`%`) stay where they fall, all of them, for the whole battle:
nothing is buried and nothing is cleared. Searching a man's pockets takes a
turn and sometimes finds a grenade or a dressing. It costs something
else every time. Out in no-man's-land and on the wire lie the old dead, from
earlier attacks, the same brown as the mud. There is nothing left on them to
search for, and they are nobody's dead.

Shots that only just miss you are said: a round cracking past your ear, a
burst stitching the ground short of you, one a turn at most. Lying wounded,
a body falls across your legs only when a man is really killed on a square
next to yours.

**Shouting.** `S` calls the men behind you on: every man of ours within
earshot — a dozen squares or so — who is west of you comes up to you for a few
turns, by the trench where there is one. If you are bleeding, the nearest man
may come and put a dressing on you.

Fresh men come up the line on both sides, but not on the same terms. (This
is The Diversion's way of it; each other battle's order sets out its own
waves. A wave comes over whole, and it is announced only when it is a real
wave and you are near enough to hear it.)
Ours are bought with ground: each wave goes over when the attack has
taken another stretch of it, and they cross at a run. A second wave
follows the first over the top a few turns behind it, whether the ground
has been bought or not. Theirs come up the communication trenches on a
clock nobody can read, and you hear the grenades before you see them.

Each of those first two waves of ours is answered. Their second line
empties — groups of them coming up out of the dugouts, north and south
together, and working forward down their own trenches toward the front
line with grenades. Their counterattacks come through their own trenches,
down the communication saps and along the fire bays to wherever our men are
holding; the garrison of their deeper lines stays in its trenches and holds
them. Taking their front trench is not the end of anything.
Holding it is the fight — and holding it too long is its own mistake.
Their gunners know exactly where their own trench is. Sit in a captured
line with a few others for long enough and a ranging shell will tell you
what comes next; the ones after it arrive on a clock, and they keep
arriving until the line is empty or you are. The only way this battle
knows to go is forward.

If the attack gets halfway, machine gun teams of ours come forward with a
wave. If a team is killed — ours or theirs — the gun stays where it fell,
drawn as a yellow `8`. Step onto it and press `M` to take it over. It
fires a wide burst as far as you can see — from a hill, a very long way —
and while you are behind it you are the loudest thing on the battlefield.
`M` again gets you off it.

A gun on the ground can also be moved. Stand on it and press `,` to get it
up onto your shoulder; press `,` again to set it down on a trench, a
parapet, a crater or open ground, and that square becomes a gun position
anyone can work — you, standing on it, and any soldier of either side who
ends up standing on it, ours or theirs. It is a two-man load and you are
one man: every step under it costs three times what it would otherwise,
you cannot run with it, and you cannot carry a wounded man at the same
time. Lifting a gun takes the emplacement with it and leaves the trench behind, if
it stood in one, and bare ground if it did not.

## The goal, and afterwards

You carry one signal flare. In four of the five battles, reaching the goal
(see *The five battles*) sends it up: the first square of the goal you stand
on is the one you fire it from. Then the second half of the game begins.
A counter-wave comes for the man who fired the flare at once; their heavy
guns take longer. There are some turns to make the place good first — and
some days, and always at the Strongpoint and the Village, they wait until that
counter-wave has failed, and another one comes after them. Then they come
down on the place — one shell at a time, not all at once — and the battalion
is left holding what it took, under them. The counter-wave forms
up out of your sight, further along their line or behind it, and comes on
along the line at you: you see it coming, and there are turns to fire, bomb
and fall back along the bay before it is on you. In The Diversion the guns
are the ones the diversion was meant to draw. Their snipers look for movement
whenever you are in the open inside their position.

The order to fall back does not come at once. It comes only after the place has
been held for a while, when it is plain that nobody is coming up behind you,
and it is: "Get back." From then on our own men in their system start back,
and surrender is possible. Going home before
the order is not held against you: once the goal is taken the officer's count
against hanging back and the shot for lying up in a deep hole are lifted.

In the Sector there is no flare. The line is taken when the last man of theirs
in it goes down with you in it, and the second half of the game is the hold:
see *The Sector*, above.

Getting home once the goal is taken — with the flare fired, or in the Sector
with the line taken — is what this game calls surviving; in the Sector, so is
being relieved.

You can also be taken out of it before that. Come back into our own trench with
a bad wound on you, or with more than half your blood on the ground behind you,
and hands take hold of you and you go down the line to the dressing station: the
war is over for you, or you are back with the battalion in a week or two,
depending which of the two it was. A scratch does not get you out of anything
-- the officer is still there, and the attack is still going forward.

The last man home is another matter, and only before the goal is taken (after
it, getting home is getting home). Get back into our own trench, after going
over the top, when nobody else of ours on the field is left alive and
unhurt, and the battle is over for you whatever your wounds. Unhurt, you are
kept on the line, put on the fire step with what is left of the battalion;
carrying a wounded man in earns you a medal, and the ending tells you what
became of him; wounded, you are sent down to the aid post and are back with the
battalion in a fortnight or a month. Two or more light wounds, at least one of
which has bled, will send you down the line before the goal even when you are
not the last. A
man who never left our trench is never the last man home, however many of ours
are down: the officer has him.

In The Diversion and The Sector, beyond their last trench, on the open ground,
there is a butterfly (`"`). It is being watched.

When you die you are shown the whole field, every body on it, and the man who
did it — or his body, if he is dead too — or what it was: a shell, a sniper,
the wire. At the end every screen waits for a key; any key but `z` goes on, so
holding `z` down to wait does not throw away the screen you died for.

`U` surrender is possible in three cases. If you are surrounded for long
enough — twenty more of them than of us west of you, you deep in their
position, and the battle well along by then — you will be told you have been
overrun, and `U` becomes possible for the rest of the fight. It becomes
possible, without a word, once the order to fall back has come; and when every
other man of ours on the field is dead. It is not a way out so much as a
different way of finding out. A man you have already hit, or one standing over one of
his own dead, does not take you prisoner. With the rest of them it is a
chance, and it is theirs to take or not.

The ways this ends: you get home, you are carried back or sent down the
line wounded, you are relieved, you are taken, or you are not. What is wrong
with you when it ends decides which account of it you are given — both legs and
a head wound and a chest are four different rest-of-your-lives, and a man who
drowned in a foot of water in a shell hole gets his own page. A severe wound to
an arm or a leg is usually saved: weeks in a base hospital in France, the
boat, a hospital at home, a convalescent home, and a medical board at the end
of it, which may send you home or back to the front.

The account also knows which battle you fought, and when. A man wounded in
Ploegsteert Wood in December 1914 goes to a clearing hospital, not a casualty
clearing station; the base hospitals of 1914 and the spring of 1915 are not
those of the summer; a prisoner taken in the first half of 1915 was held
nearer four years than three. A private's family hears of his death by the
Record Office's letter, not by telegram.

If you do get home with the flare fired, you are told afterwards what came of
the attack. In The Diversion, on the morning of Loos, you are told it was a
diversion; in any other battle, as flatly, what came of your own.

## Debug mode

Not part of playing, but part of the game: `Ctrl+A` opens the debug
commands. The shipped builds warn you and ask for a password first; the prompt
comes with a hint already in it, "Someone who might have stopped it" (Enter on
the hint alone is refused). The answer is a man's name: `Jaures` or
`Jean Jaures` — an accent that cannot be typed is simply left out — or the old
`Gondolin`. Capitals and spaces do not matter. Three things
about it are worth knowing.

It stays on. Once you have entered debug mode, a small file
`ott-debug.txt` is written in `lib/user` (on macOS, in the `OTT` folder
in your Documents), and every soldier you start
after that begins in debug mode — no prompt, no password, and the run
marked as debug from the first turn. Delete that file if you want the
prompt back.

`Ctrl+A` then `G` turns **God Mode** on and off, and it is also on the
debug options page (`Ctrl+A`, then `O`). With it on, nothing that happens
to you takes: no wound, no bleeding, no shell, no sniper, no officer's
revolver, no ending that kills you outright. The battle goes on around
you exactly as it would have. `GOD` shows near the top of the sidebar,
under your name, while it is on. It stays on for the rest of that soldier's
game, and a new soldier starts without it.

It can stage the end of a battle without fighting the length of the field.
After `Ctrl+A`: `R` fires the flare where you stand and brings their guns down,
as if you had reached the goal (the Sector has no flare of its own; use `B`
there); `B` stands you on the first square of the
battle's goal that a man can stand on (your own row first) and runs the
arrival there as a step would — in the Sector and the Strongpoint, where the
goal is a state of the field, it says "Nowhere on this map is the goal just
now" until that is true — and once the goal is taken, stands you on the
butterfly instead, where the battle has one. `Y` moves you: it asks for `y x`,
or `r dy dx` for so far from where you are. `K` pulls the nearest man up beside
you, and `J` dumps the state of your wounds. Wizard mode itself
(`Ctrl+W`) is asked for separately.

## Pictures instead of letters

The game is drawn in letters by default and reads perfectly well that way.
If you would rather see it, OTT ships its own WW1 tileset: mud, craters,
wire, sandbagged trenches, dugouts, smoke, and soldiers of both sides.
Ours are light blue and theirs the enemy colour, exactly as the letters
were, and you have a white outline nobody else has, so you can always find
yourself. Ground you remember but cannot see at this moment is drawn
duller than ground you can see. Everything 0.9 added has a tile of its own:
the high ground (pale chalk, the slope hatched and the crest plain and paler),
the old dead (gone the colour of the soil, the bone showing), and the new
battles' ground — brick walls and their loopholes, the floors of the ruined
houses, hedges, covered gun emplacements, roads, barricades, the church tower
and its graves, undergrowth, abatis, breastworks, fallen trees and trees.

- **Windows:** **Play OTT (Tiles).bat** always starts the game with the
  tiles and **Play OTT.bat** always in letters, whatever you chose last
  time. To change over while you play, use the game window's
  **Options ▸ Graphics** menu: **WW1 Tiles**, or **Classic ASCII** to put
  the letters back. That menu works once you are on the map, waiting for
  your next move; before then (the start menu, making your soldier, the
  battalion order) it is greyed out.
- **macOS:** **OTT (Tiles).app** always starts with the tiles.
  **OTT.app** starts in letters until you choose otherwise: in the menu
  bar, **Settings ▸ Graphics ▸ WW1 Tiles**, or **Classic ASCII** to put
  the letters back. That menu works at the start menu and on the map
  between moves, and whatever you pick there is how OTT.app starts next
  time.
- **Linux/X11:** start the game with `-t`, e.g. `./build/ott -mx11 -t`.
- **Linux/terminal (`-mgcu`):** not available — a terminal cannot draw a
  tile, so that frontend stays in letters.

Nothing about the game changes: the tiles are a way of drawing the field,
not a way of playing on it. Every key, every rule and every message is the
same.

## Building from source (Linux/macOS)

Requires a C compiler, cmake 3.x, and ncurses. From the repository root:

```sh
cmake -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build -j4
./build/ott -mgcu
```

On macOS that first line makes `build/OTT.app`; for the terminal game add
`-DSUPPORT_COCOA_FRONTEND=OFF -DSUPPORT_X11_FRONTEND=OFF
-DSUPPORT_GCU_FRONTEND=ON` to it. The game needs `./lib` relative to the
current directory.

## Credits

OTT is built on Sil-Q, by the Sil-Q developers and community
(<https://github.com/sil-quirk/sil-q>), which grew out of Sil (© half &
Scatha), which descends from Angband. The full credits are in README.md,
and the licence in LICENSE.md.

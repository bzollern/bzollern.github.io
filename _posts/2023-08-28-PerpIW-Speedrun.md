---
title: (KINDA SPOILERS) On the ⊥IW Speedrun
layout: post
author: Adalbert
tags:
  - puzzlehunts
---

2021 was my first actual foray into Mystery Hunt (retrofilled blog post coming later™). It is also the most memorable for me by leaps and bounds, in a way only other Galactic Puzzle Hunts have been able to match on a per-puzzle basis.

If I had to guess at the reason, it would be around 25% primacy bias, 25% about it being a bit of a landmark year thanks to The Pandemic, and 50% ✈️✈️✈️ Galactic Trendsetters' ✈️✈️✈️[^possessive] design philosophy, whatever that may have been—it's like the hunt was min-maxed to optimize memory formation, and I would attribute this primarily to the [https://puzzles.mit.edu/puzzle/www/2021/projection_device.html](Projection Device) forming its backbone.

As such, when the Projection Device came back online the next December, I immediately went back on—and was surprised to see that, among the numerous other changes Galactic had implemented to fit a static website, they also added a speedrun feature.

By then, I had already been at the Actual MIT for a full year[^year], so I knew its map like the back of my hand. Since ⊥IW's map is, of course, a direct reflection of MIT's, knowledge of one reinforces knowledge of the other.

Which meant, of course, I had to give it a shot.

I spent a few days refining the craft, then dropped it when the next semester came about, before finally completing an actual run the next June—just under an hour—and then pruning it down to 33 minutes. I'm sure faster is possible.

It's been a year since that, and it was recently brought to my attention again, so I've decided to write an article detailing my current knowledge of the speedrun. It's not for everybody, but I highly encourage giving it a shot if you happen to like puzzles.

# The Basics

The speedrun starts as soon as you talk to the rabbit-eared person next to the East Parallel. Afterwards, it's a race to talk to every single puzzle-giving NPC in the Institute. The problem? Besides the students and the school's athletes, everyone else is hidden behind layers of puzzles.

Puzzles in speedruns are a bit of an interesting topic, in that as soon as a speedrunner knows the answers they can easily do an equivalent speedrun without going through the puzzle-solving process at all. This is problematic when a significant part of the run is puzzle-based, and why the optimum for puzzle game speedruns is things like the Witness Randomizer—speedruns that require incorporating actual on-the-fly puzzle solving, instead of being beatable by rote solution memorization. Of course, such speedruns are few and far between, as they require being able to procedurally generate puzzles within the engine, so that the speedrunner sees a new puzzle every run.

Of the ⊥IW navigation puzzles, only one (the Tunnels) has procedural generation and requires rule-based memorization. However, I believe it is more fun to speedrun ⊥IW if you don't memorize, say, the exact button sequences you need to press to get into Cluster 10; part of the fun is figuring that out on the fly.

Likewise, while I can't stop you from doing so, I strongly discourage using the warp button—while it cuts down on getting out of several hard-to-navigate regions and would probably speed up runs by upwards of ten minutes, it detracts from the puzzle-solving experience (more on that later). It's not even good speedrun tech, considering warping eats up at least eight seconds of otherwise productive travel due to playing an animation beforehand and these puzzlegivers are _everywhere_—it practically only exists for one free trip out of ⊥IW.milli and several out of the Tunnels.

# The Route

Under no-warp conditions, this is the first route I used for speedruns:

The logic behind it, of course, is a traveling salesman problem all on its own, but the general gist is as follows:

- The traveling salesman problem primarily operates on students and athletes; the regional concentrations are afterthoughts
- Geography is weird - Outdoors travel is significantly faster than indoors in general
- Avoid unpopulated areas where possible

Here is a map of all Students (Cyan and Orange; Dark Blue for underground) and Athletes (Purple).

Since you start in the middle of a giant cluster on the east side of campus, the first part of the speedrun is a little more free-form, and I suspect most consistent improvement will exist in the routing over here. The primary caveat on this side is the existence of three students in an underground hallway (the dark blue dots on the map), which essentially forces you to walk down to the Sailing Pavilion at some point, then take the hallway to Building 16, whereupon the next immediately obvious destination is Stata.

You will be taking several trips through East Campus, so it's best to divide the large number of people here among them. Current theory suggests six people at the start walking through the parallel and entering Green from the backside, then three from Green to the Sailing Pavilion, then the remaining three heading towards Building 14.

After you enter 14, the route gets railroaded by where people are—main campus is sparse on puzzlegivers. People are primarily clustered in two rooms in the eastern buildings, Building 13, and the Minerva Clusters, with few others in between. The route here deliberately avoids long, empty areas like Building 6 and the fixed Infinite, though it's forced to take Hacker Passage and Building 5 since they're the fastest routes to Buildings 1 and 9.

West Campus has a lot more people. Your entry point will probably be Dorm Row, after which you will emerge on the western side of the Athletics fields. This is a large area; fortunately, Simmons Hall is nearby. A weird quirk of ⊥IW's geography means that Simmons can be used as a faster method of traversing opposite ends of the Athletics fields, so you can divide the region into two separate traversals.

The route ends at Random Hall, since the road there is the longest empty stretch in ⊥IW that must be taken on this route.

There are six warp points (the Dot in EC, the Stata Center, Killian Court, Building 13, the entrance at 77 ~~Mass~~ Perp Ave, and Simmons).

# The Green Building (14 people)

As the tallest building on campus, the Green Building must be traversed with an elevator that runs on passwords. The code to any given floor is given on the floor directly below it, and it is usually easy to parse. So easy, in fact, that the ideal amount of memorization for this section is zero—just interpret the diagrams given while you talk to the people on that floor.

The tricky parts are on the last two floors: the fifth floor requires traversing an invisible maze to get to one of the people here, and the sixth code gives you the colors directly but requires bumping into invisible walls to get the code.

While you can input the code by keyboard (using the arrow keys and space bar), it's impractical—thus this is the only part of the speedrun where the mouse is faster.

# The Infinite Corridor (6 people)

During the 2021 MIT Mystery Hunt, the Infinite Corridor did, in fact, have a countably infinite[^infinite] number of rooms; in this state, you could enter each room and talk to the person inside to get a puzzle, provided you found one specific classroom first. In the static version, it's not infinite by default to aid manueverability; you have to talk to a person standing at the end to make it infinite.

Fortunately, you don't need to talk to everyone here—just the person in the white portal at the start and one representative of each of the five puzzle types, the easiest to access of which are at 1, 2, 3, 5, and 6. The red portal in each room doubles your current number, while the gray portal takes you back to 1; thus, the fastest route is 1>2-3>6-5=>1.

For an extra challenge, though, you can attempt to reach the classroom numbers needed to unlock each puzzle; these are 13536, 68091, 33136, 85567, and 57138. However, I believe this isn't fun, just a sixteen-bit binary-memorizing festival (since red portals are essentially a binary encoding challenge). While there were other colors of portals in the live hunt, each of which was a nice puzzle in its own right, you only get red portals here, which is a little bit sad.

Don't forget the person in the white portal.

# ⊥IW.giga (20 people)

The puzzle here involves size changers. Unlike the live hunt, you don't need to be the same size as the puzzlegivers to talk to them. Like the live hunt, though, it's impossible to complete with one person. You need at least one other "person" (or rather a separate browser window) to help with the buttons for bridging the gaps to two of the NPCs in ⊥IW.milli.

I'm not sure what the policy would be here. I feel, for honesty reasons, that the process must be done on exactly one computer, with exactly one puppet account, that starts on the Dot; otherwise, what's stopping people from pre-positioning accounts on the walls in ⊥IW.kilo and skipping puzzles that way?

It's not something I'd like to dwell on, but speedrunners will prefer to optimize the fun out of a game if given the opportunity. I'm trying to make it so that the speedrun _is_ fun, and that includes honesty guards.

Either way, the route in giga is railroaded. You then have to travel back to island 1 for kilo; grab the two people on the outside on your way towards milli, then do milli and get everyone else on the way out. milli, of course, requires you to coordinate two instances of the Projection Device. Grab the robot to your right first, then do the whole bridging process; afterwards, everyone else can be found without changing your size by having the ally press the top button (though you still need the XL changer to get out).

Also, don't forget the one in giga you have to get by falling off the bridge section.

# Stata Center (15 people)

This area is also password-based, though here it's treated more like navigating a maze—you're given a password and a hint as to how the maze operates, and need to figure out the correct path.

There are seven total mazes; the eighth is a freebie that leads straight to a person. In the likely-encountered order:

- A room with eight exits, one in each ordinal direction. "When you're on a boat and trying to reach your destination, what you need is a sail."
- A linear room with no marking. "Huh, what year is it? It's 2021."
- A +-shaped room with SET cards at the exit. Three form a set according to the rules of the game; one doesn't.
- A square room with four exits. A maze is on the wall next to the stairs.
- A linear room with a . on one end and a - on the other. "The answer is telegraphed clearly."
- A +-shaped room that shows numbers near an exit. There is no hint here; the implication you should get from the numbers is that you need to take the path that follows the Fibonacci sequence.
- The freebie.
- A +-shaped room with a compass rose on the floor. "Confused? First, come to your senses."

The Green Building is a more direct set of passwords—the presentation may be different, but in the end you're still hammering in a sequence of colors, no more than six. Stata is different—every hallway has a different layout to it, and that plays into how the password is determined. As such, the fun comes not from memorizing an arbitrary sequence of directions, but from knowing what you want and building up a password from there.

Of course, this could also be bias on my part due to having memorized all of flag semaphore and morse, but knowing and applying the encoding is also better for the memory aspect than drilling a 22-bit sequence into your head to beat one puzzle.

# Clusters (12 people)

This is four separate password challenges on a keypad where none of the buttons function as expected. Of these, only Cluster 3 is likely to be more fun memorized than not, since every number functions differently and it's easier to memorize a password than ten functions; however, the intent for all of these puzzles is to treat it like a black box, discovering how it functions by interacting with it. Figuring the mechanics out on the fly is obviously not tenable for a speedrun, but just like Stata, the fun comes from figuring out how to use the mechanics to achieve the desired result.

By the way, yes, you can use your keyboard to input passwords.

# Tunnels (15 people)

Traversing the tunnels is guaranteed to take up half of your run, assuming you don't warp out of the tunnels[^coward].

The tunnels map looks a little bit like this graph:

The puzzlegivers are positioned at the green and red nodes. The edges between each node each contain three lines of ghosts that will only let you pass if their word follows an edge-specific rule.

Since taking a passageway _will_ eat up a lot of time as you wait for ghosts to filter through, the goal is to reduce the number of passageways to as low a number as possible.

Thankfully, you have allies in this endeavor.

There are seven holes in the floor of Building 13 and the nearby Hacker's Passage[^passage] that lead directly to each of the red nodes in the graph. You only really need to take five of them, though: the two holes at the near end of Hacker's Passage are redundant, as the red nodes they correspond to can be covered by another red node in the region for as many passage uses.

13-br: pitch black
13-tr: just before the one-vowel rule
13-tl: just above the misspells
hp-br: bottom, just after the bash
hp-tr: just before bash
hp-tl: just before no es
hp-bl: :shrug:

As for the rules, they cover a lot of ground. While many are various properties of words, things you can be tested on vary from HBO Originals to logic puzzle genres (think Sudoku and Kakuro).

In the speedrunning case, the path you take will heavily depend on your skillset. A vast majority of the rules are word-based and thus don't need external knowledge. However, there are a few knowledge gates that are absolutely required to traverse to a green node:

- World capitals
- Words of French origin (distinguished from words of Spanish origin)
- Winners of the Academy Award for Best Picture OR Tolkien characters (distinguished from drug brands)
- Balanced parentheses
- Knowing American spelling vs British spelling

In addition, if you don't warp out of the tunnels, returning to the center after falling down will also require:

- Winners of major American sporting events back to ~2000 OR League of Legends champions (distinguished from DotA2 characters)
- Good spelling skills
- Palindromic strings of parentheses (where e.g. "())(" is a palindrome)
- words that are also bash commands (assuming you don't want to wait for an obvious non-word)

This is an area where it's better to do your own research and formulate a plan from there. Of course, a speedrunning community will inevitably create rainbow tables to reduce the barrier on the knowledge-based rules, but I find it fun to figure out how to traverse the graph on my own terms.

# Charles River (1 person)

The one person here is Agent L, in the Sailing Pavilion. Don't forget them when you pass by for the students there, or you'll end up wasting several seconds walking all the way there.

# Concluding thoughts

A good ⊥IW speedrun has two key aspects: good routing and good puzzle-solving. Routing, of course, is crucial to any speedrun, so most of the uniqueness of this game comes down to doing the puzzles. While I cannot stop a community from cheat-sheeting this aspect out of the speedrun, nor stop the gradual creep of muscle memory that inevitably comes out of repetition, I hope I've at least convinced you to understand the solutions—to build your own knowledge base for the speedrun, rather than relying on the work of others.

---

[^possessive]: How would you possessive a plural that's followed by several emoji?
[^year]: Ignoring the remote semester forced upon me by The Pandemic
[^infinite]: If and only if you define "infinite" as one million.
[^coward]: Coward.
[^passage]: Not a real-life location, unfortunately, since that part of Building 13 is completely inaccessible.

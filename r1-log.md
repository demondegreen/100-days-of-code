# #100DaysOfCode Log - Round 1 - [Christian de Mondegreen]
# https://git.io/JPgsK

The log of my #100DaysOfCode challenge. Started on [Saturday October 30, 2021].

## Log

### R1D0
Decided to do #100DaysOfCode #100DaysOfPython, so prepped a few things.  Made a new Twitter for the purpose.
I will be going through 100 Days of Code - The Complete Python Pro Bootcamp for 2021
with Dr. Angela Yu (@yu_angela on Twitter) via udemy.

I am not a new programmer, by a long shot.  I have been self-taught programming since I was about 8 years old, started with copying BASIC out of magazines onto a TI-994a.
In my life, I have been paid to code/script in pretty much everything, ironically including Python, but it has been a while.

So I am starting from scratch at day 0.  I need to get back into the world, and I need to build some current if not simple portfolio examples.  I am hereby rebooting myself, which is frankly a bigger deal than the 100 Day commitment.  I may be out of town every once in a while, I'm only going to be reasonably tough on myself about that.  The end goal is to have 100 days of reported project-oriented learning linked from this log and annotated via Twitter @de_mondegreen.

I have noticed several people reporting starting study on Day 0.  I am always learning, so I could report something for today as well, but I will start the official reports and the official "counting" work / study, tomorrow.

I am not concerned about whether this is "working on real problems" or not, as for counting toward this challenge... The real problem that I'm working on is the slow but certain unwinding of my focus and initiative over the passing years.  The real success will be to complete one round of 100 days, even if it takes more than 100 days, at the end of which having something to show for the effort (github repo, working apps and web projects, relevent Twitter posts, blog posts).

### R1D1 
It's after midnight now, about 1:24am, so it counts as Day 1.  10/30/2021

Just took the 10 question placement exam and got a perfect score.  The result suggest that I could skip to Day 32, but I am choosing NOT do do that. 

Moreover, the additional *time exposure* working with a given concept works better for my overall mastery, and to be honest I won't turn down the ego boost of already knowing how to do some of the lessons, as it will give me some more time to look at side studies.  #100DaysOfPython doesn't have to mean Python only.  Also I definitely want to run the project days when they discuss Python Turtle and Tkinter!

Next session: repl.it is pretty awesome, they didn't have stuff like this even a few years ago.  (Forgive me, my first experience with Jupyter notebooks was only about 2 months ago, many things blow me away.) 

Reviewed string printing and concatenation.

resume session 10:40am : I'm super obsessive about doing every exercise manually, type in by hand, no matter what the course.  This has been my doom in many a good course when I couldn't satisfy my desire to do everything fast enough to maintain interest. I recognize that's my problem, I also believe that as mentioned prior more exposure and more explicit exposure (e.g., purposeful / intentional exposure with clearly defined goals) is better for my holistic learning process.

I also should not stay up until 4 coding and reading when I have to get up the next day.  There are few things that have held my interest over time, conceptually "programming" is one of them.  Telling a machine how to do something, enjoying perfect obedience, even with regard to obvious mistakes.  This and video games, we're going on 40 years active now.  I must have been 8 when I got that TI.  8 years old copying a dancing "mister bojangles" from some BASIC book.  At some point within a year or two I eventually convinced my parents to get me a tape recorder to store programs and data.  Primitive but functional.  I remember thinking I was going to write a secret note taking program, with a password and such.  Now I realize I have very little about which to write secret notes.

Resume session afternoon: finished the day final exercise, a silly band name generator that demonstrates the most basic console i/o sequence as well as fundamental string processing.
https://replit.com/@demondegreen/band-name-generator#

Left some feedback with regard to a couple of broken issues on some of the teaching material (tech changes, links change, etc).  Also started using a pomodoro timer today to try to focus better.  3 tomatoes on a saturday is not bad, and that didn't account any of the work i did before, it would have been easily 5-6.

Looking forward to tomorrow, I'm happy with the pace for day 1.  The guided project arc and intro to all the different libraries is what I need the most.  Structure.  The review of the python syntax is just icing on the cake, because of course it feels good to already know how to do something.  It gave me time to mess around and check out using the Thonny debugger (cool) without feeling distracted.

### R1D2 
10/31/2021 ooooh spooky halloween

Just completed the day two exercises and final project, a tip calculator.  
https://replit.com/@demondegreen/Tip-Calculator?embed=1&output=1#main.py
Today's work included a review of data types and type conversions, numeric operations, and f-strings, building upon the basic i/o from yesterday.  Probably the most important thing that I learned today was how to use a format string inside an f-string {}, rather than executing a string method. 

Not being as long-winded today. :)

### R1D3

Day 3 of the course completed.
summary: reviewed conditional statements and branching, comparison operators, the modulo %, logical operators.

Final project is a cool choose your own adventure / interactive fiction game.  Cool being relatively speaking compared to nothing.
https://replit.com/@demondegreen/jungle-of-doom?embed=1&output=1#main.py

flowchart: https://app.diagrams.net/?client=1#G1e30NH3zLct5md1gHnOCC67nYjVdb_VlO

11 tomatoes today, just about to be 12. 

### R1D4

Day 4 completed.  Not nearly as lengthy for me as yesterday.  I felt like I put too much time into a few things yesterday.  

summary: reviewed randomness and pseudorandom number generators, modules, lists

final project was a console rock paper scissors game.
https://replit.com/@demondegreen/RockPaperScissors

Mine works.  As I was writing it I specifically commented that I'm assuming no errors or error handling, as if the input was coming from taps of a touchscreen pad.
Little did I know that she would introduce the concept of error handling in the solution for the project.  Fine by me, but I did not rewrite.

I also did not rewrite my prototype in her pattern, although I can see where her pattern would be more easily extended to a RPS type game with an additional n hand positions that were all along a spectrum.  I just wrote the logic tests explicitly, no big deal.  Could I have rewritten it, yes.  As a result of how I formatted my code, I did not really need to use the index to choose what image to print, I just printed it by name.  However, I conceded that is more elegant and extensible.

6 tomatoes today when all is said and done, including the obligatory log post.

### R1D5

summary: for loops, ranges, code blocks, "".join, additional random module methods

final project is a (console) password generator
https://replit.com/@demondegreen/password-generator#main.py
https://replit.com/@demondegreen/password-generator-limitedlib

which I wrote two ways.  the first way is more elegant but doesn't use any for loops which was the topic for the day.  the second uses a for loop as well as random int indices to reference the original lists.

in her video solution, she already uses random.choice() on the easy version, so if random.choice is on the table, may as well use random.choices() -- especially since the "hard" mode already converts to a list and has random.shuffle in play.  My rewrite only uses for num in range in order to get the length of the lists, which ironically uses a len() inside.

so i'm happy with mine. i started with a list from the outset, and reviewed using "".join() once i was satisfied with the list as such.

will be 6 tomatoes after finishing a couple of other things.  I went way over tomatoes yesterday but it wasn't related to coding, so... not included.

also did the first 5 lessons of the zombie solidity tutorial for side kicks. cryptozombies.io 

### R1D6

summary: review code blocks / indentation, functions, while loops

final project: create instructions for a robot (Reeborg) to solve any a randomly generated maze

Reeborg is a pretty cool learning site.  Wish they'd had this when I was in elementary school/junior high.  Great to use it now though!

I was able to quickly troubleshoot the intermediate level problem (where edge cases would leave the robot in an infinite loop).  I keep coming up with exactly the same solutions are her, so I will take that as a good thing.

7 tomatoes today

### R1D7

first week down!

summary: hangman project! https://replit.com/@demondegreen/Hangman?embed=true#main.py

I made my first flowchart, I am so cool and proud hah.

https://drive.google.com/file/d/1QISFDFQdzm8zz_DfJTDDMh_tf5x1jVPi/view?usp=sharing

some parts of the project were a bit frustrating because of the way she had it organized pedagogically, but for the same reasons it was a very low stress day for me.

My code diverged from hers several times, but I had to be familiar with her code in order to use the next repl's starting position.  No big deal.  The game works but it is brutally hard LOL.

will be 9 tomatoes after cleaning up and also looking a bit at the solidity tutorial again.

BONUS: make that 11 tomatoes.  completed the first lesson on crypto zombies and created this wonderful zombie https://share.cryptozombies.io/en/lesson/1/share/Christian_deMondegreen?id=Y3p8MTQzMDEx this is actually pretty exciting.

I ignored blockchain altogether for as long as I've known about it because I was butthurt after a few stupid experiences with bitcoin.
But the problem was I was already ignorant or I wouldn't have done what I did (didn't buy early, sold what sliver I had early because I literally had no idea what it was.)

BUT the fact of the matter is, there is a lot of opportunity to still make money in ongoing problems, even if it is just development fees.  I'm trying to find something that is current to re-inject myself into, language independent.  I have a lot of self-taught project experience, a lifetime of this crap, but I have only rarely injected any of that expertise into the public.  I really need to now, trying to survive in this bizarre cyberpunk dystopia with a strange meta-economy moving much faster than the prime.

better late than never?

### R1D8
missed yesterday, not counting the day. so this is now Sunday November, 7 2021.

Have been really getting side-interested in smart contracts. It surprises me that I'm actually open to working with crypto and defi now.  I have actively avoided that knowledge domain (and thereby that devspace) for as long as I knew it existed.  Anyway I digress.  My prior notes reminded me.  I've found some amazing assets to learn that, but the first priority is finishing the python challenge.

So now why am I not worried about suddenly calling this day 9 like I have seen some people do on twitter?  Well I'm not, I am calling it 8 because this is the 8th day of effort I'm putting toward this very specific #100DaysOfCode / #100DaysOfPython challenge.  It would be worse for me to try to keep up with an offset than it is to just say "oops worked too hard building those wooden tables, didn't drink enough water" (true) and do day 8 the next day.  It's my life, it's my count, it's my choice.

I also think this is the most sane way to handle #100DaysOfCode when you're sometimes having to go out of town where there is no internet (truth).  Sure you could fill those days with "i downloaded and watched some videos" or "i coded some local stuff" .  Fine.  But it is not the same level of effort and expectation as set forth by a complete curriculum. 

i continue to digress....

summary: review functions with inputs, parameters, and arguments

final project: caesar cipher encoder/decoder (console)
https://replit.com/@demondegreen/caesar-cipher?embed=1#main.py

not the worst way to spend a sunday. so far 7 tomatoes, but I will probably start looking at the next cryptozombies lesson.  i really dove into the concept last night, after allowing myself to get over myself with regard to programming.  The stupid thing is I have the worst imposter syndrome.  I have literally been coding like this since I was ...what...  8 years old?  I've gotten paid to code in everything from perl to COBOL (yes, actual COBOL on a mainframe with byte-wise raw storage io.  holy crap).   and yes, even python, but it has been a while.  I wrote an entire CMS in 2005 because the client refused to listen to me tell him that WordPress would be more secure.  It's just been a while.  I have hidden from the public eye for years, living very meagerly.  But yeah, I need to start being who I actually am instead who I have been led to imagine myself to be. 

### R1D9

summary: review dictionaries and nesting. 

basically ad hoc data structures

final project: A Silent Auction sim
https://replit.com/@demondegreen/SilentAuction?embed=1#main.py

in the meantime also making some headway with solidity on the side.
was up until 2 again because i kept having epiphanies

### R1D10
Summary: review functions with outputs, docstrings, function recursion

Learned that input() has a return, so can be used to make a loop flag without a separate variable.

final project: text-based 4 function calculator in the console
https://replit.com/@demondegreen/console-calculator#main.py?embed=1

I wrote my fully functional prototype alone then watched her to look for improvement.

Had some issues with the bottom line of the web-based console in replit, but I confirmed that the issue was not my code by running the calculator locally.

We did this in different ways.  She had a separate micro function created for each operation, while I just passed the operator to the calculate function and had 4 returns.

Well, it ends up she was going to use this entire lesson as a teaching moment because she not so subtly immediately introduced mapping functions to other labels, which turned out to be a pretty cool way to use the typed in symbols.

The symbols themselves were keys mapped to the function names (no parens) in a dictionary. neat.

You can directly call the correct function by addressing the mapped function by passing the index symbol, rather than make a temporary function label as she did.

I feel a little weird wrapping the entire script into a function and then calling itself to loop. in BASIC you just GOTO 10, of course there's nothing like that in python (labeled lines), but in this way the function name actually does act as a label that can be used to loop back and repeat.

Neat, I probably wouldn't have thought to do that as the solution. Well obviously I did not, I had it wrapped differently in my original prototype.

### R1D11
Capstone project, a console blackjack game.  Relatively simple - does not account for splits, double down, insurance etc.  Just 1 on 1 21.
https://replit.com/@demondegreen/blackjack?embed=1

Not sure why it won't play from that embed page, replit has being acting weird all day as if I'm disconnecting and connecting from the internet frequently.  Nothing else gives me that indication.  So I eventually moved over to Thonny and finished it locally.  It's actually pretty fun and frustrating, so I am not upset.

I did this without using any of her hints, so I guess that makes this an "expert" level attempt. I would not call this an expert solution, but I guess I am pretty pleased that I can write a full console program with somewhat convoluted logic without referring to anything but the pydocs to see whether sum() was a method or a function. :)  

I am going to go through now and watch how she did it, because I guarantee this is not the most elegant solution.  Nevertheless rather than just commit her code instead of mine, I am committing mine as a snapshot of my thoughts and how I handle logic at this point in time.

I am also starting to commit some of the more interesting code snippets to another repo:
https://github.com/demondegreen/my-100-days

### R1D12
Nov 12, 2021

summary: namespaces and scope, naming constants

final project: guess the number game
https://replit.com/@demondegreen/guess-the-number?embed=1#main.py
https://github.com/demondegreen/my-100-days/tree/main/R1/D12%20Number%20Guess

Not a lot new here, I actually thought it was significantly easier than the blackjack game, so it was a nice reprieve.  I wrote it without assistance again, so this version is *my* take on the solution as a first prototype. It works.  I feel like the penalize_player() function is kind of unnecessary, I only did it to avoid a couple of lines of repeated code, but that then necessitated rewriting all the turn count decrements as results of return rather than a direct decrement (which is easier to read).  Whatever! Best number guessing game I've written in a while.

Also spent some time reviewing a roadmap toward hopeful freelance work in the blockchain space.  I feel like I am incredibly late to the party, but there's no time other than now.  I can't do anything about past decisions.  So let's do this.  It does mean I have to add a javascript review (which I may do as part of another 100 days) as well as some serious react learning.  (Maybe a CSS intensive also.  I need enough to make a lightweight, responsive front-end and it isn't completely foreign, it has just been a while and I really want to make sure to use the current thinking patterns as regards...well everything.)

### R1D13
Nov 15, 2021 , had to work overnight all weekend.  Been studying blockchain on the side, so still a win.

Summary: general tips for debugging and using a debugger with breakpoints.  No standalone final project, several coding exercises.

This was a very quick day for me, I should have just done it yesterday but I was wiped.

### R1D14
The end of the "Beginner" section of the course, today we were given a working program and told to break it down and re-write it from scratch.  Looking forward to tomorrow where we move out of Replit.  I think I've hit my limit of patience with a few of its quirks.

project: higher lower game
https://replit.com/@demondegreen/higher-lower?embed=1#main.py
https://github.com/demondegreen/my-100-days/tree/main/R1/D14%20Higher%20Lower

No major problems here.  I planned by way of writing out the process in comments, which are documented as pseudocode in the repo.  My final version was slightly different, but it marks the beginning point right before I wrote down any real code.  An interesting artifact, and perhaps helpful to someone.  Moved some of the repeated code out of hte main game loop (function) into functions.  I was thinking of other ways to optimize this but it really isn't that big of a deal.  Time to move on.

I lied, i came back and spent another half hour refactoring and re-arranging.  much happier with this version.  It handles things that the instructor's does not. It also adds a win condition rather than perpetually revolve.  It's probably not like the original game, but I am treating all the entries more like cards.  They get removed from the stack --> when the stack is 0 on a final correct answer, you win because you've cleared the deck.

The fact is this would be an extremely rare condition with anything but the smallest of datasets. e.g., Unless someone is cheating, they're not going to get 50 of these answers correct in a row.  Removing the card from the deck also ensures you never draw the same card for B as what's already in A, which is a bigger issue because it requires its own handler.

### R1D15

Cool day! We got off Replit and into PyCharm which I am loving.  Although I actually would have preferred she moved us into vscode, this is a very nice IDE and the open source version is good enough for now.  Definitely appreciating the speed of the code completion compared to replit which was constantly falling offline (I'm on wifi in the back of the building, but nothing falls off that much).  Also loving how it sets up virtual environments per project automagically.  Actually I really like that.

No new python, but another reverse engineering logic project.

project: Coffee Machine simulator
https://github.com/demondegreen/my-100-days/tree/main/R1/D15%20Coffee%20Machine
https://git.io/J1wTc

### R1D16

summary: review oop, attributes, methods, libraries

TIL Turtle graphics language / LOGO exists in Python.

final project: oop coffee machine sim, using provided library and documentation
repo: https://github.com/demondegreen/my-100-days/tree/main/R1/D16%20OOP%20Coffee%20Machine
https://git.io/JMObi

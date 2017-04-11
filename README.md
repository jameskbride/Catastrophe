# Catastrophe Cata

**By the way, this is a rough draft.  Please don't judge me.**

Cat-Tastrophe Cata
By Yasi

Objective:
Determine the maximum number of cats you can afford given

* Your current savings (dollars)
* Your monthly free income (dollars)
* Your montly free time (hours)

This will be determined using several rules.  This kata is designed to be of variable length, so you may implement as many or as few rules/stories as you wish.  It is designed to be done in order, but you do not have to finish.

The point of this exercise is to use TDD practices to solve a problem writing clean, readable code.  A UI is not nessesary.

Basic Rules:

* You are willing to spend all of your savings, montly free income, and monthly free time all on cats, of course.
* The cat-hating government will only let you have a maximum of 100 cats, no matter how many resources you have.
* You plan on having your cats forever, so you cannot use your savings as montly income, or vice versa.  Monthly budget and upfront budget should be treated as separate resources.
* You cannot pay someone to do your cat chores for you. That would diminish the bond between you and your cats.

BUYING YOUR CATS
-----------------

**ADOPTION FEE**
* $100, one time only for each cat
* If you have at least 20 cats then the rest will just wander into your yard for free.  No one really knows why.

**FIXING FEE**
* NEUTERING: $75, one time only, for each male cat
* SPAYING: $150, one time only, for each female cat
* You always adopt alternating male and female cats, starting with a female.
* Cats that wander into your yard will also follow this pattern

CARING FOR YOUR CATS
---------------------

**VET BILLS**
* $5 per month per cat
* 1 hour per month for every 2 cats (rounded up)

**LITTER BOXES**
* you need 1.5 litter boxes per cat, rounded up
* $25 one time cost per litter box
* $10 per month per litter box
* 2 hours per month per litter box

**FOOD & WATER**
* Food & Water Bowls: $5 one time only per cat
* Food: $15 per month per cat

**CRATE**
* $20 one time only per cat
* you only need a maximum of 2, no matter how many further cats you have, because you only have 2 hands.

**SCRATCHING POSTS**
* $30 one time only per cat
* you need a minimum of 3, even if you have only one cat

**CAT TREES**
* $70 one time fee for every 3 cats

**BEDS**
* 6 cats can sleep in your bed with you
* $15 one time only for each remaining cat

FANCY CATS
------------
* every fifth cat you buy/find is fancy
* fancy cats eat fancy food, which is $30 per fancy cat
* fancy cats use fancy cat trees, which are $150.  A regular cat can use a fancy tree but a fancy cat can't use a regular tree.

INTERACTING WITH YOUR CATS
---------------------------

**GROOMING**
* $10 cat brush, one time only, you'll only ever need one
* 2 hours per month per cat

**PETTING**
* 3 hours per month per cat
* You can pet 2 cats at a time (you have 2 hands)
* If you have at least 10 cats, there are always 6 cats which need to be pet one at a time because they can't share attention

**PLAYING**
* You need 10 toys for every 3 cats (rounded up)
* Each month, your cats will destroy 5 of those toys, the other 5 will remain intact
* Toys cost $10 each
* You must play with your cat for 15 hours a month, but you can play with 3 cats at a time

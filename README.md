tip-top-tap-kata
===

The following _would like to_ be a TDD Kata, an exercise in coding, refactoring and test-first, that you should apply daily for at least 15-30 minutes.

## Before you start

- Try not to read ahead.
- Do one task at a time. The trick is to learn to work incrementally.
- Make sure you only test for correct inputs. There is no need to test for invalid inputs for this kata.

## The kata

Requirements:

- At least 6 players, seated on a circular table.

### Step 1: Implement a basic round

The game starts with a random player who says `tip`, then in clockwise order (or counter-clockwise) the next player will say `top`, then the player next to him/her will say `tap` while point at another random player, who will start another round saying again `tip`. Then the next will say `top`... and so on.

### Step 2: Players tend to make mistakes: classic mistake

`TODO`

- Players now starts with a random error-prone percentage...
- ... So a player may say for example `tap` instead of `top`

### Step 3: Players tend to make mistakes: mislead or wrong start

`TODO`

- A player may say `tip` even if the one who said `tap` wasn't pointing at him/her

### Step 4: Grappa comes in!

`TODO`

- There's now a bottle of grappa in the middle of the table (**1 liter**)
- Every time a player makes a mistake, he/she has to drink some grappa (**10 ml**) and her/him error-prone percentage will increase

### Step 6: ... "And then there were none"

`TODO`

- Game ends when the grappa bottle is empty

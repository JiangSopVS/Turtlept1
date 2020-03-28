## Introduction to Turtle War

Attack, Defend, and Score

### BASE STATS

Base Turtle: pt = 10, exp = 5, step = 50

Silver upgrade: when pt reaches 20, step = 40

Gold Upgrade: when pt reaches 40, step = 30

Platinum Upgrade: when pt reaches 60, step = 20

* When step = 0, for non-Platinum grades, can buy 10 steps for 5 pt

### ATTACK

Attacking enemies (For base, silver, and gold): step - 2, pt + 4, exp + 5 

Attacking enemies (For Platinum only, when step = 0): pt + 2, exp = 5

Can only make 1 attack per turn, or another attack at expense of exp - 5

```Marking

# Turtle Part 1
## Cautions

1. Observe battlefield
2. Weigh win options
3. Wait for opening
4. Act with caution

```

### DEFEND

Defend (for base): pt - 2, exp - 2

Defend (against lower grade): pt - 1, exp -2

### DEMISE (DEATH)

When pt = 0 or exp = 0

### SCORE

## Win Condition

WHEN ENEMIES ARE ALL DEFEATED

TAKE OUT ALL OPPONENTS BEFORE DEMISE; ELSE RETURN AS BASE TURTLE

# Understanding Check

In role-playing games like Dungeons & Dragons, users will frequently roll a 20-sided dice to determine if they can or cannot do something.

In some of these situations, the person rolling the dice is given either "advantage" or "disadvantage". Advantage lets you roll two dice and take the higher of the two to use for the check. Disadvantage lets you roll two dice and take the lower of the two to use for the check.

Program two whole number variables called `dice1` and `dice2` that will use random numbers to randomly get a whole number from 1 to 20.

Program another whole number variable called `requirement` that you assign the number `12` to.

Requirements for passing the check:
- When the dice number is at least the requirement number, print `"You passed the check!"`
- When the dice number is lower than the requirement number, print `"You failed the check!"`

Program two boolean variables called `advantage` and `disadvantage`, which you initially assign a value of `false` to both.

Use an `if` statement to decide if they should be rolling one or two dice.

If they are rolling one dice, check if they pass using the above rules.

If they are rolling two dice, determine whether it is because of advantage or disadvantage (we are assuming it will only ever be one of the two).
- If they are rolling with advantage, pick the larger of the two dice rolls and use that to check if they pass the check, with an additional note in the print statement about it having used advantage.
- If they are rolling with disadvantage, pick the smaller of the two dice rolls and use that to check if they pass the check, with an additional note in the print statement about it having used disadvantage.

For all of the above situations, have it print out what the final rolled number was!

Here are a couple of sample outputs the program could produce (your results may vary due to the random number):

```
You rolled a 7!
You failed the check with disadvantage!
```

```
You rolled a 18!
You passed the check with advantage!
```

Test it out with changing the boolean values of `advantage` and `disadvantage` to see if everything works properly.

Once you have gotten to just warnings, save the Java file and commit and push your changes via GitHub Desktop.

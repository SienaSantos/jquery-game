# jquery-game
For our jQuery practice, you're going to make a game. We will call this game, Ninja Gold.

Our main character is a ninja in search for gold. He can find gold in 4 different places: the cave, the house, the goldmine and at the casino. 

In 20 trys, the ninja should reach 200 gold.

The probability and the breakdown of each location is as follows:
- cave 80% +/- 5 gold
- house 60% +/- 10 gold
- goldmine 40% +/- 20 - 25  gold (random)
- casino 20% +/- 40 - 50 gold (random)

Feautures:
- Counter for number of attemps
- Counter for total gold. Make it red if he loses money and green if he gains money
- A log of the event. If the ninja loses money, make the log text color red and green if he gains money.
- Reset button (gold 0 and trys 20)
- Different locations with buttons (no need for actual pictures of the location)
- A ninja sprite that moves around the different locations. (when you click goldmine, he will move to goldmine. When you click casino he will move to the casino)


##Other Notes##

For the log, use an array of the event (json object contains data like the time, location and amount) 

```{ location: 'cave',
  time: 'some date string',
  amount: -40
}```

Use the same array for getting the total score. 

###Log###
- Use bootstrap tabs to sort the different logs. All, Losses, Gains.
- Create separate arrays for negative and positive events. 
- Also put the total gains and total losses.
- Learn to use Array.filter or Array.reduce Array.map functions. You can use jQuery equivalents

##Bonus##
- Persist the data (score and log) even with a browser refresh.
- Deploy it using surge.sh




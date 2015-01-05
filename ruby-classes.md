# Ruby Class Lab
These problems will use your knowledge of classes. 

* Create a class called `superHero` that takes a `firstName` and `lastName`. Give each superHero a `superPunch` method that returns `"WHAM!"`.
* Create a class called `robot` that takes `name` and `purpose`. Give each robot a `greet` method that returns `"beep boop"`

* Make a `Starship` class that takes a `model` and `ownerName`. 
  * Give your `StarShip` a `setTopSpeed` method and a `getTopSpeedMethod` that let you change and read the `topSpeed`. *Assume `topSpeed` is just a number.*
  * Give your `Starship` an `accelerateTo` method that sets `currentSpeed` to some number, unless that number is greater than its `topSpeed`.
* Make a `Dice` class that takes a `numberOfSides`. Add a method called `getSide` or `roll` that randomly returns a number from `1` up to the `numberOfSides`.
  * Modify your `getSide` method to record the returned side in a `lastRoll` instance variable. 
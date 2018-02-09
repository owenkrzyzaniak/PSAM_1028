```ruby

myFruits
(16) ["Strawberry", "Blueberries", "Kiwi", "Apple", "Orange", empty × 10, "Lettuce"]
var lastElementInArray = myFruits[myFruits.length - 1]
undefined
lastElementInArray
"Lettuce"

```

```ruby

var colorArray = ["Red","Green","Blue"]
undefined
colorArray.unshift("Yellow")
4
colorArray.unshift("Purple")
5
colorArray
(5) ["Purple", "Yellow", "Red", "Green", "Blue"]

```
```ruby
var HorrorLocation = ["Cemetery", "Haunted House", "Circus", "Forest", "Cellar", "Boat", "Bog", "Island", "Lake", "Hospital"]
undefined
var HorrorAdjective = ["Death", "Black", "Bloody", "Slime", "Suicide", "Cold", "Ghost", "Zombie", "Suffering", "Gore"]
undefined
var HorrorAdjective = [" Death", " Black", " Bloody", " Slime", " Suicide", " Cold", " Ghost", " Zombie", " Suffering", " Gore"] 
undefined
var HorrorLocation = [" Cemetery", " Haunted House", " Circus", " Forest", " Cellar", " Boat", " Bog", " Island", " Lake", " Hospital"]
undefined
var HorrorIntro = "Welcome to"
undefined
HorrorIntro + HorrorAdjective[Math.floor(Math.random() * 10)] + HorrorLocation[Math.floor(Math.random() * 10)]
"Welcome to Ghost Hospital"
HorrorIntro + HorrorAdjective[Math.floor(Math.random() * 10)] + HorrorLocation[Math.floor(Math.random() * 10)]
"Welcome to Suicide Hospital"
HorrorIntro + HorrorAdjective[Math.floor(Math.random() * 10)] + HorrorLocation[Math.floor(Math.random() * 10)]
"Welcome to Suffering Forest"
HorrorIntro + HorrorAdjective[Math.floor(Math.random() * 10)] + HorrorLocation[Math.floor(Math.random() * 10)]
"Welcome to Cold Haunted House"

```

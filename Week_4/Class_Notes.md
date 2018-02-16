```ruby
var hasFangs = false

if (hasFangs){ 
console.log("That's a vampire")
}
undefined
var hasFangs = true

if (hasFangs){ 
console.log("That's a vampire")
}
VM346:4 That's a vampire
undefined
```
```ruby
var hasFangs = true
var hasClaws = true

if (!hasFangs){ 
console.log("That's a vampire")
} 
else if (!hasClaws) {
console.log("It's a werewolf")

         
}else if (hasFangs || hasClaws){ console.log("That's a monster")
         }
```
```ruby
var sheepCount = 0
while( sheepCount < 10)
{
// do something here
console.log ("I have counted " + sheepCount + " sheep")

sheepCount++ //shorthand for sheepCount = sheepCount + 1

}
```
```ruby
var myPhrase = "Hello Earth"
console.log(myPhrase)

var name = prompt("What is your name?")
console.log("Hello " + name )
```




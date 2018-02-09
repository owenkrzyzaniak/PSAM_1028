```ruby

<!DOCTYPE html>

<html>

<head>   
	<title>Horror Movie Name Generator </title>
</head>

<body>   

<h1> Welcome to My Horror Movie Name Generator! </h1>

<h2> Refresh your page to reveal a new movie title </h2>

<script type="text/javascript">
var HorrorAdjective = [" Death", " Black", " Bloody", " Slime", " Suicide", " Cold", " Ghost", " Zombie", " Suffering", " Gore"] 
undefined
var HorrorLocation = [" Cemetery", " Haunted House", " Circus", " Forest", " Cellar", " Boat", " Bog", " Island", " Lake", " Hospital"]
undefined
var HorrorIntro = ["Welcome to", "Down at", "Lost at", "Trapped in"]
undefined

console.log(HorrorIntro[Math.floor(Math.random() * 4)] + HorrorAdjective[Math.floor(Math.random() * 10)] + HorrorLocation[Math.floor(Math.random() * 10)])

</script>





</body>


</html>

```

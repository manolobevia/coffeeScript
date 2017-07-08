# CoffeeScript (CS) 
* Boolean values can be `true/yes/on`, `false/no/off`

* No need to use var keyword

* No need to add semicolon for ending an statement

* Use string interpolation with double quotes. 
- - - -
**js**

`var farm = “potatoes” + ” /“ + ”garlic” + ” /“  + “eggs”`

**coffeeScript**

`farm = “#{potatoes} / #{gralic} / #{eggs}”`

- - - -

* Use # for comments

* `is` is the same like == equal comparison operator

*  `isnt` is the same like != non equal comparison operator

* In CS  `not isTrue` is the same like `!isTrue` in JS

* Comparison statement with JS and CS

- - - -
```xPos = 300
In JS
print xPos <100 and xPos< 500 
In CS
print 100 < xPos < 500 
```
- - - -

* `print myVar ? “Hello”`.  If myVar is true, it will print myVar, if not it will print Hello

* Conditionals, if there is no indentation in block code, code won’t be compiled

- - - -
```
If condition
	block code
else if condition (no need to use else, we can use just if)
	block code
else 
	block code
```
- - - -

* In CS,  `print something if condition` is the same as:

```
if condition
	print something
```

*  ```unless conduction
	print something
   ```

* Arrays. We can do it vanilla js style or having elements of array in lines and indented
- - - -
``` 
myArray = [
	elem1 (comma is not necessary, if you want to use it, go ahead)
	elem2
	elemN
] 
```

`print myArray[1..2]  # 2 dots`
Elem2, ElemN

`print myArray[1…2] (# 3 dots)`
Elem2

- - - -

* Objects

- - - -
JS
`var mammals = { type: “cow”, legs: 4, color: “gray” };`

CS
```
mammals =
	type: “cow”
	legs: 4
	color: “gray”
	
mammals = 
	cow:
		legs: 4
		color: “gay”
	dog:
		legs: 4
		color: “white”
	cat:
		legs: 4
		color: “pink”
```

* delete mammals.cow.color  OR
delete mammals[“cow”].legs

* for loop
- - - -
```
for num in [1..10]
	print num
```
- - - -
loop in array
```
car = [
	“wheels”
	“seats”
	“music”
]

for elem in car
	print elem
```
- - - -
loop in object
```
person = 
	name: “manolo”
	age: 24 (# I wish)
	country: “the world”

for key, value of person
	print key, value
```
- - - -

*  Ssingle line comments
`
&#35; This is a comment
`

* Multiple line comments
- - - -
```
### 
This is a comment
Another comment
###
```
* Functions 

```
sayHola = ->
	print “hola”

printName = (name) ->
	print name

printName “Manolo”

printVeggies = (veg1, veg2) ->
	print veg1, veg2

printVeggies “potato”, “carrot”
```



 



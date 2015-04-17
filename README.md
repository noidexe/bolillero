# Bolillero
A javascript implementation of Jon Davis "Shuffle Bags"


## How To Use
Add a script tag loading bolillero.js and then do: 
```
var myBolillero = Bolillero(elements);  //elements is an array of any size
                                        //and can have elements of different type
```

This will create a new bolillero containing all the elements in the `elements` array and shuffle them randomly. When you need to get one random element out of the bolillero just to. 
```
myBolillero.next();
```
You are guaranteed to get a different element from the array each time until you've gotten all of them, and then start again indefinitely. 

For more info on how this can be useful read:
[Shuffle Bags: Making Random() Feel More Random](http://gamedevelopment.tutsplus.com/tutorials/shuffle-bags-making-random-feel-more-random--gamedev-1249)

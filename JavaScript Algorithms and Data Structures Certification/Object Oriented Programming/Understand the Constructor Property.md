**Understand the Constructor Property**

There is a special `constructor` property located on the object instances `duck` and `beagle` that were created in the previous challenges:


```

let duck = new Bird();
let beagle = new Dog();

console.log(duck.constructor === Bird);  //prints true
console.log(beagle.constructor === Dog);  //prints true

```

Note that the `constructor` property is a reference to the constructor function that created the instance. The advantage of the `constructor` property is that it's possible to check for this property to find out what kind of object it is. Here's an example of how this could be used:

```

function joinBirdFraternity(candidate) {
  if (candidate.constructor === Bird) {
    return true;
  } else {
    return false;
  }
}

```

Since the `constructor` property can be overwritten (which will be covered in the next two challenges) it’s generally better to use the `instanceof` method to check the type of an object.



---------------------

**CHALLENEGE**


```
function Dog(name) {
  this.name = name;
}

// Only change code below this line
function joinDogFraternity(candidate) {

}

```

**SOLUTION**

```
function Dog(name) {
  this.name = name;
}

// Only change code below this line
function joinDogFraternity(candidate) {
  if(candidate.constructor === Dog){
    return true
  } else {
    return false
  }
}

```

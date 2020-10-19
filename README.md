# What-I-learned-week-5
# **Filter:**
* *goes through an array and finds specific items based on what is searched for*

* *returns fewer elements than are in array*

* *elements of original array are not changed*

* *elements not searched for remain unchanged*

* *works like map but does not change any of the original values*

## **For - of loops:**

* *a way to loop through an array or object without using [i] as a counter*

* *sets a new variable to equal the index of the items in the object or array*

## **Function Expressions:**

* *treats a function like a variable*

* *can assign a function to a const value*

* *naming the function, the parameters, or the statements is not required*

* *objects and arrays can be passed into functions*

## **Objects**

* *can use typeOf before an item in JavaScript to see what it is such as an object, array, etc...*

* *an object is a compilation of data describing one thing*

* *very similar to an array but also completly different*

* *objects use `{}` whereas array's use `[]`*

* *can make an empty object with `const someThing = {}`*

* *can then make a copy of the object and change whatever it is that you want changed*

* *can use both dot notation `obj.something = blueberrypie`*
 
* *will almost always use dot notation but can use bracket notation in cases when dot notation is not acceptable*

* *bracket notation is used mainly for illegal words which are variables that can not normally be declared for reasons such as having a space in the name or beginning with an number*

```
const makeBoss = function (obj) {
  const newObj = {
    name: obj.name,
    attackDamage: obj.attackDamage,
    boss: true,
    level: obj.level,
    alive: obj.alive,
    hitPoints: obj.hitPoints
  }

  return newObj
} 

||

const makeBoss = function (obj) {
const newObj = {};
newObj.name = obj.name,
newObj.attackDamage = obj.attackDamage + 10,
and so on...

}
```

![](https://render.fineartamerica.com/images/rendered/default/poster/10/8/break/images/artworkimages/medium/1/lets-go-steelers-florian-rodarte.jpg)
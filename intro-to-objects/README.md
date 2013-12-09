#Introduction to Objects
**During a mentor session with one of my students, we started talking about how she might approach the Shopping List project. The obvious and simplest approach was (from an implementation point of view) to hold a bunch of String objects inside an array. However, on reflection we felt that this could perhaps be too simplistic. For example, let's say that one of the project requirements was to be able to cross out items on the list instead of deleting the item. It would be pretty hard to represent this if all we had was an Array of String objects.**

Enter the Object. As we discussed the problem, we realised that if we could perhaps have a slightly more complex representation of the item in the list (after all each item is a real thing, has certain properties and is certainly more than a just a string of letters!), then perhaps we could give the item a certain state which would mean that it is deleted but not removed from the list - ie. crossed out.

It seemed to me to be the perfect place to start introducing objects our mentor sessions. Let's take a look at how we might model a shopping list in Javascript.

## 1. As an Array of Strings



## 2. As an Array of Objects



## Conclusions
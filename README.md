# Intro to Object-Oriented Programming

`OOP` is very useful on large scale `projects`, as it facilitates code `modularity` and organization.

By implementing the abstraction of **entities**, we're able to think about the program in a similar way as our world works, with different actors that perform certain actions and interact with each other.

To better understand how we can implement OOP, we're going to use a practical example in which we're going to code a little video game. We're going to focus on the creation of characters and see how OOP can help us with that.👽 👾 🤖

---

# How to Create Objects – Classes

So any video game needs characters, right?  
And all characters have certain **characteristics (properties)** like `color`, `height`, `name`, and so on,  
and **abilities (methods)** like `jumping`, `running`, `punching`, and so on.  

👉 Objects are the perfect data structure to use to store this kind of information.👌

---

## Example Setup

Say we have **3 different character "species"** available,  
and we want to create **6 different characters** (2 of each species).

---

## Approach 1 – Object Literals

A way of creating our characters could be to just **manually create the objects using object literals**, like this:

```js
const alien1 = {
  name: "Zorg",
  species: "Alien",
  sayPhrase: function () {
    console.log("We come in peace!");
  },
  fly: function () {
    console.log("Zorg is flying!");
  }
};

const alien2 = {
  name: "Xen",
  species: "Alien",
  sayPhrase: function () {
    console.log("Take me to your leader!");
  },
  fly: function () {
    console.log("Xen is flying!");
  }
};

// Similarly, we could create Human and Robot characters manually...


# Object-Oriented Programming (OOP) for Code Refactoring

After joining the new project, I found that the codebase was hard to manage. The logic was repeated, and there was no clear structure, which made it difficult to understand and maintain. My team lead asked me to study Object-Oriented Programming (OOP) so that we could refactor the code to improve its quality.

OOP is a programming paradigm based on four main principles:

1. **Encapsulation** – Groups related data and functions into one unit called a class.
2. **Abstraction** – Hides unnecessary implementation details and shows only what’s needed.
3. **Inheritance** – Allows a class to inherit properties and methods from another class.
4. **Polymorphism** – Lets one method behave differently based on the object that calls it.

By using OOP, we can reduce code duplication and improve readability. Below is a simple JavaScript example using OOP concepts:

```javascript
class Animal {
  constructor(name) {
    this.name = name;
  }

  speak() {
    return "Some sound";
  }
}

class Dog extends Animal {
  speak() {
    return "Woof!";
  }
}

class Cat extends Animal {
  speak() {
    return "Meow!";
  }
}

function animalSound(animal) {
  console.log(`${animal.name} says ${animal.speak()}`);
}

const dog = new Dog("Buddy");
const cat = new Cat("Whiskers");

animalSound(dog); // Buddy says Woof!
animalSound(cat); // Whiskers says Meow!
 ``` 

## References

- [Mastering Markdown - GitHub Guide](https://guides.github.com/features/mastering-markdown/)

- [JavaScript OOP - MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_programming)

- [JavaScript Classes - W3Schools](https://www.w3schools.com/js/js_classes.asp)

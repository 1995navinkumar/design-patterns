* Identify the aspects of your application that vary and separate them from what stays the same
* Program to an interface not an implementation
    ``` 
    Programming to an implementation :
        Dog d = new Dog();
        d.bark();
    
    Programming to interface/supertype :
        Animal animal = new Dog(); //assign this in runtime
        // Animal animal = getAnimal(); //Abstraction
        animal.makeSound();

* Favor composition over inheritance
* Strive for loosely coupled designs between objects that interact
* Classes should be open for extension, but closed for modification
* **Dependency Inversion Principle** - Depend upon abstraction not upon concrete classes


 

# Classes vs. Objects
It is important to remember that classes are just templates for creating new objects. Objects contain both a state and behavior, and is an instance of a class.


### Instances
An **instance** is a specific version of an object that can differ in numerous ways.

Going back to the previous chapter, ***Rectangle***, ***Animal***, and ***Vehicle*** are all classes. These classes, as is, are considered a type, unless you create a specific version of the class. 

In essence, if we create two different vehicles they would be specific instances of the ***Vehicle*** class. 

Remember, ***An object is an instance of a class.***


### Examples

``` Java
public class ExampleClass extends ConsoleProgram
{
  public void run()
  {
    // `Animal` is our class.
    
    // `myDog` and `myCat` are objects, because
    // they are specific instances of our `Animal` class.
    Animal myDog = new Animal("Cujo", true, 7);
    Animal myCat = new Animal("Kerby", true, 2);
  }
}

-------------------------------------------------

public class ExampleClass extends ConsoleProgram
{
  public void run()
  {
      // `Rectangle` is our class.
      
      //`mySquare` and `myRectangle` are objects, because
      // they are specific instances of our `Rectangle` class.
      Rectangle mySquare = new Rectangle(20, 20);
      Rextangle myRectangle = new Rectangle(5, 10);
  }
}
```



# Object-Oriented Programming

## What is an Object

There are different styles for writing programs, but one very useful style is known as object-oriented programming (or OOP, for short). OOP is used in many different languages, including Python. OOP focuses on the idea of objects as the nouns of a programming language. We've already been using many of the standard object types in Python, such as integers, floats, strings, lists, tuples, and dictionaries. Nouns (objects) can be modified or used by verbs (functions and methods). Methods can be thought of as the behaviors of an object. They are actions that are intrinsic to the object itself. Functions are actions extrinsic to an object.

As our programming tasks become more complicated or specialized, we will often find that the standard object types in Python do not fully meet our needs. Instead, we can invent and define our own types of objects (like we did with custom functions last week). Custom objects will have their own properties (variables) and behaviors (methods). When we define new objects, we also define what these properties and behaviors can be.

When talking about creating our own objects, we will need to distinguish between object classes and object instances. Think of an object class as a generic description of a type of object. For instance, "book" could be an object class. We know that books have titles and authors, but we don't need to think of a specific title or author to think about the idea of a book. However, an instance of an object _will_ have specific properties. For instance, our textbook is a particular instance of a book with the title, "Practical Computing for Biologists", and the authors, "Haddock and Dunn".

The requirements of a custom type of object are entirely dependent on the goals of your code. What information does this object need in order to define itself? What actions will the object perform? A very important skill for any programmer is to be able to think about a programming goal, and break that goal down into the objects and functions that will be needed to accomplish it.

## Creating Custom Objects in Python


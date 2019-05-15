# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Polymorphism, in the literal sense means "taking many different forms".

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

We allow an object/class to be recognised as more than one class - and used accordingly.

3. What can we use to implement polymorphism in Java?

You could use an Inheritance.

4. How many 'forms' can an object take when using polymorphism?

As many as are inherited by the superclass.

5. Give an example of when you could use polymorphism.

Within an array, you could use an Inheritance to make it so the Class that is expected can be more broadly designated.

For example, when needing to store multiple classes of a similar design, such as phones and tablets - we could instead use polymorphism and store them within the same ArrayList.

i.e.  ArrayList<Technology>

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

When we assign an object to the composition of another object.

7. When would you use composition? Provide a simple example in Java.

An example of composition would be when you know an object will require other objects to function. For example a 'Car' object would need other objects to function, such as an 'Engine' object or 'Suspension' object.

8. What is/are the advantage(s) of using composition?

With composition a class can be allowed to use the behaviours of another group of classes. It also makes it possible to change this behaviour during runtime.

9. When an object is destroyed, what happens to all the objects it is composed of?

When it is destroyed, the object behaviours of the other objects it is composed of are also destroyed.

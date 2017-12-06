---
layout: essay
type: essay
published: true
title: "Don't Reinvent the Wheel: Why to Use Design Patterns"
date: 2017-12-05
labels:
  - Design Patterns
---

<img class="ui fluid image" src="../images/reinventing-the-wheel.jpg">

If I were to just analyze the phrase “design patterns”, I might deduce that “design” deals with how something is constructed and built while “patterns” relates to commonalities observed over time that consistently work well. This isn’t far from the truth: Design patterns are essentially time-tested solutions that work effectively in solving common recurring problems. To not use design patterns would be idiomatically equivalent to trying to reinvent the wheel — a waste of time and energy in trying to create from scratch what has already been perfected and tested. In the following paper I will highlight a few common design patterns with some everyday analogies as well as some instances where I have used them in my code projects.

The idea behind the Factory design pattern is to give the receiving client options. My brother and I shared a twin-size bunk bed most of our lives: Part of its manufactured design was the ability to reposition the ladder that went up to the top bed depending on the bed’s setup in the room. Additionally, the ladder could be entirely removed and the top and bottom bunks could be separated to form two independent beds. These features were designed to allow the consumer to change the setup of the bunk bed, and this is essentially how the Factory design pattern works. I’ve used this many times when coding polymorphic class in Java and C++, where I would create a parent class (say, a Battle Droid class) which could later be instantiated as a child class (like a B2 Super Battle Droid class).

The Singleton design pattern allows a single instance of some object to be available and unique everywhere. The Guinness World Record organization performs a similar function in recording world records, ensuring that only one record holder is recognized at a time. Anyone who wants to know the holder of a record refers to the Guinness Book of World Records as the single definitive source, and while the actual record holder may change the Book as the global source will not. While the Singleton design pattern can be useful in creating global variables, I personally have not needed to use it in coding projects. I do know that my software engineering professor found a rather ingenious implementation of Singleton in creating an instance of a data collection and then exporting it as a constant variable to be used in other parts of the program. Any program file that needed to access that specific collection instance could then just import the variable.
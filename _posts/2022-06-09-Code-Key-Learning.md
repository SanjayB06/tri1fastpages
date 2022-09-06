---
toc: true
layout: post
description: Code.org Key Learning from Week2
categories: [markdown]
title: Code.org Key Learning
---


## Lesson 10

<img width="393" alt="image" src="https://user-images.githubusercontent.com/70538669/188696094-56e54c81-f040-4258-b91d-195bb7a80a05.png">

Inheritance: This code syntax shows how to create a new Child class that inherits from a parents class. All the methods and attributes can now be used in the new child class. 


![image](https://user-images.githubusercontent.com/72475804/188559943-32671741-8b45-47c6-970c-6f737aae831b.png)

The extends keyword shows that the new PainterPlus class inherits from the original Painter class. This means that it inherits all of its properties and methods, and that these methods can be used in the new class. 

#### PainterPlus.java
<img width="353" alt="image" src="https://user-images.githubusercontent.com/70538669/188695914-61eb0a43-64b6-4f9e-9144-d6de29aa5510.png">



#### MyNeighborhood.java

<img width="512" alt="image" src="https://user-images.githubusercontent.com/70538669/188696008-e2b66eee-2366-4f14-a0eb-246253b91dab.png">

## Methods


## Lesson 14

#### PainterPlus.java
![image](https://user-images.githubusercontent.com/72475804/188560894-feccabf7-8a6a-4d6b-a25b-b7fdb387d1cc.png)
PainterPlus extends everything from the Painter parent class.

#### PatternPainter.java
![image](https://user-images.githubusercontent.com/72475804/188561085-84b154a4-b12d-4e68-a661-79c89d9180c0.png)
PatternPainter inherits from the PainterPlus class. Since PainterPlus inherits from Painter, PatternPainter will be able to use both PainterPlus and Painter methods and attributes. 

#### BackgroundPainter.java
![image](https://user-images.githubusercontent.com/72475804/188561331-e224e6e1-2b71-4e18-99f5-769f96951d86.png)
BackgroundPainter goes even further and extends from PatternPainter, meaning it can use methods from PatternPainter as well as PainterPlus and Painter. 

#### Check For Understanding

<img width="1359" alt="image" src="https://user-images.githubusercontent.com/70538669/188697768-1072bb75-d812-44c1-9d35-06d89c693532.png">

Taco extending food is the only one that represents a class inheritance example because Taco is a subclass of Food. 



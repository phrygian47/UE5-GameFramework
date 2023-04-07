# Overview

This is a simple project using Unreal Engine 5 to create a 3rd person game framework that is to be expanded into a larger MOBA type game. As a software delevoper my goal
with this project was to learn how to program, as a result I avoided using Blueprints and preset content in order to amplify learning how C++ interacts with UE5, and
how you can use a mix of Blueprints and C++ classes to create a game framework. 

This 3rd person game the player controls a character that can be moved with the WASD keys and look around with the mouse. This game also includes the use of abilities, 
the ability included is a simple fireball that destroys any object it comes into contact with. While simple in theory learning an entirely new language as well as engine 
framework was difficult. There is not much up to date documentation on C++ with Unreal Engine, as it seems a lot of courses have transitioned into using BluePrints, 
especially with the bigginner level concepts. 

A short demonstration video is provided below.

[Software Demo Video](https://youtu.be/oEo--XyAgHs)

# Development Environment

To devlope this software I used Unreal Engine 5, and Visual Studio 2019 for the C++ class development. Unreal has many predefined libraries that makes the devlopment 
of these classes a little easier. A few of the libraries I included were the SpingArm component, Camera, Enhanced Input, and Input subsystems. Programming with C++ in 
Unreal proved to be much more difficult than I originally thought. There is not much documentation for C++ programming, and the documentation on the official website can sometimes be misleading. Programming with Unreal is also different than traditional game programming, since Unreal has so many predefined functions and classes a
lot of time was instead spent on learning how to connect everything, and learning which components were needed to have a workable player class, movement actions, or camera.

# Useful Websites

While some documentation wasn't as helpful as desired, the official Unreal Engine 5 website is still the best place for information on C++ programming with UE5. 

- [UnrealEngine.com](https://docs.unrealengine.com/5.1/en-US/)

Epic Games, who owns Unreal Engine5, also has a very active dev community with a lot of information that can be accessed. Specific questions can also be answered.
- [EpicGames.com](https://dev.epicgames.com/community/)

# Future Work

This game's final form is meant to be a MOBA type game. We have the basics and the framework set up, but much more work needs to be done. This work includes:

- Adding more abilities to use
- Creating a small map
- Adding health bars
- Adding additional player
- Adding minions and minion AI

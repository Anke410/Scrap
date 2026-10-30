# Scrap
Scarp is meant to be a little desk buddy. He is an interactive Arduino based robot. My main focus with scrap is to give it as much personality as I can, as well as to make his personality more spontaneous. He uses ultrasonic distance sensing, LCD expressions, multiple personality modes, LED indicators, sound feedback and automated sleep behavior. 

# Scrap – An Interactive Arduino Desk Companion

**Small robot. Big personality.**

## About Scrap

Scrap is a small, interactive desk companion robot developed using an Arduino Uno.

Unlike traditional robots designed primarily to perform specific mechanical tasks, Scrap focuses on personality, interaction and spontaneous behaviour. The main objective of this project is to create a robotic companion that feels expressive and engaging through its own unique personality.

Scrap is designed to respond to his surroundings and interact with the person sharing the desk with him. Through different personality modes, facial expressions, sound effects, lighting and distance detection, he can display a variety of reactions and behaviours.

One of the main goals of this project is to make Scrap's personality as dynamic and spontaneous as possible, allowing him to react in different ways rather than repeatedly displaying the same predictable responses.

## Core Features

- **Personality system:** Multiple behavioural modes that influence Scrap's reactions and expressions.
- **Spontaneous behaviour:** Varied and unexpected reactions designed to make interactions feel more natural.
- **Ultrasonic distance sensing:** Detects nearby objects and people to influence Scrap's behaviour.
- **LCD expressions:** Displays facial expressions that communicate different moods and reactions.
- **LED indicators:** Provides additional visual feedback.
- **Sound feedback:** Uses a buzzer to create sounds and communicate reactions.
- **Sleep and wake behaviour:** Automatically enters a sleep state after a period of inactivity and responds when someone approaches.
- **Button interaction:** Allows manual interaction and changes to Scrap's behaviour.

## Personality Development – Adaptive Behaviour System

One of the main long-term goals for Scrap is to develop a personality system that evolves according to his interactions throughout the day.

The proposed system will use an interaction-based counting mechanism to keep track of different types of interactions Scrap experiences.

Each interaction category will have its own counter. As interactions occur, the corresponding counters will increase or change according to the interaction.

At different points, Scrap will evaluate these counters and determine which interaction category has accumulated the highest value. This will influence his dominant personality for that period.

For example:

- Frequent playful interactions could make Scrap adopt a more playful personality.
- Frequent periods of inactivity could influence him to become more sleepy or less active.
- Frequent approaches and proximity interactions could make him more curious or affectionate.

His personality will therefore not remain fixed. It will be influenced by the interactions he experiences, allowing his behaviour to evolve throughout the day.

The system is intended to make Scrap feel less predictable and give him a sense of behavioural individuality.

**This feature is a planned development goal and will be implemented as the project evolves.**

## Project Goals

The long-term goal is to develop Scrap into a more expressive and interactive robotic companion by:

- Expanding his personality and behavioural systems.
- Introducing adaptive personality changes based on daily interactions.
- Improving the spontaneity and variety of his reactions.
- Exploring more advanced human-robot interaction.
- Integrating additional electronic components and movement.
- Developing a more expressive visual identity.

## Technologies and Components

**Current development platform:**
- Arduino Uno R3
- C++ / Arduino programming
- HC-SR04 ultrasonic distance sensor
- LCD display with I2C interface
- LEDs and resistors
- Active buzzer
- Push button
- Breadboard and jumper wires

Additional components and functionality may be introduced as development progresses.

## What I Am Learning

This project provides practical experience in:

- Embedded systems programming.
- Arduino and microcontroller development.
- Electronic hardware integration.
- Sensor technology and distance measurement.
- Programming behavioural logic and state-based systems.
- Human-robot interaction.
- Problem-solving, testing and debugging.

## Future Development

Scrap is an ongoing personal robotics project. His hardware, software and personality system will continue to evolve as new ideas and features are developed.

The ultimate goal is to create a desk companion that does more than respond to commands: a robot with changing behavioural tendencies, expressive reactions and a personality influenced by its interactions with the world.

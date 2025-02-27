---
layout: post
title:  "Week 38: Planning and Research"
date:   2022-09-23 15:44:00 +0200
published: true
---

Together with [Luleå Makerspace](https://www.luleamakerspace.se/) we are
working on developing functionality for a robot, 
[Pepper](https://www.aldebaran.com/en/pepper). 
Luleå Makerspace is an ideal organization' work is mainly introducing children
to programming and modern technology. The organization focuses on gender equality,
and has as a goal to make girls and young women more welcome in the tech-space.
Part of the project is aiming to make programming on the robot accessible to 
everyone with the help of a block programming language. Another part is focused
on developing custom interactions for the robot, such as playing hide and seek, or
telling an interactive story.

We have divided our group into two sub-groups:

## Block programming

This group will work mainly with compilation technology, parsing
a set of instructions from blocks and translating that to 
code that Pepper can use. This group will utilize 
[Blockly](https://developers.google.com/blockly) as the 
GUI.

## Interaction

This group will work with robotics, and is responsible for creating
custom behavior for Pepper. There is also a focus on AI in this group,
e.g image recognition.

#### Web interaction

Allow Pepper to search the web for 
information based on user input. The scope includes
searching for text and images, and also displaying
images on Pepper's tablet.

#### Image recognition

Pepper has some basic image recognition functionality,
such as recognizing faces. This group will work on expanding functionality, so that Pepper will be able 
to recognize for example the hand gestures used in a game of rock-paper-scissors. The group will also expand it in other ways.

#### Rock-paper-scissors

To enable Pepper to play rock-paper-scissors, we
have a group that implements arm- and hand movement for playing rock-paper-scissors. This group will utilize the work of the image recognition group. We have also chosen to display on Pepper's tablet what Pepper chooses.
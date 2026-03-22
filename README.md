# SlushEOS-aio

## TL;DR
- Hobby project
- Personal embedded operating system
- Not modular (or deployable) yet

## What is it?
A hobby embedded operating system :3. For now, the project is for very specific hardware, and is not very modular. I'll keep it this way for now, until I get better at operating systems. 

While I start up this project, it might be hard to follow along, but every now and then when I have the time, I'll try to properly document the project and work on my website (which is where aaall of my project will be found).

## Project goal
This operating system is meant to accompany another project of mine : SlimeGadgetSM01 (the hardware in question). I want a hand-held everyday gadget for tasks like calendars, password management, little games... basically a phone, but it'd be my own. I want to share the source code and designs of my project to hopefully inspire other people. I'm using this as a learning experience, but I also want to have fun making it!

## re: the hardware in question
To specify, I'm starting with an ESP32, with a mix of inputs and outputs; I have a small 128x128 display, an 8x8 red dot matrix display, an old 3x4 key pad, a rotary encoder, and it's probably not going to end there. I am calling it a gadget after all! Once I'm comfortable enough to upgrade, I'm considering maybe a Raspberry Pi Pico, or even evolve from embedded and involve more optimized architectures with a Raspberry Pi Zero, or an STM32 board.

---

# Roadmap

## First steps
### Version `0.y.z`

Arduino framework paired with an ESP32 board. All features, "apps", etc., will be a part of the same build.

Version 0 will not yet create a fully functional device, It'll focus around working with the hardware and establishing libraries
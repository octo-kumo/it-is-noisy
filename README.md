## Inspiration
- Some nights I can't sleep because of noisy neighbours
- I just don't know if the noise is from floor up, or neighbours
- Wouldn't it be nice if everyone have a noise tracker in their house?
- I will be able to identify the noise maker **quickly** and **easily**, without even going out of the door!
- ~~And I will be able to get my full 4 hour sleep~~
- So I decided to make this app to help people reduce noise pollution

## What it does
- It use the microphone to passively calculate a noise-level value
   - A single value averaged for 10s worth of audio, no privacy concern here
- Every household has its own noise value, and all those values in a HDB etc will stack up
- Users can set their location
- A map around the user is shown to them
   - The map has a heat map visualisation of the surrounding noise levels
   - Updates in realtime
- A "It is noisy" button to find out noisy households near you
- **Currently** has bunch of fake data for visualisation purpose, but multiple real users are supported, because the system underlying is working, and the fake data is stored in the actual database

## How I built it
[Electron](https://www.electronjs.org/) + [Node.JS](https://nodejs.org/) + [Google Maps API](https://cloud.google.com/maps-platform/) + Lots of **love 💕**

## Challenges I ran into
- Google maps documentation is not very helpful
- I fell asleep and had a 8 hour cut in my time

## Accomplishments that I'm proud of
It works!
The heat map shown looks really cool!

## What I learned
Web development skills

## What's next for it-is-noisy
1. A 4-infinity points 3D pin point system to find the noise maker without the noise maker needing to install the app
2. A more secure data structure

### Try it online
https://octo-kumo.github.io/it-is-noisy/

### Demo Videos
1. [Demo 1](https://youtu.be/CPCLDOhJSQA): General demo
2. [Demo 2](https://youtu.be/nkK9SdxETrA): Changing location

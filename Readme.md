> @popescuaaa 2020
# PPSQ
## Pragmatic Particle System Quantification
---
## Description
- This project aims to a be an eficinet particle engine that allows the user to configure different parameters and to experiment: particle lifespan, particle size, engine configuration and so on.
- The project biggest challange is to adapt Three js standard old js code to new es6 code and to enhance the current functionality until the engine will be resource efficient and more than that, prepared for any future adition (basically my aim is to make the code modules independent and ready to be used in another circumstances)
## Setup
- Three.js + Vanilla JavaScript
## How to make the particle system efficent ?
- The main strategy is by recycling old particles into new one without continus creating new particles and delete old ones, as the amount of data that will be send to the GPU will be significanly large

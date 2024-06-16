# Component Switch (WIP)

A 2-input 1-output component switch (WIP). Meant as a very low cost & small automatic component video switcher that detects the analog video signal on one of two inputs and uses multiplexers to switch between the two sources. Uses an MSP430 microcontroller as the main logic IC. 

### TODO
- [x] General PCB Design & Idea
- [ ] Finalize PCB Design
- [ ] Write code for microcontroller
- [ ] Model housing for switch
- [ ] Test all components

This is meant to be an alternative to the gcompsw for those who don't have as many video sources or the budget. I wanted to make something simpler for my case since I couldn't justify spending that much on a video switch and I think this might work. It's designed to work with two older game consoles and a single AV input on a TV or reciever. In addition to automatically detecting a signal and switching the source, there is a manual override switch in the current design. Note that while the gcompsw is a packaged product with all the conveniences that come with it, this is not however and so its niche is much smaller. If you want to make a copy of the switch for yourself, you'll obviously need to look into getting all the components, getting the PCB manufactured, flash your microcontroller, and print the housing before being able to use it.

The reason for choosing an MSP microcontroller as the main logic IC in this project is simply because I am re-purposing it after being finished with my design project for a university course which you can take a look at here: https://github.com/ShyavanS/PID_TEC_Temperature_Controller_Design_Project


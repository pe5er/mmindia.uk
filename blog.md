---
title: Blog
---

### Final Preparations

_April 2019_

**Peter**

The trip to Gregynog has quickly approached, as has the final revision of our MicroMouse robot. It has been a fun an interesting project, and I am very happy with both the developments we have made and our final result. Unfortunately we didn't complete our custom PCB in time, due to a short between the power and ground rails of the MC9S08AW60 that we were unable to trace the source of. We still have a respectable robot with an LCD and surface mount white line sensors to bring for the assessment!

**Jojo**

For the final hours, I worked on an algorithm for the line following which never stops any motor but slows them down. This should speed up the micromouse, as corrections in direction do not result in a full stop of one wheel. As we needed to prepare for the assessment and start up our presentation this feature is not in our final micro mouse. However, we output the position of the micromouse relative to the line on the screen as a value from 1 to 9 with 5 being the centre.

**Farah**

Be ready after easter break ,First week of April sessions the soldier the the components and getting ready for the assessment and looking forward for Gregynog.

**Jacky**

In April, most of the parts of hardware and software are done. One final step to complete the whole project are assembling the sensors on the micromouse and some modification about the programming.

**Team:India**

* * *

### New PCB

_March 2019_

**Peter**

This month I've mostly been working on the new PCB. This PCB is a single, double sided board that will cover all the functions of the MicroMouse. It contains the MCU, White Line circuit, Infra-Red circuit and LCD circuit

**Jojo**

This month I continued the programming for our micromouse. A working battle mode program alongside a menu on the LCD screen was implemented which uses the collision buttons to swap between obstacle avoidance, line following and battle mode.

Further, I cleared up our prototype and soldered a screen header to it so that we have a backup version in the case that we do not get our single PCB setup working in time.

**Farah**

In march eg-252 sessions as a group we have done a new PCB design it print it and drill it, the board is drilled by me.

**Jacky**

In March, I was working on the white line following sensor. Some technical problems like bad soldering, bad connections arose. I spent considerable time to re-solder those circuit in order to get it work.

**Team:India**

* * *

### Line Following

_February 2019_

**Peter**

We have made great progress over the last few weeks, as we now have a MicroMouse that is capable of both line following, and basic combat modes. We purchased some surface mount infra-red line sensors, and built a very compact circuit to detect white lines. I was involved in choosing these integrated circuits, and soldering together a prototype circuit.

I have also been using KiCad to design the final, double sided PCB that we intend to use at Gregynog for the final assessment.

**Jojo**

After the holidays break, our group got together to decide on our special feature: an LCD screen. I spend the majority of the lab sessions this month on enhancing Dr. Tim’s C program for our needs. After getting numbers and characters outputted to the screen for the first time it got really easy to read in sensor values, prints their intensity on the screen and uses those to debug and calibrate our white line following algorithm.

**Farah**

As a team after we built the micromouse and its start work we built a line following sensors and start to do the codes to follow the white line, each member in the team trying hard to get a great result at the end and be ready for the assessment on 13th of march to check the line following micromouse and the combat..

Our plans for March are to build a new PCB and build 3D printing case.

Looking forward to complete our work next few months.

**Jacky**

**Team:India**

* * *

### First Movement!

_November 2018_

**Peter**

This month we have made great strides of progress in our micromouse project: completing the intra-red and line following circuits on breadboard, testing different IR sensors, and building a prototype micromouse robot that was able to move in a straight line and detect collisions.

We were also given the PCB Schematic for the infra-red circuit, which I have been laying out on a PCB. To do this I have been using Proteus EDA software.

The website has seen great improvement over this month, with the addition of the project management section and public documents. Overall I'm very pleased the the progress and development that Team:India has achieved over the past few weeks

**Jojo**

This Month Jacky and I got the LDR breadboard circuit working. We derived optimal resistor values to replace the potentiometer for the final circuit. The rest of my lab time was spent on researching and coming up with ideas for the Aesthetic Design and what the special feature of our Micromouse could be. Our favourite idea is to use a Boost Converter to get more energy of the battery onto the track. It still needs to be decided on whether it is possible or worth it to build one from scratch, or if it is cheaper and more effective to get premade components in order to get a more consistent output voltage.

**Farah**

On November the MM circuit have been built in breadboard and test it works successfully.

We have test the wheels and the speed of them.

The website is ready to be publish.

Our plans for next month to finish the circuit in the actual board and do the sensors for the MM.

**Jacky**

In the time of November, I tested the speed condition of the motor which is connected to the microcontroller. In the test, we use the HMC 8042 (Rohde&Schwarz) power supply as the power source of the motor. We tested the motor with the input voltage which with is lower than 4 volts. Also, I proposed some ideas to the team about how the outer frame of our micromouse should be. Such as a character from the mobile game(Plants VS Zomble) and R2D2 from Star Wars.

**Team:India**

* * *

### Getting Started

_October 2018_

**Peter**

The goal of the first month of the MicroMouse project was to establish ourselves as a team, discover what each other's strengths and weaknesses were, and ultimately to get started with some of the first tasks we need to achieve to get the project on the road.

Our team was chosen by the Electrical and Electronic Engineering departmnet, by pairing together students with a variety of different skillsets, in order to create a balanced team. One of our first tasks was to use this information to decide which aspects of the project we'd each be best at doing, based on our skillsets.

We completed a skills matrix, allocating different team members to each part of the project. We were also tasked with setting up a Microsoft Team group, complete with a Kanban project management board, group chat and file collaboration. We quickly grew used to the Kanban board, using it to assign tasks that needed to be completed. The Kanban system allows us to move tasks between three columns. 'Deliverables, Work in Progress, and Done'.

**Jojo**

Organization and project planning consumed most of the time of the first month. The two main topics I was busy with was setting up a basic Website for our team with Peter and building an LDR bread board circuit with Jacky. Once working and tested this circuit will be used for the line following task. To enhance the design of our website I started to recap on basic html and CSS programming using the Website [w3schools.com](https://www.w3schools.com/).

**Farah**

In first session for EG-252 each student has choose roles and skills to start work in micromouse. Teams were choose randomly. In first week for micromouse project was for team bonding and decide what to do and the responsibilities for each member of the team. I have choose to do hardware stuff such as breadboard and soldering. Breadboard has been built in the laboratory. Last lab in October is the assessment week for project management and project skills matrix.

[Video of working Infra-Red circuit](/gallery)

**Jacky**

At first, I had discussed with my teammates about the positions of each persons in the whole project. After allocating the duties, I am the researcher of the team. It is basically a job of finding useful information that I can enhance the quality of our product. Then, I was busy building up the white line sensor, which is able to keep our micromouse moving along a white line, with jojo.

**Team:India**

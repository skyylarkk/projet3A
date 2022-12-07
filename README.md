# Robot arm project

This project is carried out by a three-students group in option Mechatronics and Complex Systems at ENSEA.

### Objectives

Our project consists in the realization of a 6-axis robot capable of catching and maintaining without damaging it a pot of yogurt. This could help people with disabilities.

### Mecanics

The mechanical part of the robot is modelled using SolidWorks software and then printed in 3D. The corresponding folder in the repository lists the various elements of the robot and their associated SolidWorks files (parts + assembly).

### Power module

In order to make the robot work, we need to build a power module to distribute the right power to every parts of the robot. The robot is powered by alternative by 230 V at 50 Hz.

### Steppers code

We chose to command the steppers with a STM32 nucleo-G431RB card. We use the STM32CubeIDE software. The different code files for the command of these steppers are present in the corresponding folder in the repository.

## To start

Here are the different instructions instructions instructions to follow to make the project work :

### Requirements

In order to make the project work, you will need the following softwares :

- STM32CubeIDE
- SolidWorks
- a software to print in 3D
- a software for PCB modeling

You also need this equipement to build your robot :

- a 3D-printer
- a STM32 Nucleo-G431RB
- 3x stepper motors with at least a 4N tork 
- 2x AX-12
- 2x XL-320
- 
- 

## Starting

In the different folders of the repository you have access to the code for the steppers, the mecanical parts and the PCB scheme for the power module of the robot.

- for the steppers code, you need to use STM32CubeIDE to upload the code on your Nucleo. Be careful to use the code from the last stable version for this project.
- for the mecanical parts, you have acces to the files you can open with SolidWorks. It is useful if you want to modify the different part ase you want, but it can possibly impact the proper functioning of the robot. You also have access to STL files of every mecanical parts in order to print it in 3D.
- for the PCB, you have all the files needed to build it in order to make the robot work.

## Built/developped with

* [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) - for the steppers code
* [SolidWorks](https://www.solidworks.com/) - for the mecanical parts

## Versions

**Last stable version :** 1.0
**Last version :** 1.0

## Autors

* **CHAPUIS Clément** _alias_ [@ClementChapuis](https://github.com/ClementChapuis)
* **HERAULT Félix** _alias_ [@FelixHerault](https://github.com/FelixHerault)
* **SUTRA Aurélien** _alias_ [@skyylarkk](https://github.com/skyylarkk)


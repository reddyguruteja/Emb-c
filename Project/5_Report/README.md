
# Requirements:-
# Introduction
# ULTRASONIC SOUND SENSOR WITH ATmega328 MICROPROCESSOR
 The project as the name suggests is based on Ultrasonic sensors.Ultrasonic sensors work by sending out a sound wave at a frequency above the range of human hearing. Our ultrasonic sensors, like many others, use a single transducer to send a pulse and to receive the echo. The sensor determines the distance to a target by measuring time lapses between the sending and receiving of the ultrasonic pulse.
 # Requirements:
 # High Level Requirements:
 -> It can send echo to find object
 -> It can able to detect Moving object
 -> Moving object signal will displayed on a display unit
 
 # Low Level Requirements:
 ->  We can find the exact location of an Target
  -> It can find distance of an object
  -> It can find speed of an object
  -> It can display distance of an object
 # Research
 The requirements for the program to run or for the code to be in effect are basic and a great solution for the detection of clear objects.
# SWOT ANALYSIS:-
# a) Strength:
The distance to an obstacle can be measured with the low cost ultrasonic sensor . The sensors can measure distances form 2 to 400cm with an accuracy of 3mm. This sensors module includes ultrasonic transmitter, ultrasonic receiver and control circuit.

# b) Weakness:
Although we fully believe in the capability of our sensors, we understand that ultrasonics are not suited for every application. Focuses of low thickness, similar to froth and fabric, have a tendency to assimilate sound vitality; these materials may be hard to sense at long range.

# c) Opportunity:
This project Can be used as parking assistance systems in vehicles with high power ultrasonic transmitter. This Project Can be used as burglar alarm with suitable additional software for homes and offices.

# d) Threats :
Ultrasonic sensors must view a surface (particularly a hard, level surface) unequivocally (oppositely) to get adequate sound reverberation. Additionally, solid detecting requires a base target surface range, which is indicated for every sensor sort. If connection is wrong there might be chances of short-circuit.

# 4W's an 1H :-
# What:
we have made a setup based on a microcontroller in which real time distance is sensed by an ultrasonic sensor and displays measured distance on an LCD display.

# Where:
It measures accurate distance using a non-contact technology - A technology that involves no physical contact between sensor and object.

# When: 
In 1959, Satomura created an ultrasonic flowmeter that used doppler technology.

# Why: 
I am Developing this project for easily measure the distance between objects

# How:
By using Atmega328 an display an ultrasonic sensor mainly used to determine the distance of the target object.

# Advantages:
•The ultrasonic sensor has high sensitivity, high frequency and high penetrating power therefore it can easily detect the external or deep objects.
        •The use of ultrasonic sensor makes this system more accurate and precise than other methods.
        •This system is easy to use, not dangerous during operation for nearby objects, person, equipment or material.
        •Radar systems have a number of defense as well as civil applications.
        
 # Applications:
       •It is used in machines like Automotive parking sensor obstacle warning systems,industrial distance measurements, terrain monitoring robots.
       •RADAR speed meters are used by the traffic police for enforcing speed limit.
       •Marine RADARs used to locate the landmarks and other ships.
       •Air traffic control uses radars to track aircraft on the ground, in the air and to guide planes for smooth landings.
# Bill Of Materials
 # a) SOFTWARE :-
# 1] SimulIDE:
  - SimulIDE provides AVR, Arduino and PIC microcontrollers that can be accessed just like other components. 
  - Features like gpsim and simavr allow you to use PIC and AVR microcontrollers, respectively.
  - Editor/Debugger is still in its firsts stages of development, with basic functionalities, but it is possible to write, compile and perform basic debugging with
      breakpoints, watch registers and global variables.
      
 # 2] AVR:
   - An automatic voltage regulator (AVR) is an electronic device that maintains a constant voltage level to electrical equipment on the same load.
  - The AVR regulates voltage variations to deliver constant, reliable power supply.
  - Features:
    i] SENSING INPUT. Voltage.
    ii] POWER INPUT (PMG) Voltage.
    iii] REGULATION. +/- 1% (see note 1)
 # b) HARDWARE :
 # 1] ATmega328:
    - ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed
  - Perhaps the most common implementation of this chip is on the popular Arduino development platform. 
  - ATMEGA328P is an 8-bit microcontroller based on AVR RISC architecture.

# 2] Sound (HC-SR04 sensor):
  - A sound sensor is defined as a module that detects sound waves through its intensity and converting it to electrical signals.
  - The HC-SR04 sensor works best between 2cm – 400 cm (1" - 13ft) within a 30 degree cone, and is accurate to the nearest 0.3cm.
  - Features:
    i] Input Voltage: 5V
    ii] Current Draw: 20mA (Max)
    iii] Digital Output: 5V
    iv] Digital Output: 0V (Low)
    v] Working Temperature:  -15°C to 70°C
    vi] Sensing Angle: 30°Cone
    vii] Angle of Effect: 15° Cone 
    viii] Ultrasonic Frequency: 40kHz
    ix] Range: 2cm - 400cm
 #  3] Display (16x2 lcd):
  - A display device is an output device for presentation of information in visual or tactile form.
  - Features:
    i] The operating voltage of this LCD is 4.7V-5.3V.
    ii] It includes two rows where each row can produce 16-characters.
    iii] The utilization of current is 1mA with no backlight.
    iv] Every character can be built with a 5×8 pixel box.
  
  # 4] Potentiometer:
  - the input impedance to be an order of magnitude (10 times) higher than the output (source) impedance.
  - Potential gradient is calculated as K = V/L, where V is the voltage across the potentiometer wire and the L is the length of the wire in the potentiometer.
  - Features:
    i] Resistance :	1K Ohm 
    ii] Potentiometer Type 	Pot Potentiometer 
    ii] Material	Carbon Film and Metal
    iv]Interface	3 Pin
    v]Shaft Length	15mm
    vi]Dimensions 	1 x 1 x 1cms 
    vii]Weight :15 grams
 
# Block Diagram:

# FlowChart![flow chart](https://user-images.githubusercontent.com/98813939/157236786-a31181a7-41ac-442f-a1b1-ca9753fc630b.png)

# System block diagram
![block diagram](https://user-images.githubusercontent.com/98813939/157236832-d4641104-bf4d-4f20-8b55-85a1b2cd78cf.png)

# Circuit Design
![u 1](https://user-images.githubusercontent.com/98813939/157236877-80be2c1b-b1da-4c6f-8fb4-dc817e1ec56a.png)

# Conclusion
The objective of the project was to design and implement an ultrasonic distance meter. The device described here can detect the target and calculate the distance of the target. The ultrasonic distance meter is a low cost, low a simple device for distance measurement. The device calculates the distance with suitable accuracy and resolution. It is a handy system for non-contact measurement of distance. The device has its application in many fields. It can be used in car backing system, automation and robotics, detecting the depth of the snow, water level of the tank, production line. This device will also have its application in civil and mechanical field for precise and small measurements. For calculating the distance using this device, the target whose distance is to be measured should always be perpendicular to the plane of propagation of the ultrasonic waves. Hence the orientation of the target is a limitation of this system. The ultrasonic detection range also depends on the size and position of the target. The bigger is the target, stronger will be the reflected signal and more accurate will be the distance calculated. Hence the ultrasonic distance meter is an extremely useful device.

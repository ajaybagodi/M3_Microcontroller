# M3_Microcontroller
# Block Diagram
![STM32F4-Discovery-Hardware-block-diagram](https://user-images.githubusercontent.com/46984887/156366488-bd33d54a-8d16-4a7f-b18f-ff9a788c172f.png)
delete repository




## Applied Model Based Design

## Description
Anti-lock Braking System also known as anti-skid braking system (ABS) is an automobile safety system which prevents the locking of wheels during braking and avoid uncontrolled skidding. The modern abs system allows steering during braking which gives more control over the vehicle in case of sudden braking.
The main advantages of using ABS system in vehicle is that it provides better control over the vehicle and decreases stopping distance on dry and slippery surfaces. Since in ABS installed vehicle the chance of skidding is very less and hence it provides a better steering control during braking. Without ABS system, even a professional driver can fail to prevent the skidding of the vehicle on dry and slippery surfaces during sudden braking. But with ABS system, a normal person can easily prevent the skidding of the vehicle and get better steering control during braking.

## Abstact

Antilock Breaking System (ABS) is used in advanced automobiles to prevent slip and locking of wheel after brakes applied. It is automobile safety system, the controller is provided to control the necessary torque to maintain optimum slip ration. The slip ration denote in terms of vehicle speed and wheel rotation. It's an automated system that run on principles of threshold braking and cadence braking which were practiced by skillful drivers with previous generation braking system. It response time is very faster so that makes easy steering for the driver. ABS generally offer advanced vehicle control and minimize the stopping distance in slippery and dry surface, conversely on loose surface like gravel or snow covered pavement, ABS can significantly increase braking distance, although still improving vehicle control.


## Features
1.To reduce stopping distance
2.stability
3.steerablity


## Objectives
## To reduce stopping distance
1. The road surface type and conditions can be inferred from the vehicle's
braking pressure, wheel slip measurements, and deceleration rate
comparisons.
2. The wheel slip is regulated so that the road adhesion coefficient is
maximized. By keeping all of the wheels of a vehicle near the maximum
friction coefficient, an antilock system can attain maximum fictional
force
3. In turn, this strategy leads to the minimization of the vehicle stopping
distance.

## Stability
1. A locked-up wheel generates a reduced braking force, smaller than the peak
value of the available adhesion between tires and road. A locked-up wheel
will also lose its capability to sustain any lateral force. This may result in the
loss of vehicle stability.
2. The basic purpose of a conventional ABS system is thus to prevent any
wheel from locking and to keep the longitudinal slip in an operational range
by cycling the braking pressure.
ANTILOCK BRAKING SYSTEM 6
## Steerability
1. Good peak frictional force control is necessary in order to achieve
satisfactory lateral forces and, therefore, satisfactory steer-ability. 
2. If an obstacle appears without warning, emergency braking may not be
sufficient. When the wheels are locked, car no longer respond to the driver’s
steering intention.
3. With ABS car remains steerable even during emergency braking, and thus the 
obstacle can be safely avoided
## Images

## Block Diagram
![image](https://user-images.githubusercontent.com/46984887/159897122-78ee81bc-521a-4423-b258-e79442be7c46.png)

## Flow chart

![image](https://user-images.githubusercontent.com/46984887/159905667-37d7e058-5c63-49bd-8e73-aed61d281e2a.png)
![image](https://user-images.githubusercontent.com/46984887/159905973-9d3b9a1f-6857-4f3d-8d17-81517035c5b6.png)

## Requirements

## High Level Requirements

|ID|High Level Requirements|
|--|-----------------------|
|HLR1|When Driver press the Brake Pedal, Piston presses the Brake Fluid & Then ECU Sends signal to Solenoid Valve & Pump|
|HLR2|When Wheel stops due to Brake, Speed Sensor sends signal to ECU. ECU Sends signal to Pump & Solenoid Valve to Stop Brake Fluid flow & Release Pressure on Wheel (By Return the Brake Fluid through the Return line)|
|HLR3|Again Speed Sensor sends Signal to the ECU about wheel Speed. Again ECU Sends signal to Solenoid Valve & Pump to Start Flow|

## Low Level Requirements

|ID|Low Level Requirement for HL01|ID|Low level Requirement for HL02|ID|Low Level Requirements for HL03|
|---|-----------------------------|--|------------------------------|---|------------------------------|
|LLR1|Hence Brake Fluid flows from –   MASTER CYLINDER -> PUMP -> ACCUMULATOR -> SOLENOID VALVE -> WHEEL DRUM|LLR2|WHEEL DRUM-> SOLENOID VALVE -> ACCUMULATOR   Therefore Wheel again starts to Rotate|LL03|Hence Again Brake Fluid flows from –   PUMP -> ACCUMULATOR -> SOLENOID VALVE -> WHEEL DRUM

This Steps occurs Rapidly till Vehicle Speed Reduces or Vehicle Stops Without Skidding|

## Components of ABS system

It has four main components
1. speed sensors
2. Valves
3. Pump
4. Controller

## Speed sensors:
Detect how fast the wheels rotate
## Valves: 
Located in the brake line, these stop and release pressure on the brakes
## Pump: 
Applies pressure to the calipers, or brake drums, and are filled with hydraulic fluid
# Controller: 
Takes data from the sensors and controls when to pump the brakes


##  Anti-lock Braking System (ABS)

The controller (ECU-Electronic Control Unit) reads the signal from each of the speed sensors of the wheel.
As the brakes are suddenly applied by the driver, this makes the wheel to decelerate at faster rate and may cause the wheel to Lock.
As the ECU reads the signal which indicates the rapid decrease in the speed of the wheel, it sends signal to the valve which makes the valve close and the pressure to the brake pad reduces and prevents the wheel from locking.
The wheel again starts to accelerate, again the signal sends to the controller, this time it opens the valve, increasing the pressure to the brake pad and brakes are applied, this again reduces the speed of the wheel and tries to make it stop.
This process of applying brakes and releasing it happens 15 times in a second when a driver suddenly applies the brake harder. Due to this the locking of the wheel is prevented and the skidding of the vehicle eliminated. During braking with ABS system, the driver can steer the vehicle and reduces the risk of vehicle collision.
For Better Explanation about Anti-lock Braking System Watch the Video Given Below:

 
## ABS System Operation

conventionally, the work of the anti-lock braking system is divided into 3 stages:

## Wheel lock - the ECU sends a signal to activate the system;
## Actuation of the actuator - the hydraulic block changes the pressure in the system, which leads to the unlocking of the wheels;
## Deactivation of the system when wheel rotation is restored.
It is worth considering that the whole process is controlled by algorithms embedded in the control unit software. The reliability of the system lies in the fact that it is triggered even before the wheels lose traction. An analogue that works only on the basis of wheel rotation data would have a simpler design and principle of operation. However, such a system would work no better than the first designs of Gabriel Voisin.

When the ABS in operation, it can be felt by the driver through pulsation in the brake pedal; this happens because of the rapid opening and closing of the valves. The pulsing action of the pedal tells the driver that ABS system is in operation. Any fault in the ABS system is indicated on the instrument panel of the vehicle and it will work when the fault is completely removed.

## SWOT Analysis

## STRENGTH
 ABC helps to Stop Constant locking of vehicle wheel, Hence Results in Vehicle stops without the skidding of wheel.
## WEAKNESS
High cost 
## OPPTURNITY
High Resale Price
## THREAT
One of the threat of ABS is it's "Delicate" It's easy to cause a problem in an ABS by messing around with the brakes. Problems include disorientation of the ABS, where a compensating brake sensor causes the vehicle to shudder, make loud noise or generally brake worse.

## 5W's && 1'H

## WHO
Any person who can drive vehicle can operate it easily
## WHAT
On a hard brake wheels not get locked ,instead wheels get slows down and stops at certain distance
## WHEN
To stop vehicle at quick situations friction between the roads and tyre surface is increased
## WHERE
It is found in alomost all modern vehicles & widely used in Automobiles
## WHY
to avoid skidding while braking. 
## HOW
Developed using the sensors & Electronic Control Unit implemented on a hardware

## Advantages & Disadvantages

## advantages
It prevents the locking of the wheel and thus eliminates the chance of skidding.
The skidding of the vehicle is completely removed, which results in excellent control during braking?
A better steering control is obtained with the ABS system.
It reduces the chance of collision by 30 %.

## Disadvantages
A vehicle equipped with ABS (Anti-lock Braking System) is costlier as compared with a vehicle without ABS.






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


## Features/Functions
1.To reduce stopping distance
2.stability
3.steerablity

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

## sped Sensors
It is used to calculate the acceleration and deceleration of the wheel. It consists of a toothed wheel and an electromagnetic coil or a magnet and a Hall Effect sensor to generate signal. When the wheel or differentials of the vehicle rotates, it induces magnetic field around the sensor. The fluctuation in this magnetic field generates voltage in the sensor. This voltage generated sends signals to the controller. With the help of the voltage the controller reads the acceleration and deceleration of the wheel.
 

##  Valves
Each brake line which is controlled by the ABS has a valve. In some of the systems, the valve works on three positions.
In position one, the valve remains open; and pressure from the master cylinder passed through it to the brake.
In position two, the valve blocks the line and separates the brake from the master cylinder. And this prevents the further rise of the pressure to the brakes. Valve operates in second position when the driver applies the brake harder.
In position three, some of the pressure from the brake is released by the valve.
The clogging of the valve is the major problem in ABS. When the valve is clogged, it becomes difficult for the valve to open, close or change position. When the valve is in inoperable condition, it prevents the system form modulating the valves and controlling pressure to the brakes.
 

## Pump
Pump is used to restore the pressure to the hydraulic brakes after the valve releases the pressure. When the controller detects wheel slip, it sends signals to release the valve. After the valve releases the pressure supplied from the driver, it restore a desired amount of pressure to the braking system. The controller modulates (adjust) the status of the pump so as to provide desired amount of pressure and reduce slipping of the wheel.
 

## Controller
The controller used in the ABS system is of ECU type. Its main function is to receives information from each individual wheel speed sensors and if a wheel loses its traction with the ground, a signal is sent to the controller, the controller than limit the brake force (EBD) and activate the ABS modulator. The activated ABS modulator actuates the braking valves on and off and varies the pressure to the brakes.

## Speed sensors: Detect how fast the wheels rotate
## Valves: Located in the brake line, these stop and release pressure on the brakes
## Pump: Applies pressure to the calipers, or brake drums, and are filled with hydraulic fluid
# Controller: Takes data from the sensors and controls when to pump the brakes


##  Anti-lock Braking System (ABS)

The controller (ECU-Electronic Control Unit) reads the signal from each of the speed sensors of the wheel.
As the brakes are suddenly applied by the driver, this makes the wheel to decelerate at faster rate and may cause the wheel to Lock.
As the ECU reads the signal which indicates the rapid decrease in the speed of the wheel, it sends signal to the valve which makes the valve close and the pressure to the brake pad reduces and prevents the wheel from locking.
The wheel again starts to accelerate, again the signal sends to the controller, this time it opens the valve, increasing the pressure to the brake pad and brakes are applied, this again reduces the speed of the wheel and tries to make it stop.
This process of applying brakes and releasing it happens 15 times in a second when a driver suddenly applies the brake harder. Due to this the locking of the wheel is prevented and the skidding of the vehicle eliminated. During braking with ABS system, the driver can steer the vehicle and reduces the risk of vehicle collision.
For Better Explanation about Anti-lock Braking System Watch the Video Given Below:

 


 

## ABS System Operation


When the ABS in operation, it can be felt by the driver through pulsation in the brake pedal; this happens because of the rapid opening and closing of the valves. The pulsing action of the pedal tells the driver that ABS system is in operation. Any fault in the ABS system is indicated on the instrument panel of the vehicle and it will work when the fault is completely removed.

## advantages
It prevents the locking of the wheel and thus eliminates the chance of skidding.
The skidding of the vehicle is completely removed, which results in excellent control during braking?
A better steering control is obtained with the ABS system.
It reduces the chance of collision by 30 %.

## Disadvantages
A vehicle equipped with ABS (Anti-lock Braking System) is costlier as compared with a vehicle without ABS.
|HL01|

## SWOT Analysis

## STRENGTH
 ABC helps to Stop Constant locking of vehicle wheel, Hence Results in Vehicle stops without the skidding of wheel.
## WEAKNESS
High cost 
## OPPTURNITY
High Resale Price
## THREAT









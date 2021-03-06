# LDR-Darkness-sensor-circuit


![image](https://user-images.githubusercontent.com/19898602/138691113-cffc3beb-e55e-4910-bc24-84e617ed77df.png)


In this article we will see how can we build a darkness sensor by using LDR sensor. This sensor detect light falling on it and change it resistance accordingly.
This change in resistance of LDR detect by a circuit. Which turn led ON When light is not falling on LDR and turn LED OFF when light falling on LDR.

By using such characteristic of LDR we can build a LDR Darkness sensor circuit which turn ON light in darkness and turn OFF light when there is sufficient light. Also we can build reveres of it also if required.


# How it works

LDR stands for light dependent resistor, as name suggest it is a type of resistor whose resistance is depends on the amount of light falling on it.
LDR is made up of high resistance semiconductor.
When light photons fall on LDR this photons are absorbed by the semiconductor this gives enough energy to the bound electron to jump to the conductive band.
as a result free electron as available in LDR this makes it more conductive and drop in resistance of LDR.
In dark its resistance is high as several mega ohm, and in light its down to few ohms.

This change in resistance of LDR will detect by a circuit and it will turn on LED accordingly, we will see such type of circuit in below examples.

![image](https://user-images.githubusercontent.com/19898602/138692279-a341be64-6566-435c-bf53-9f67de749a03.png)


LDR is a photoresistor is a light-controlled variable resistor.

The resistance of a photoresistor decreases with increasing incident light intensity,

in other words, it exhibits photoconductivity.

A photoresistor can be applied in light-sensitive detector circuits, and light- and dark-activated switching circuits.


![image](https://user-images.githubusercontent.com/19898602/138692365-84746b06-baac-43e3-bde1-c9f262302ad2.png)


A photoresistor is made of a high resistance semiconductor.

In the dark, a photoresistor can have a resistance as high as several megohms (M??),

while in the light, a photoresistor can have a resistance as low as a few hundred ohms.

![image](https://user-images.githubusercontent.com/19898602/138692406-0eb9e5b1-5fcb-4df6-ae54-236aa2b8a246.png)


BC547 is an NPN bi-polar junction transistor. A transistor, stands for transfer of resistance, is commonly used to amplify current. A small current at its base controls a larger current at collector & emitter terminals.

BC547 is mainly used for amplification and switching purposes. It has a maximum current gain of 800. Its equivalent transistors are BC548 and BC549. data sheet

50K ohm resistor one end is connected with Positive (9V) of battery and other end is connected in series with LDR and LDR another point is connected with negative of battery

here in video I have used 2 100Kohm resistor in parallel because i dont have 50K one.

1K OHM resistor one end is connected with Positive (9V) of battery and other end is connected with anode (positive) of LED

Cathode (negative) of LED is Connected with C (collectr) of BC 547 Transistor

Emitter (E) of transistor is connected with the negative of battery

Base (B) is connected Junction point of the 50K resistor & LDR

it is a simple and powerful concept , which uses transistor ( BC 547 NPN) as a switch to switch ON and OFF the LED LIGHT automatically .
It automatically switches ON lights when the light goes below the visible region of our eyes. ( e.g in evening after Sunset ). it automatically switches OFF lights when light fall on it ( e.g in morning ) , by using a sensor called LDR (Light Dependent Resistor) which senses the light just like our eyes.

# VIDEO

Here is the video of project in action, you can watch the video and for more details continue to read the post.

https://youtu.be/jqHOPSL2MMU

# LDR Circuit to turn on LED in dark

![image](https://user-images.githubusercontent.com/19898602/138691228-e2bf144a-f14d-4ade-859e-863c94eecfff.png)



# Component used

>> 9V battery


>> LDR sensor


>>50K, 1K Ohm resistor


>>BC547 Transistor

So when sufficient light falling on LDR the resistance of LDR in very low, as a result all current is flowing from resistor R2 AND LDR so LED D1 is not glowing,


When there is dark and no light is falling on LDR, so the LDR resistance became very high so current will flow ro the base of transistor Q1 BC547, so transistor became turn on, and LED D1 glow.

# LDR Circuit with adjustable sensitivity using potentiometer

![image](https://user-images.githubusercontent.com/19898602/138691373-f43a5ed2-b54c-4876-a076-95d7734dadaa.png)


# Component used


>> 9V battery


>> LDR sensor


>> 10K Ohm potentiometer


>> 1K Ohm resistor


>> BC547 Transistor

In this circuit we can adjust the sensitivity of darkness sensor by using potentiomter,

## LDR Circuit to glow 230V AC load


![image](https://user-images.githubusercontent.com/19898602/138691482-cdc9a57d-0881-4fa1-8bd9-549d803e8b07.png)


##  Component used


>> 9V battery


>> 5V DC relay


>> 230V AC Lamp


>> 50K, 1K Ohm resistor


>> 1N4007 Diode


>> BC547 Transistor


>> 50K, 1K Ohm resistor


>> BC547 Transistor

This Circuit is to operate 230V AC bulb or light on LDR circuit.
This will use in our house, garage, factory, building, street light to turn on lights in dark.

Here also the working principle is same just led is replaced by a DC relay to operate high voltage load,
When light is not falling on LDR the relay will operate and the contact of relay changeover, in this way 230V lamp get connected with 230V supply and start glowing.
A flyback diode 1N4007 is used to save circuit from back EMF generated by relay while de-energizing.


At last I would like to tell you something about custom PCB

Yes PCB are the heart of the electronics based project usually we hesitate to try custom PCB and opt to homemade solutions

like breadboard or Zero PCB earlier I also was in the same boat, I hesitate to try custom PCB my belief was they are much expensive.

but then I came to know about [JLCPCB.COM](https://jlcpcb.com/IAT) and I was totally surprised how low price PCB's are they offering 

there PCB quality is best in market, now I always go with PCB for my project and [JLCPCB.COM](https://jlcpcb.com/IAT) is my trusted 

If new user signup now using this link [JLCPCB.COM](https://jlcpcb.com/IAT) they will get 30$ coupon from [JLCPCB.COM](https://jlcpcb.com/IAT)

PCB manufacturer, you can also try there PCB service for more details you can visit their website [JLCPCB.COM](https://jlcpcb.com/IAT)
You can also try there new purple colour for PCB without any extra cost.
![image](https://user-images.githubusercontent.com/19898602/134336832-cb9953e9-02a6-4ff7-9d27-2caad10fe7c7.png)
![image](https://user-images.githubusercontent.com/19898602/130722577-c30b7b43-ea89-4847-9c6b-058f9fabeda3.png)![image](https://user-images.githubusercontent.com/19898602/130722585-b5268db1-5f17-428f-ba60-b823140f2a70.png)


![MVI_0001](https://user-images.githubusercontent.com/19898602/138692079-5da22769-b21e-4cd6-8863-329b59b5b586.gif)


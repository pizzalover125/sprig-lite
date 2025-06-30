---
title: "Sprig Lite"
author: "pizzalover125"
description: "A mini game console."
created_at: "2025-06-25"
---
**Time Spent: 12 hours**
### 6/5/25
A couple of years ago, I got introduced to the attiny85 in an electronics class. I basically built this exact project on a breadboard. That was SUPER cool and was where I began my electronics journey. Ok so I began with the PCB. Schematic was super simple, as the attiny85 is super simple. Originally, I was thinking to have a CR2032 for a battery as it is super small and minimalist. Then I realized that I could make a game console fit on the back of 2 AA batteries. I also liked that because it would give me infinite battery life. So I went with that. I then made the PCB layout and routed everything super fast. It was super easy. 
![image](https://github.com/user-attachments/assets/c3d7c2f5-2123-4e29-8276-62156d9abbfe)

### 6/7/25
Today I made some minor refinements. First, I added PCB silkscreen art. I also decided to call this project "sprig-lite" and use their artowrk and stuff. Then, I decided to add an aditional button for the ability to play more games. For some reason changing the switch was super hard. KiCad just wouldn't work :cry:. Eventually, I got this one model to work. I also calculated that this device will literlly have 60-70 hours of battery life. I also made the BOM. This project, I'll use Amazon because AliExpress is just too unreliable. I also decided to ditch the 3D case because its too pointless for a device supposed to be minimal and I don't want to make it bigger. Here is the finished product: EDIT: I'll include the case and use mounting tape. The reason is that I'll have to offset the PCB from the battery so the solder joints from the top don't hit the batteries. 
![image](https://github.com/user-attachments/assets/f291f75e-e7be-46b5-9cc1-9daa839cf048)

### 6/10/25
My project got rejected :( and I was told to make firmware. So... I did! Note that its heavily based off of the projects made in https://electronoobs.com/eng_arduino_tut120_code1.php. But then I realized I don't understand any of the code :(. So... instead of trying to rewrite the binary values, I just changed my schematic and PCB. 

### 6/29/25
I wanted to make this 6 points, so I was told to make a case. I agree, my case looks ABSOLUTELY DISGUSTING. It's literally just a box. So, I decided to add fins on both side so people could hold the console properly. It was pretty simple, but it looked complete with filets all over:
![image](https://github.com/user-attachments/assets/8d7f14b4-5fbe-4502-96bb-f0b7e599191a)

Then, I added a back panel that can be screwed off, so the batteries can be accessed. It used M3 screws btw:
![image](https://github.com/user-attachments/assets/77dc65fb-b461-4e06-8b02-2a9b0c9b5175)

And, we're done!



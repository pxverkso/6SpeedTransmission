## Pxl Shift
---
# A Six Speed Transmission using 3 planetary gearboxes, this transmission was designed with First Tech Challenge hardware but can be adapted to the user's hardware. 
# All files are in .STEP and .STL format for easy editing of parts. The program code is in the .zip file called FTCRobotController.
<img width="606" height="569" alt="image" src="https://github.com/user-attachments/assets/3687724b-a1ee-4549-80b9-dfb6b2834f2c" />  
<img width="3000" height="4000" alt="20260626_151211" src="https://github.com/user-attachments/assets/47fdbc50-f309-4952-b337-01f5dbe9654b" />

## How it works
The Transmission has 6 different speeds that can be shifted automatically. Each stage takes around 5 seconds to ramp up to shifting speed. 

## Why I made this
This was a great CAD Exercise where I was able to practice my tolerances. It was also a learning opportunity for me to learn how transmissions work and how gears are able to be switched simultaneously.


The CAD Model of Pxl Shift is [Available Here](https://cad.onshape.com/documents/75fb335df3e2ec43449c259f/w/3389e1c426c2c39876040c3b/e/85c02890f00469d3cc6075b8?renderMode=0&uiState=6a388c4a8541333eb969d891) for exporting, viewing or assembly. You don't need an account for Onshape to view assemblies. Please use this as the assembly instructions as well. 

## ASSEMBLY (IMPORTANT) 
I would explain the assembly process but it would end up being confusing for those of you actually building it since the part's all look similar so use the Onshape CAD. 
By looking at the left of your screen, you'll be able to see some folders of parts like the image below:
<img width="191" height="93" alt="Screenshot 2026-07-23 235255" src="https://github.com/user-attachments/assets/f055af9a-dd14-4d52-8957-20d93bad7746" />
Then Click the Eye Button to hide the assembly. Like below
<img width="191" height="93" alt="Screenshot 2026-07-23 235309" src="https://github.com/user-attachments/assets/59338973-d522-4340-a5d0-b7864f2b5f98" />
<img width="191" height="93" alt="Screenshot 2026-07-23 235323" src="https://github.com/user-attachments/assets/59e83745-657d-4b34-aad4-01bad83ef167" />

Hide All folders Except PG3 And Work Your way up in this File order:

PG3
PG2
PG1
Input Clutch
Base + Power Transmission
btrshftr

After You've build all the subsystems, you can just slide each subsystem into one another and it should assemble flawlessly. 


## Programming (If you'd like to motorize it)
For myself, I programmed my Pxl Shift on the 

## REV Robotics Control Hub 

A prebuilt PCB with preinstalled connectors and drivers, super easy to create projects like this for a programming newbie like me

An alternative PCB to this, if you want to build one yourself, is a Raspberry Pi with a Adafruit DC Motor Hat 
(Unfortunately you'll have to figure this out yourself, no code or drivers have been built for this project using these peripherals yet) 

My school let me borrow parts for this project and the parts I used can be easily substituted with much cheaper parts. Here are the parts list used in this [build](https://docs.google.com/spreadsheets/d/1n-YdPj7j1ZeOJgT02BMX6BGqi6td0hHqOzs9oTdzwKs/edit?usp=sharing)

Parts: (If you're worried about wires, if you order the motors from the website, wires are included in the package!)

| Link + Name | Price (Needed for build) USD | Price USD | Link | Total Price Needed for Build USD: | Column 5 | Total USD (Without Taxes): |
|:------------|:-----------------------------|:----------|:-----|:----------------------------------|:---------|:---------------------------|
| 8mm REX Bearing | $99.73 (72) | $5.99 | https://www.gobilda.com/1611-series-flanged-ball-bearing-8mm-rex-id-x-14mm-od-5mm-thickness-2-pack/ | $857.96 | | $857.96 |
| REV Robotics Control Hub | $375 (1) | $375 | https://www.revrobotics.com/rev-31-1595/?searchid=5410248&search_query=control+hub | | | |
| 12v Nimh Battery | $64.99 (1) | $64.99 | https://www.gobilda.com/12v-nimh-nested-battery-3000mah-mh-fc-xt30-connector/ | Note: | | |
| Smart Robot Servo | $100.80 (4) | $25.20 | https://www.revrobotics.com/rev-41-1097/ | I built this using parts that | | |
| 8mm REX® Shaft with E-Clip (Stainless Steel, 216mm Length) | $8.29 (1) | $8.29 | https://www.gobilda.com/8mm-rex-shaft-with-e-clip-stainless-steel-216mm-length/ | were lent to me by my school | | |
| M4 Screws | $54.99 (1) | $54.99 | https://www.gobilda.com/m4-socket-head-screw-assortment-pack-600-pcs/ | I did not pay any of these prices | | |
| 8mm REX® Shaft with E-Clip (Stainless Steel, 168mm Length) | $7.19 (1) | $7.19 | https://www.gobilda.com/8mm-rex-shaft-with-e-clip-stainless-steel-168mm-length/ | I built this as an offseason | | |
| 2000 Series Dual Mode Servo (25-2, Torque) | $36.99 (1) | $36.99 | https://www.gobilda.com/2000-series-dual-mode-servo-25-2-torque/ | project to showcase at district | | |
| 5203 Series Yellow Jacket Planetary Gear Motor | $109.98 (2) | $54.99 | https://www.gobilda.com/5203-series-yellow-jacket-planetary-gear-motor-13-7-1-ratio-24mm-length-8mm-rex-shaft-435-rpm-3-3-5v-encoder/ | events. | | |

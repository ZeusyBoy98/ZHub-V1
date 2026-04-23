# ZHub-V1
A basic USB hub built to suite my needs.
Made for Hack Club Fallout

## Zine
![Zine](IMG/ZHub-V1-Zine.png)

## What?
A basic USB hub with:
<ul>
<li> 1 Upstream USB-C
<li> 1 Downstream USB-C
<li> 3 Downstream USB-A
<li> USB 2.0 because I used a very basic chip
</ul>

## Why?
Because I don't have any USB-C USB hubs and A to C adapters are annoying. If I can just have one USB hub on me at all times, that can allow me to plug all the stuff I could possibly need in, then that achieves my goal.

## How?
In order to make this project for yourself, you'll need to purchase the board and get it assembled through PCBA with all the components below (PCB manufacturer-acceptable BOM at PCB/Gerbers/bom.csv). You'll also have to 3D print the case.
| Quantity | Item                 | URL                                                            | Unit Price ($USD) | Total Price ($USD)                |
| -------- | -------------------- | -------------------------------------------------------------- | ----------------- | --------------------------------- |
| 5        | CoreChips SL2.1A     | https://www.lcsc.com/product-detail/C192893.html?              | 0.2355            | 1.5920                            |
| 17       | USB A 2.0 Receptacle | https://www.lcsc.com/product-detail/C668591.html               | 0.0627            | 1.1288                            |
| 11       | USB C Receptacle     | https://www.lcsc.com/product-detail/C2765186.html              | 0.0633            | 0.7271                            |
| 60       | 1uf Capacitor        | https://www.lcsc.com/product-detail/C14445.html                | 0.0023            | 0.1380                            |
| 15       | 100nf Capacitor      | https://www.lcsc.com/product-detail/C1525.html?s_z=n_capacitor | 0.0013            | 0.0195                            |
| 30       | 5.1k Resistor        | https://www.lcsc.com/product-detail/C2906874.html              | 0.0006            | 0.0180                            |
| PCB      |                      |                                                                |                   | 3.10                              |
| PCBA     |                      |                                                                |                   | 30.78 (Includes component prices) |
| Shipping |                      |                                                                |                   | 9.24                              |
| Total    |                      |                                                                |                   | 43.12                             |

### Build Guide:

#### 1. Preparation<br>
Before starting, make sure you have:
<ul>
<li>The gerbers, pick and place files, and BOM, all available in this repository
<li>A 3D printer (or get the printed parts from someone else)
</ul>

#### 2. Ordering
Go to your PCB manufacturer of choice (Make sure they have PCBA) and follow their instructions on how to order.

#### 3. Case
3D print the print file, CAD/ZHub-V1-Print.3mf <br>
This has all the case parts you need (top and bottom)

#### 4. Assembly
Once the case has finished printing, place the assembled PCB into said case, then get the lid and slide it into the grooves of the bottom half of the case to close it.

#### 5. Profit
Plug a USB-C to C cable into the upstream port of the hub (the one not next to any other ports), and plug the other end of that cable into your computer. Then plug whatever USB devices into the downstream ports and...

Enjoy your ZHub!

## Renders
![Top](IMG/ZHub-V1-Top.png)
![Front](IMG/ZHub-V1-Front.png)
![Angled](IMG/ZHub-V1-Angled.png)

## Designing

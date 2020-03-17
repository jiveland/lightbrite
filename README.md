# Light-Brite
In the process of building an interactive Light-Brite as fun project.

*The idea is to use 1/2'' acrylic rods for the pieces

*Power LEDs for illumination. 

![Work in Progress](https://github.com/jiveland/lightbrite/blob/master/images/IMG_3184.jpg)

# Driver:

The first version of the Light-Brite will be a 8x8 LED matrix. 

Based off the Maxium 7219 8-digit LED driver:
[Maxium 7219 Driver](https://datasheets.maximintegrated.com/en/ds/MAX7219-MAX7221.pdf)

Utilizing a Raspberry PI 3 for control:
[Control Programs](https://max7219.readthedocs.io/en/0.2.3/)

A low power LED matrix HAT is available for the PI:
[Low power Pi HAT](https://www.amazon.com/HiLetgo-MAX7219-control-Display-Arduino/dp/B00LSG54O2/ref=sr_1_8?crid=5A6FXIFY03TO&keywords=max7219+dot+matrix+module&qid=1584419672&sprefix=max7219+d%2Caps%2C217&sr=8-8)

# Circuirt:
To step up the power of the MAX 7219 applications notes are provided:
[Application Notes MAX 7219](https://www.maximintegrated.com/en/design/technical-documents/app-notes/1/1196.html)

![Circuit Diagram](https://github.com/jiveland/lightbrite/blob/master/images/circuit.png)

[n-MOSFET RFP30N06LE](https://www.sparkfun.com/datasheets/Components/General/RFP30N06LE.pdf)
[p-MOSFET FQP27P06](https://www.sparkfun.com/datasheets/Components/General/FQP27P06.pdf)

20 Ohm resistor used to limit the current for each LED. 

# Light-Brite Hardware:

 Acrylic rods
[Acrylic Rods From TAP Plastics](https://www.tapplastics.com/product/plastics/plastic_rods_tubes_shapes/colored_acrylic_rod/148/425?msclkid=5591d8ba1b881346f1aa86d903e4da27&utm_source=bing&utm_medium=cpc&utm_campaign=%5BTDM%5D%20Shopping%20Tier%202&utm_term=4576717153513326&utm_content=20)

LEDs
LEDs on star boards are available in variety of prices depending on the quality and efficiency desired.
[LEDs on Star Boards](https://www.amazon.com/gp/product/B01J3FTU9E/ref=pe_2640190_232748420_pd_te_o_gc_ti?_encoding=UTF8&pd_rd_i=B01J3FTU9E&pd_rd_r=0SVYSHXQYPD9D8YWVHE5&pd_rd_w=nOkku&pd_rd_wg=bNmCQ&pf_rd_p=7c4712d4-5c4a-4b6f-b768-0b1fefc8544e&pf_rd_r=0SVYSHXQYPD9D8YWVHE5)


Heatsink

LEDs are conneced to a aluminum plate by thermal paste and glue. 

![LEDs on Heatsink](https://github.com/jiveland/lightbrite/blob/master/images/IMG_3191.JPG)



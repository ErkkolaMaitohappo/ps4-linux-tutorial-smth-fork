# This section will cover how to permanently install install using a internal modchip

## Credit: https://neburone10.github.io/ Rubén Ríos.


## Requirements:

- Basic soldering skills

- Soldering iron

- Solder

- Wire (Its recommended flexible stranded wire, here is used 0.75mm diameter including plastic insulation)

- Thermal tape to insulate the wires and chip to avoid shorts

- LuckFox Pico (bigger model can be used allowing integration in the space found)

- (Optional)MicroSD card of 8GB or higher

- Video tutorial [here](https://www.youtube.com/watch?v=OKjHICa40To&t=4s&pp=ygUbbW9kZGVkIHdhcmVmYXJlIHBzNCBtb2RjaGlw) by MODDED_WAREFARE. His tutorial is a bit different though.

For the board configuration, refer to the repository: https://github.com/0x1iii1ii/PPPwn-Luckfox. Note that when using this board, ethernet pins 4, 5, 7, and 8 need to be connected to GND for the router to recognize it, as seen in issue https://github.com/0x1iii1ii/PPPwn-Luckfox/issues/7

Regarding the ethernet connection, the creator apologizes for not being able to maintain the color coding in the photos, He didn't have enough cables. For the PPPoE connection used by the PPPwn exploit, only 10/100 ethernet is needed, so 4 wires are sufficient. This diagram shows the pins we need

<img src="/ethernet.png" width="75%">

As you can see, only TxD+, TxD-, RxD+, and RxD- are needed, and these should be connected to the LuckFox board on pins TxP, TxN, RxP, and RxN respectively from the following diagram.

<img src="/luckfox.jpg" width="75%">

For power, although the board can be powered via USB-C, it is also possible to do so via the VBUS and GND pins, corresponding to numbers 40 and 38 in the previous diagram.

With the connections clarified, the only thing left is how to route the cables so they don't interfere with the metal plates or plastic covers.

> [!NOTE]
> These images are taken from the internet, ignore the condition of the motherboard, the important thing is what is marked in each case with the red circles.

<img src="/f-board.jpeg" width="75%">

- **Side A(Image above)**

<img src="/b-board.jpeg" width="75%">

- **Side B(Image above)**

On side A, we have the ethernet connections, following the diagram shown earlier it would look like this:

> [!NOTE]
> These pictures we're taken from his own console

<img src="/ethernet_soldered.jpg" width="75%">

The wires are secured in this area with hot glue so they wouldn't move and thus not interfere with the metal plate above the motherboard.

<img src="/ethernet_glue.jpg" width="75%">

- All that's left is to get power for the LuckFox chip. We will take this from the rear USB marked in the red circle on side B of the motherboard. The connections would look like this:

<img src="/usb_wires.jpg" width="75%">

- To properly place the wires, we need to pass them under the metal plate as indicated in this diagram:

<img src="/scheme.jpeg" width="75%">

- The red arrow indicates where the wires enter the rear of the metal plate, the green lines indicate where the wires are hidden under the metal plate.

- This is the real image of how it looked in his console:

<img src="/result1.jpg" width="75%">

- At the back, the wires pass close to the edge of the power supply bay as seen in this image:

<img src="/power_wires.jpg" width="75%">

- The wires pass next to the hard drive tray as shown below:

<img src="/result2.jpg" width="75%">


- In this image, you can see the connections closer to the LuckFox board and also the position where it will be located:

<img src="/result3.jpg" width="75%">

- I also covered the board and its connections with thermal tape to avoid any unwanted contact that could cause a short circuit:

<img src="/result4.jpg" width="75%">

- Finally, the final installation would look like this with the top metal plate already in place.

<img src="/result5.jpg" width="75%">

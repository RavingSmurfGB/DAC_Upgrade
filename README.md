# DAC_Upgrade
Upgrading the XDUOO XD05 BAL with the discreet op-amp SS2590


## Contents
* [Justification](#Justification)
* [Discreet Op-Amps](#Discreet-Op-Amps)
* [Testing](#Testing)
* [Break out Board](Break-out-Board)
* [Enclosure](Enclosure)
* [Progress](#Progress)

## Justification
This project comes from my passion to find my perfect audio setup, the XDUOO XD05 BAL is a great DAC/Headphone Amp combo but lacks a clarity, layering and punch; among other things with the stock op-amps installed.
I have currently tested the following discreet op-amps
* [Sparkos Labs SS3602](https://sparkoslabs.com/product/dual-discrete-op-amp-ss3602/)
* [MUZG Audio Efficient JFET operational amplifier](https://muzgaudio.com/en/produkt/efficient-jfet-operational-amplifier/)
* [Sparkos Labs SS2590](https://sparkoslabs.com/product/pro-discrete-op-amp-ss2590/)


## Discreet Op-Amps

Discreet op-amps come with a DIP-8/ 8 Pin IC Socket attached on the bottom, however the higher end units tend to come with 6 pinouts that require a breakoutboard to convert to the DIP-8.

Futhermore the amound of Discreet Op-Amps required varies by the amplifier that is used. A typical amplifier would require two Op-Amps, one for the left channel and one for the right channel allowing for stereo sound to be produced.

![alt text](https://github.com/RavingSmurfGB/DAC_Upgrade/blob/main/images/unbalanced_amplification.png "Logo Title Text 1")

However a balanced amplifier works slightly differently, it sends two left channel signals and two right channel signals, each with either a positive or negative polarity. This is in a attempt to reduce noise and also increases the power which the amplifier can send to the listening device (Headphones, IEMs etc..) 
In such a implementation four Op-Amps are required.

![alt text](https://github.com/RavingSmurfGB/DAC_Upgrade/blob/main/images/balanced_amplification.png "Logo Title Text 1")

## Testing

The [breakout board](https://sparkoslabs.com/pro-discrete-op-amp/pro-to-dual-op-amp-adapter/) that Sparkos Labs supplies required soldering, furthermore the XDUOO XD05 BAL DIP 8 sockets are very close together.

![alt text](https://github.com/RavingSmurfGB/DAC_Upgrade/blob/main/images/dac.jpg "Logo Title Text 1")

Which means that a setup such as the one below is a common sight.

![alt text](https://github.com/RavingSmurfGB/DAC_Upgrade/blob/main/images/DAC%20with%20ss2590.jpg "Logo Title Text 1")

Where, extenders are used to allow the Op-Amps to run side by side, dodgy soldering which is prone to breaking and exposed PCBs which add up to a extremely delicate setup. Over time this will break and potentially dammage other components on the board.

## Break out Board

The [breakout board](https://sparkoslabs.com/pro-discrete-op-amp/pro-to-dual-op-amp-adapter/) board as mentioned converts the Dip-8 to what is commonly refered to as the pro style connector, the traces are fairly easy to follow as only a single layer of the PCB is used.

![alt text](https://github.com/RavingSmurfGB/DAC_Upgrade/blob/main/images/breakout.jpg "Logo Title Text 1")

By tracing this the following wiring diagaram can be made.

![alt text](https://github.com/RavingSmurfGB/DAC_Upgrade/blob/main/images/Sparkos%20breakout%20board%20diagram.png "Logo Title Text 1")

## Enclosure


## Progress

I am currently experimenting with replacing the break out board with cables.

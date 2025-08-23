# Apple 2 & 2e slot extender
# I will start off by saying that this is my first time posting a GitHub project and also the first time I have had a PCB fabricated commercially.
## Why do I want an Apple 2 or 2e slot extender?
### Its very tight and dark to probe a card inside the case of a Vintage Apple 2e computer, especially as there are a lot of bare live parts that can be contacted or shorted inside the case and on the Apple mother board.
Thus getting the card under test outside the case is a must for keeping my Apple well and running into the next decade.
Apple Card extenders are hard to source at the moment in the year 2025, so I decided to have a go at making my own.

I have used Kicad 9 to design the passive circuit and produce the PCB.

Not all of the design is my work as I asked contributor markdev if I could use one of his card edge footprints. And you can see his very kind reply agreeing to my use of his hard work.

*Hey there, yes that would be OK. The footprint is in this file https://github.com/markadev/AppleII-VGA/blob/main/AppleVGA/AppleVGA.pretty/AppleIIBus_Edge.kicad_mod which you can copy into your own project.
I also have another footprint in this library: https://github.com/markadev/KiCad-AppleII HOWEVER it contains some small size adjustments from the one used in this project and I never got around to creating a board to test it. So it's a bit more of a risk to use.*
 
My first PCB has worked but it seems that I have used the footprint that required some adjustment. 

### It’ s pictured below and was fabricated by PCBWAY directly from the Kicad project.
![Example Image](https://github.com/MrCrusty/APPLE-SLOT-EXTENDER/blob/main/jpg/IMG_2057.JPG)

The center slots are to allow simple seperation with a hacksaw so that the two halves can then be joined with a 50 way ribbon cable.
![Example Image](https://github.com/MrCrusty/APPLE-SLOT-EXTENDER/blob/main/jpg/IMG_2053.JPG)

As stated the card edge is not quite as snug in the Apple slot as it should be so a Version 2 was designed with the card edge suitably adjusted to fit the Apple slot size snugly.
I had during the above production of Version 1 shown the 3D design to the subscribers at APPLEFRITTER.com and asked for any improvements that might be made to Version 1. I had two answers 

The first was to suggest the use of Electroless Nickel Immersion Gold (ENIG) instead of tin.

## Version 2 nearly stalled at this point as it would seem that I must have had a first time deal from PCBWAY. The cost of the PCB had increased three times over Version 1 and the postage had jumped to the highest rate with no other options, if I was to request ENIG my wife would have have had me on bread and water for a month.

I decided to have a trawl on the web and see if other companies offered better deals 
## AISLER has come to my rescue offering a resonable PCB production cost downloaded direct from my Kicad project with resonable postage rates from Germany to the UK. and ENIG was 3 Euro more than tin. Version 2 arrived exactly on the day that they advised and emails during the production run key me informed of progress. 
## Version 2 meets the card edge requirements I expected and is nice and snug fit in the card socket.

## I said there was a second suggestion which was to have a silkscreen with names of the contacts related to the extension slot, this request arrived just after Version 2 had been sent for production. 
## A Version 3 has been designed with the new silk screen and components adjusted to allow the the extended size of the silk screen, its not been sent for production but uses exactly the same edge connector as Version 2.

## I will update this readme as things transpire. 

# please be aware you can plug a card in back to front with terrible results to the card and the Apple computer so do take care when using the extended. 
# LIKE ALL MY PROJECTS ITS FREE TO USE AND ABUSE, BUT I DO NOT TAKE RESPONSIBILITY THAT YOU APPLE COMPUTER WILL LIKE OR BE ABLE TO USE THIS EXTENDER. MINE IS HAPPY WITH IT YOURS MAY NOT BE> 


















































































































































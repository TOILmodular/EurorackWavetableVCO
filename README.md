# Wavetable VCO
This is a Eurorack DIY project for a Wavetable VCO based on the ElectricDruid VCDO chip.
The chip is available at the [ElectricDruid](https://electricdruid.net) web shop.

I built the module mainly by utilizing the example schematics in the documentation for the chip. It contains a main and a sub oscillator output with 16 and 8 different waveforms, respectively. Most of the controls can be voltage controlled.

There is a [YouTube video](https://www.youtube.com/watch?v=ECpdo4HfqLg) available, showing the built and sound demonstrations of the module.

## Module Built and PCBs
If you want to build the module yourself, I uploaded the schematics, the BOM and the Gerber files for the PCB.

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created a version with footprints for those components.
Choose the one you need.

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.
I cannot guarantee, if this set of zipped Gerber files works also for other providers, like e.g. PCBWay. I have not tried that. But I saw online, that others did it.

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, refering to the component layout in the Gerber files. The layout is the same for both versions.

## Additional Information about specific Components
If you want to use the Gerber files for having PCB manufactured, please note the following information about components used.

- The module is mainly using THT components.There is only a number of SMD 0.1uF capacitors with the package size 1608.
- In order to save space, I am always using small size resistors, about 3mm length, which are about half the size of usually used resistors.

![VCDO](https://user-images.githubusercontent.com/97026614/178847755-9d0dc88d-2205-430e-aa33-a740faf9cba9.jpeg)

![VCDOFront](https://user-images.githubusercontent.com/97026614/178847775-7df4ade8-d466-4815-8090-4832dd2294d2.jpeg)

![VCDOSide](https://user-images.githubusercontent.com/97026614/178847815-b77609da-177b-477f-a837-d2c4b9f82f55.jpeg)

![VCDOBackSide](https://user-images.githubusercontent.com/97026614/178847851-f70a8c87-64f7-4694-aab3-ad0cef2818e0.jpeg)

![VCDOParts](https://user-images.githubusercontent.com/97026614/178847884-4b90a7c4-8035-4871-8a66-16a76e534c1c.jpeg)

![Capture1](https://user-images.githubusercontent.com/97026614/178255748-f92e6745-74c5-4cc2-8fe0-ac3176a4bce5.JPG)

![Capture2](https://user-images.githubusercontent.com/97026614/178255767-555cdae8-e0b0-4951-b829-64ac7e5ad75a.JPG)

![Capture3](https://user-images.githubusercontent.com/97026614/178255788-55a63420-045a-48f2-b408-8caec6e6f57c.JPG)

![Capture4](https://user-images.githubusercontent.com/97026614/178255803-e562d9ed-1a04-4268-a389-710fd0f4fc0b.JPG)

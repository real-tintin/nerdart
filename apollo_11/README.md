# Apollo-11
This work illustrates the machine code of the Luminary 1A (version 099), the Lunar Module's (LM) Apollo Guidance Computer (AGC) for Apollo 11. Two different variants exist:
* **apollo_11_bin**: First 512 bytes of the binary code for Luminary 1A (version 099), the Lunar Module's (LM) Apollo Guidance Computer (AGC) for Apollo 11.
* **apollo_11_asm**: Page 800-801 of the source code for Luminary 1A (version 099), the Lunar Module's (LM) Apollo Guidance Computer (AGC) for Apollo 11.

## The binary code
The binary code is a part of the compiled (using the Docker image) [Virtual Apollo Guidance Computer](https://github.com/virtualagc/virtualagc), where the generated binary has been dumped to binary format using `xxd`.

## The assembler code
The original assembler code for the Apollo 11 guidance computer has been transcribed (about 3000 pages!) and is available on Github, https://github.com/chrislgarry/Apollo-11.

## The Futura font
The Futura font is the first font to land on the lunar surface, as it was used to engrave a plaque: *HERE MEN FROM THE PLANET EARTH FIRST SET FOOT UPON THE MOON JULY 1969, A. D. WE CAME IN PEACE FOR ALL MANKIND* - signed by the astronauts (Neil A. Armstrong, Michael Collins, Edwin E. Aldrin, Jr.) and president Richard Nixon. The plaque was mounted on the lunar landing vehicle which was left behind on the moon, see [How Apollo 11 launched Futura to the moon](https://www.typeroom.eu/article/how-apollo-11-launched-futura-moon) for further reading.

In this work the Futura font is used for the title and description.

## Specs of the AGC
* 2048 words of RAM. A "word" was 15 bits of data—therefore just under 2 bytes (16 bits) of data—and so the total RAM was just 3840 bytes.
* 36,864 words of read-only memory, equivalent to 69,120 bytes.
* Maximum of about 85,000 CPU instructions executed per second.
* Dimensions: 24"×12.5"×6".
* Weight: 70.1 pounds.
* Power supply: 2.5A of current at 28V DC

Astronauts communicated with the AGC using a numeric display and keyboard called the DSKY (for "display and keyboard", pronounced "DIS-kee").
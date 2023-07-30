# Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic

Decoders are one of the trivial yet essential circuits in the realm of digital electronics. These facilitates reduction in number of interconnects by a factor of log2N, where N is independent address locations. Huge blocks of SRAM memory having various banks of SRAM cell, have multiple stages of decoder that are hierarchically linked. The MSB (Most significant bits) is decoded(pre-decoded) at the first stage, leading to selection of array that is to be accessed by providing enable signals for the subsequent decoder stages that further helps in enabling the world lines. These word lines turn on the access transistors (in the case of SRAM block) or any other element connected to it when required input is given. 


This repo explicitly depicts the difference between dynamic and static CMOS logic and application of the same by developing a decoders and analyzing theri performance.
The schematic files are not only designed but theri corresponding Layouts ae generated to examine the effects of parasitic capacitance and resistances in order to obtain virtually perfect values of delay, area consumption and power consumption.



Various tools used were.

Schematics            - Cadence Virtuoso Schematic XL

Layout                - Layout XL

Simulation            - ADE L

Technology            - GPDK180

Physical Verification - ASSURA

RC Extraction         - Quantus RC


All the files included are final.

I have also attached the pdf of the IEEE published paper of the same.
C. Srinivas, B. G S, C. S P, K. E. A and P. Vimala, "Comparative Analysis of Decoders using Static & Dynamic CMOS Logic," 2023 International Conference on Advances in Electronics, Communication, Computing and Intelligent Information Systems (ICAECIS), Bangalore, India, 2023, pp. 368-372, doi: 10.1109/ICAECIS58353.2023.10170322.

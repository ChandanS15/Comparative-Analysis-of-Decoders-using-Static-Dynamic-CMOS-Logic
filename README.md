# Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic

Decoders are one of the trivial yet essential circuits in the realm of digital electronics. These facilitates reduction in number of interconnects by a factor of log2N, where N is independent address locations. Huge blocks of SRAM memory having various banks of SRAM cell, have multiple stages of decoder that are hierarchically linked. The MSB (Most significant bits) is decoded(pre-decoded) at the first stage, leading to selection of array that is to be accessed by providing enable signals for the subsequent decoder stages that further helps in enabling the world lines. These word lines turn on the access transistors (in the case of SRAM block) or any other element connected to it when required input is given. 


This repo explicitly depicts the difference between dynamic and static CMOS logic and application of the same by developing a decoders and analyzing theri performance.
The schematic files are not only designed but theri corresponding Layouts ae generated to examine the effects of parasitic capacitance and resistances in order to obtain virtually perfect values of delay, area consumption and power consumption.

Static CMOS Logic![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/d1f19020-4ec7-4ab4-90ed-4624ba63eb1f)

The Static CMOS logic are -

Robust against Noise making it trouble free to automate

Relatively consume less power

One of the main disadvantage is, in high-fan-in circuits it turns out to be expensive in terms of are and performance

Number of Transistor required  = 2*N



![static jpeg](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/e3698d02-b288-4c21-a75f-3a07d7063a3e)

Dynamic CMOS Logic![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/2c2c36a3-bc33-43dd-9e5d-00a4fe8a7379)

The dynamic CMOS logic are - 

Simple and fast but at the expense of

       Reduced Noise Margin
       
       Static Power Dissipation
       
       Number of Transistor = N+1 (for pseudo-NMOS)
              
![dynamic jpeg](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/2e0bda8e-9552-4be7-9bc8-fe7b503926f9)  

Various types under this category are Ratioed logic, pseudo-NMOS, Domino logic, pass-transistor, DCVSL(Differential Cascode Voltage Switch Logic).

In our project we are extensively focusing on pseudo-NMOS logic

The common advantages and disadvantages are

Substantial reduction in gate complexity.

But at the expense of static power consumption, asymmetrical response and reduced Noise Margin.


pseudo-NMOS Logic![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/0cc6e3ae-c15d-47e2-a13b-9e160c49c64c)

Conventional/static logic is  made of both PUN and PDN network, in contrast pseudo-NMOS comprises of only PDN network with a single PMOS transistor.
The single PMOS is always grounded leading the output F to be always high(VDD). Consequently, the Nominal output high voltage VOH = VDD.
Nominal output low voltage is no equal to 0 as in conventional CMOS due to the fight between PDN and the grounded PMOS and acting as load device.
![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/1cd27f5b-d546-41c9-8cfa-00cfa1a32f86)


























Various tools used were.

1. Schematics            - Cadence Virtuoso Schematic XL

2. Layout                - Layout XL

3. Simulation            - ADE L

4. Physical Verification - ASSURA

5. RC Extraction         - Quantus RC

6. Technology            - GPDK180


All the files included are final.

I have also attached the pdf of the IEEE published paper of the same.

C. Srinivas, B. G S, C. S P, K. E. A and P. Vimala, "Comparative Analysis of Decoders using Static & Dynamic CMOS Logic," 2023 International Conference on Advances in Electronics, Communication, Computing and Intelligent Information Systems (ICAECIS), Bangalore, India, 2023, pp. 368-372, doi: 10.1109/ICAECIS58353.2023.10170322.

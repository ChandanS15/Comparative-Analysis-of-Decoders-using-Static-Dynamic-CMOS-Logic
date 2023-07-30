# Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic

Decoders are one of the trivial yet essential circuits in the realm of digital electronics. These facilitates reduction in number of interconnects by a factor of log2N, where N is independent address locations. Huge blocks of SRAM memory having various banks of SRAM cell, have multiple stages of decoder that are hierarchically linked. The MSB (Most significant bits) is decoded(pre-decoded) at the first stage, leading to selection of array that is to be accessed by providing enable signals for the subsequent decoder stages that further helps in enabling the world lines. These word lines turn on the access transistors (in the case of SRAM block) or any other element connected to it when required input is given. 


This repo explicitly depicts the difference between dynamic and static CMOS logic and application of the same by developing a decoders and analyzing theri performance.
The schematic files are not only designed but theri corresponding Layouts ae generated to examine the effects of parasitic capacitance and resistances in order to obtain virtually perfect values of delay, area consumption and power consumption.

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/91cf14ff-6104-4ace-b17e-c49fe5ee4f09)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/ba36a135-4cc3-4212-b222-9150ebbf03d2)


![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/63836c4f-a298-4086-9a2b-4f8ed9ad0c29)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/2995a5d2-fdf7-4afe-bafa-449695847421)


![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/7177100c-dd70-44b1-9c81-60b91ae30038)

![static jpeg](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/f9a9a147-990c-4a73-b7b8-88ba076b5a88)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/a4f17e66-4fc7-44ca-bcb8-14e3d02529e4)


![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/46e94312-79ad-4ec0-8c4d-f8147b707738)

![dynamic jpeg](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/3371e266-4c82-4027-9d98-d9cd6e066b43)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/4371f630-ac31-4997-977e-9970c478cc64)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/be36e3ad-5483-4b06-92f5-eb5e71fe5cb2)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/274dd3d0-657b-43cb-8425-ca1febf28e7d)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/cf8e14ec-c421-4912-8030-594371ce24aa)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/0a8495e1-3b36-43d3-9153-7d57b9958da6)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/98ccbf5f-22ba-487e-ac9b-319eb491f3dd)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/f177b003-4b89-497e-b10f-eb3a8f3c2f70)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/46692b68-2ea7-4f49-a663-7c5e1aa88b32)

![image](https://github.com/ChandanS15/Comparative-Analysis-of-Decoders-using-Static-Dynamic-CMOS-Logic/assets/82103081/7133d622-bb46-4e1f-99b9-472b0cb6ba76)











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

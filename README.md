# Discrete-OPAMP

The goal of this project is designing a simple Operational Amplifier (OPAMP). The OPAMPs
that you use in the labs are very complex, they consist of multiple transistors, have advanced
biasing circuits, are low noise, are frequency compensated for stability, have output stages to
deliver descent amount of current to a load. In this project you will design an OPAMP with selfbiasing, differential input and single ended output, and an output stage.
EEE313 Fall 2023-2024 26.11.2023
The fundamental specifications are
• Dual power supplies (+/- VDD) no more than +/-10V.
• Power consumption should be less than 200mW, i.e., <10mA total current per supply
• AV=vout/(v+-v-)>500.
• An output stage that can drive RL<1kΩ. The gain should not drop when RL is connected.
• Resistors are allowed but you can get much higher gains with transistors.
• The circuit should generate its own biasing, if you need different voltages you should
generate them from the supplies.
• Frequency compensation is not required, but you can implement it if you want to.
Note that these are the minimum requirements, if you can do better it is appreciated.
Your circuit will be tested as shown in Figure 1, + terminal will be grounded, R1=R2=5kΩ, and
Vout =-Vin should be observed.
![download](https://github.com/MelihKutayYagdereli/Discrete-OPAMP/assets/122688232/03cb7090-2124-4167-b67c-23399f6fc566)
![download (1)](https://github.com/MelihKutayYagdereli/Discrete-OPAMP/assets/122688232/4b4ae6b2-3969-48c2-9c18-e218d418f3d6)

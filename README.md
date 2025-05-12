# Digital-Tube-Decoder
a specific module that converts 8-bit signed binary inputs into Binary-Coded Decimal (BCD) format and displays the result on The FPGA's 4-digit 7-segment display (Digital Tube).

# How to use 
1- include all (.v) files to your project <br>
2- instanitate "Top_module.v" to your ALU top module where:<br>
    - Output of the ALU is connected to input (A)<br>
    - The MSB of the selection line is connectd to the input (sel)<br>
    - system clock should be connected to the input (clk)<br>
   <div align="center">
  <img src="https://github.com/abdallah-zein/Digital-Tube-Decoder/blob/main/Images/block-diagram.jpg" alt=" System Block Diagram">
</div>
<br>

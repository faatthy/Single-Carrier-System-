## Single carrier System

## System Discribtion 
![image](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/4d69093b-b908-4926-948f-0d193f137473)
1.1 The Mapper  
The first block in the communication system under consideration is the mapper. The 
mapper takes the I/P data bits and produces the symbols to be transmitted on the channel. 
The modulation schemes under consideration are the BPSK, QPSK, 8PSK, BFSK and 
16QAM systems. Figure 2 shows the constellations. 
1.2 The channel 
The channel is an AWGN channel. In this model, the channel just adds noise to the 
transmitted signal. In MATLAB, the command “randn” should be used to generate the 
AWGN.  
1.3 The Demapper 
The simple demapper in the model under consideration will take the output of the channel 
and decide on the symbol transmitted. The output bit stream of the receiver is compared to 
the input bit stream and the BER is calculated.

![image](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/984b1640-8cea-4edf-b982-8a21191fcbb5)


## Generate constellations 
![3](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/2637c60f-9ef2-4b7a-88d3-9ff749a5202e)
![4](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/9b4e9918-a4ac-4a09-b230-e5b8315ba654)

## BPSK Vs QPSK Vs 8PSK Vs 16QAM BER 
![image](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/aeda56e6-b2a4-4d19-9502-2fef6df671ac)
 presents a comparison among four different constellations. Both BPSK and QPSK demonstrate 
the expected similarity in Bit Error Rate (BER), confirming that QPSK is more efficient due to its narrower 
bandwidth compared to BPSK. However, 8PSK exhibits a higher bit error rate than QPSK. This is because, 
beyond QPSK, increasing the number of bits improves bandwidth efficiency at the expense of increasing 
the BER. 
16QAM, although having the largest BER, demonstrates the highest bandwidth efficiency. It is also the 
most effective scheme for transmitting a large number of bits, as its constellation optimally utilizes 
space, resulting in lower energy consumption compared to other modulation schemes when 
transmitting the same large number of bits.

## Gray Vs Non Gray QPSK BER
![image](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/61e215f2-72f8-4879-9c2b-4bc61921d1b3)
Gray QPSK ensures that adjacent symbols differ by only one bit, leading to smoother transitions 
between symbols and lower Bit Error Rate (BER). In contrast, Non-Gray QPSK allows symbols to differ by 
more than one bit, resulting in larger transitions between adjacent symbols and consequently higher 
BER

## BPSK 
![image](https://github.com/faatthy/Single-Carrier-System-/assets/110846097/7fccbf17-f0cf-4392-aeba-2f3cd8742329)

<table border="1">
  <tr>
    <th>Signal Name</th>
    <th>Width (bits)</th>
  </tr>
  <tr>
    <td>A</td>
    <td>parameterized</td>
  </tr>
  <tr>
    <td>B</td>
    <td>parameterized</td>
  </tr>
  <tr>
    <td>ALU_FUNC</td>
    <td></td>
  </tr>
  <tr>
    <td>&nbsp;</td>
    <td>CLK</td>
    <td>4</td>
  </tr>
  <tr>
    <td>&nbsp;</td>
    <td></td>
    <td>1</td>
  </tr>
  <tr>
    <td>Arith_OUT</td>
    <td>RST</td>
    <td>parameterized</td>
  </tr>
  <tr>
    <td>&nbsp;</td>
    <td></td>
    <td>1</td>
  </tr>
  <tr>
    <td>Carry_OUT</td>
    <td></td>
    <td>1</td>
  </tr>
  <tr>
    <td>Arith_Flag</td>
    <td></td>
    <td>1</td>
  </tr>
  <tr>
    <td>Logic_OUT</td>
    <td>parameterized</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Logic_Flag</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>CMP_OUT</td>
    <td>parameterized</td>
    <td>1</td>
  </tr>
  <tr>
    <td>CMP_Flag</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>SHIFT_OUT</td>
    <td>parameterized</td>
    <td>1</td>
  </tr>
  <tr>
    <td>SHIFT_Flag</td>
    <td></td>
    <td></td>
  </tr>
</table>

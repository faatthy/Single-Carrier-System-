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


# QCN3-Board

PCB board for the hybrid coupler QCN3

<img src="./img/qcn3.jpg" alt="QCN3" width="200"/>

## Warning, maximum transmission power (datasheet) is 15W. But it's better to not go over 5-10W

<p float="left">
	<img src="./img/board.png" alt="QCN3 Board" width="300"/>
	<img src="./img/FinishedBoard.jpg" alt="QCN3 Final board" width="300"/>
</p>



It allows to do the right hand circular polarization without having to deal with coax cables.  

------

Nano VNA results (with 2 50 ohms loads at the outputs)

<p float="left">
	<img src="./img/BoardTesting.jpg" alt="QCN3 Board test setup" width="300"/>
	<img src="./img/NanoVna.jpg" alt="QCN3 Board results with nanovna" width="300"/>
</p>

------

Connect the 90º pin to the right of the 0º pin to allow **right hand circular polarization**.  
Make sure that the 2 output wires have the same length!

<img src="./img/Connection.png" alt="Board pinout" width="400"/>

------

You can order it at jlcpcb or other companies using the gerber zip file in this repository.  
Make sure to order it with 1.6 board width  

------

BOM:

- 1x QCN-3
- 2x SMD resistor 2512 100Ω 2W
- 3x SMA connectors for PCB with 1.6mm spacing


<p float="left">
	<img src="./img/qcn3.jpg" alt="QCN3" width="200"/>
	<img src="./img/resistor.png" alt="SMD resistor" width="300"/>
	<img src="./img/sma.png" alt="SMA connectors" width="300"/>
</p>

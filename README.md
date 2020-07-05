# III_final
Course assignment: Introduction to Industrial Informatics

To develop a knowledge driven, monitoring and supervisory control system of the
FASTory Line using knowledge base (OWL) to make operational decisions for carrying
out the required tasks. 
System Capabilities: The aim of the complete system building is to enable the
control of the FASTory system through the web interface so it can work as the basic
component of large cyber physical system in big automation environment. The
system is aimed to work using a web interface and execute the tasks
(pallets moving and assembling) automatically once commanded and able to
respond in sequence of tasks to accomplish a complicated task.

## 2. System Description:
The FASTory line includes the main components of a production line; robots,
transportation system, tools, end effectors, raw material, working stations, loading
and unloading stations and a buffer station.
The system consists of the following:
● Conveyor- Each workstation in the FASTory line consist of two conveyors;
main and bypass. The main conveyor is used if the pallet requires service
from the work cell. Meanwhile, the bypass is used if the work cell is in busy
state (another pallet(s) [max 2 pallets] are in the cell) to bypass the pallet to
the next work cell. Both Conveyors (Main and Bypass) are controlled by a
single RTU.
● Work Stations-
In FASTory there are 12 work stations in total, each work station contains one
conveyor and one robot, for each conveyor there are several zones and each
zone has one presence sensor to detect the presence of the pallet, one
stopper to stop the pallet in the zone and each entrance zone for each work
station has an RFID reader for pallet recognition.
There are 10 identical work stations which draw the main parts of three
models of a mobile phone (WS 2-6 and 8-12). The remaining 2 workstations
are WS1 used for loading raw material and unloading the product, WS7 is
used for loading and unloading the pallet.
● Robots- The factory line uses SONY SCARA robots for production. Each robot
is represented as an RTU in the line.
● RTUs- The FASTory is equipped with INICO S1000 Remote Terminal Units
(RTUs). There are RTUs with unique IP address for each robot and conveyor in
a work cell.

The system was capable of carrying out required task. The task include drawing different shapes of customizable mobile phone configurations once the order is created. The process is automated where the operation and control is executed with the stored knowledge of robotic work station in Knowledge Base (KB).

<image src = "img/Murata.PNG" alt = "murata sensor" width = 250> 
<image src = "img/Murata.PNG" alt = "murata sensor" width = 250> 
<image src = "img/Murata.PNG" alt = "murata sensor" width = 250> 
<image src = "img/Murata.PNG" alt = "murata sensor" width = 250> 
<image src = "img/Murata.PNG" alt = "murata sensor" width = 250> 


# SDORP: SDN based Opportunistic Routing for Asynchronous Wireless Sensor Networks
To simulate SDORP, a new platform with a graphical user interface that provides details of simulations runs with other important pieces of information is developed. The toolkit is developed using C# and WPF in .net 4.5.
Developed by Muhammad Umar Farooq Qaisar et al. (muhammad@mail.ustc.edu.cn). 
If you decided to use this simulator for academic issues, please support us by citing any of the following works:

[1] M. U. F. Qaisar, X. Wang, A. Hawbani, L. Zhao, A. Y. Al-Dubai and O. Busaileh, "SDORP: SDN based Opportunistic Routing for Asynchronous Wireless Sensor Networks," in IEEE Transactions on Mobile Computing, doi: 10.1109/TMC.2022.3158695.
Abstract: In wireless sensor networks (WSNs), it is inappropriate to use conventional unicast routing due to the broadcast storm problem and spatial diversity of communication-links. Opportunistic-Routing (OR) benefits the low duty-cycled WSNs by prioritizing the multiple candidates for each node instead of selecting one node as in conventional unicast-routing. OR reduces the sender waiting time, but it also suffers from the duplicate packets problem due to multiple candidates waking up simultaneously. The number of candidates should be restricted to counterbalance between the sender waiting time and duplicate packets. In this paper, software-defined networking (SDN) is adapted for the flexible management of WSNs by allowing decoupling of the control plane from the sensor nodes. This study presents SDN-based load-balanced opportunistic-routing for duty-cycled WSNs that addresses two parts. First, the candidates are computed and controlled in the control plane. Second, the metric used to prioritize the candidates considers the average of three distributions, transmission distance distribution, expected number of hops distribution and residual energy distribution so that more traffic is guided through the nodes with higher priority. Simulation results show that our proposed protocol significantly improve network lifetime, routing efficiency, energy consumption, sender waiting time, and duplicate packets as compared with the benchmarks.
URL: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9733217&isnumber=4358975

[2] A. Hawbani, X. Wang, L. Zhao, A. Al-Dubai, G. Min and O. Busaileh, "Novel Architecture and Heuristic Algorithms for Software-Defined Wireless Sensor Networks," in IEEE/ACM Transactions on Networking, vol. 28, no. 6, pp. 2809-2822, Dec. 2020, doi: 10.1109/TNET.2020.3020984.
Abstract: This article extends the promising software-defined networking technology to wireless sensor networks to achieve two goals: 1) reducing the information exchange between the control and data planes, and 2) counterbalancing between the sender's waiting-time and the duplicate packets. To this end and beyond the state-of-the-art, this work proposes an SDN-based architecture, namely MINI-SDN, that separates the control and data planes. Moreover, based on MINI-SDN, we propose MINI-FLOW, a communication protocol that orchestrates the computation of flows and data routing between the two planes. MINI-FLOW supports uplink, downlink and intra-link flows. Uplink flows are computed based on a heuristic function that combines four values, the hops to the sink, the Received Signal Strength (RSS), the direction towards the sink, and the remaining energy. As for the downlink flows, two heuristic algorithms are proposed, Optimized Reverse Downlink (ORD) and Location-based Downlink(LD). ORD employs the reverse direction of the uplink while LD instantiates the flows based on a heuristic function that combines three values, the distance to the end node, the remaining energy and RSS value. Intra-link flows employ a combination of uplink/downlink flows. The experimental results show that the proposed architecture and communication protocol perform and scale well with both network size and density, considering the joint problem of routing and load balancing.
URL: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9203970&isnumber=9295473

# Bugs
If any bugs are encountered during the execution of the toolkit, please restart toolkit, or you can download the new version of this toolkit. If there is any error occurs, the toolkit will shut down automatically.
# How to use the toolkit of simple testing
1) Open SDORP.exe or run the SDORP.sln project in the Toolkit folder. If the toolkit can’t run pleases refer to (http://staff.ustc.edu.cn/~anmande/miniflow/#_Installation_Problems).

2) Import the required network topology, from File-> Import Topology.

3) From the main menu, select Coverage->Random

4) To select the rate of sending packet, from the main menu Test-> Select one Source per time, and select the desired rate.

# How to use the toolkit for experiments and evaluation
1) Open SDORP.exe or run the SDORP.sln project in the Toolkit folder. If the toolkit can’t run pleases refer to (http://staff.ustc.edu.cn/~anmande/miniflow/#_Installation_Problems).

2) Import the required network topology, from File-> Import Topology.

3) Set the experiment settings, after clicking Experiment, and click Start.

4) After the scenario is run, results are obtained from Show Results -> Show Results

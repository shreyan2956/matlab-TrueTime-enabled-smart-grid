# matlab-TrueTime-enabled-smart-grid

This Simulink file models a **TrueTime-enabled smart grid** scenario, integrating real-time networked control with power system components. The visible components include TrueTime Send, Receive, and Network blocks, which simulate real-time communication and processing delays for evaluating control system performance under realistic networking conditions.

In this grid setup, electrical signals are generated and measured, then transmitted over a simulated network using the TrueTime protocol. The TrueTime Send block transmits measurement data (like voltages or switching signals) across the network to remote controllers or monitoring stations, while the TrueTime Receive block gathers responses or commands. The TrueTime Network block simulates network-induced effects (delays, packet drops) crucial for analyzing the performance and stability of cyber-physical power systems.

This configuration is particularly suited for investigating **smart grid applications**, such as distributed generation, remote monitoring, microgrid management, and advanced control algorithms (like load shedding, fault detection, or demand response), all under the influence of real-time network dynamics. The system’s modularity enables the modeling of various grid topologies, communication infrastructures, and real-time cyber-physical interactions essential in modern smart grids. 

However, the errors shown (“truetime not found”) indicate that the TrueTime library is either missing or not properly installed in your Simulink environment. For successful simulation, ensure TrueTime is installed and configured so all networked real-time blocks operate as intended.

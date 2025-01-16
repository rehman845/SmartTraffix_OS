# SmartTraffix_OS
SmartTraffix is a traffic management simulation system implemented in C++ with graphical visualization using SFML. It aims to optimize traffic flow at a four-way intersection by managing vehicles, traffic lights, and queues under predefined conditions and dynamic scenarios.

Key Features:
Traffic Light Control: Round-robin switching of traffic lights with prioritization for emergency vehicles.
Queue Management: Dual-lane roads with a capacity of 10 vehicles per lane, supporting vehicle queuing and emergency handling.
Vehicle Management: Handles regular, heavy, and emergency vehicles with predefined arrival rates and speed limits:
Regular: 60 km/h
Heavy: 40 km/h (restricted during peak hours)
Emergency: 80 km/h (always prioritized)
Dynamic Simulation: Real-time traffic visualization with vehicle movement, color-coded traffic lights, and on-screen analytics.
Deadlock Prevention: Implements Banker’s Algorithm to prevent traffic deadlocks.
Functional Highlights:
Vehicle Handling:
Simulates traffic flows for four directions (North, South, East, West).
Prioritizes emergency vehicles.
Traffic Light Scheduling:
Manages light cycles with equal timing by default and priority overrides for emergencies.
Tracks payment status, challan history, and overdue records.
User Portal:
Enables vehicle owners to view and pay challans securely.
Analytics:
Provides real-time stats for vehicle counts, challan statuses, and other metrics.
Technical Details:
Speed Adjustment: Vehicle speeds increase dynamically by 5 km/h every 5 seconds.
Graphical Representation:
Animated vehicle movement through intersections.
Visualized traffic light states and dynamic analytics.

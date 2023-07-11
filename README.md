# Traffic-Light-Controller
The provided code is an example of a Verilog module that implements a 4-way traffic light controller. It uses a finite state machine (FSM) to control the state transitions and timing of the traffic lights.
Module Declaration: The module is defined as traffic_controller and includes the input and output ports for the traffic lights.

Timescale Declaration: The timescale directive defines the time units for the simulation.

State Definitions: The define statements define constants for the different states of the traffic light controller.

Input/Output Declarations: The input and output ports of the module are declared.

Signal Declarations: Various wires and registers are declared to hold the current state, timer counts, and control signals for the traffic lights.

Timer Implementation: Four timers are implemented using registers and combinational logic. These timers control the timing of the traffic light transitions.

Traffic Lights State Machine: The main logic of the traffic light controller is implemented using an always block. It describes the state transitions and control signals for the traffic lights based on the current state and timers.

State Transitions: The state transitions are defined based on the current state, timer counts, and the input signal for blinking lights. Each state corresponds to a specific combination of traffic light signals.

Blinking State: The state S12 handles the blinking of yellow lights. It toggles the yellow lights based on a separate timer.

Default State: If none of the defined states match, the default state is set to S0.

The provided Verilog code demonstrates the basic structure and implementation of a 4-way traffic light controller. It can be further customized and extended based on specific requirements and desired timings for the traffic light transitions.

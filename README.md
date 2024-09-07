# PyLTSpice (with example)
As the name suggests, this repo will guide you to integrate LTSpice with python scripting. 
Whys it useful? Obviously LTSpice is an open-source free to use simulator used by academia all around the world. Its beginner friendly, and has  a wide variety of tools for modelling.
However, as the complexity of the circuit increases, and say that you want to have various parameters being altered and the result has to be computed at every instant; this is hence very cpu intensive; 
Having ways to perform the same task to various data points at once (parallel processing) is very helpful.
Thereby, having a platform to create, generate and modify netlists at runtime is more adviced due to flexibility and more control.
This is facilitated by this library. It was developed by NUNOBRUM and his team a couple of years ago. 


As for an example, Ill be implementing it to a nano-device, Magnetic Tunelling junction, which is used to solve a higher order differential (Quantum) equation.
I have generated the netlist in the required way(cant disclose due to NDA :p)  and the various parameters in the equation appear as the Voltage-Controlled-Current-Sources in the circuit.

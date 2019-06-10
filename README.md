# ShaggyDemiurge Finite State Machine

Yet another Finite State Machine for Godot 3.1, this time based on nodes and method names. 

You have a FSM node, children nodes (usually regular Node) are states, each state node has its own script (Built-in scripts are fine here). In that script you can define methods with predetermined names (names can be customized if needed for some reason) that determine, what happens on each tick while this state is active, which states you can transition to, and what happens when you leave current state to that specific state, what happens when you arrive at this state etc. etc.

More info in script

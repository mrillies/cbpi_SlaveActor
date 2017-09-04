# cbpi_SlaveActor
Adds an actor that is turned on if any of its masters is on.

Useful for groups of valves requiring a pump or for a master contactor for elements (if combined with a delay actor)

The slave actor will be on if:
- Any of the Actors 1-8 are on
- The SlaveActorControl Actor is switched on (manual control)

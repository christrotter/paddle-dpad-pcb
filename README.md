# paddle-inator
NOTE: Ordered pcbs on July 12, 2025, so this is untested at the moment.

A prototype pcb to mount ALPS SKRHACE010 switches on the back of the thumbcluster and use them as soft-action paddle-keys.  Uses an SK6805-EC15 led indicator and 12-pin 0.5mm pitch FFC connector - I'm trying to move away from single-wire soldering.

The application I'll be trying these out in is for 'curl your fingers inwards' paddle switches, but I needed a very soft touch due to fibromyalgia.

I've been using the SKRHACE010 5-way switches in my dpads and they are wonderful with enough leverage.  I prototyped using an old pcb with that switch and so far seems like this will work just fine.

![Cutaway](/images/cutaway.png)

# Usage example
The actual use case in-model might help to clarify the functionality.  There are three of these paddles just between the thumb keys and main keywell.

![Example1](/images/example-usage1.png)
![Example2](/images/example-usage2.png)


# Connector wiring details
- 3 GND pins, 1 5v pin
- 6 pins for the switch (_even though I only really use one_)
- DI & DO for led signal

# PCB details
- 14.2 x 23.9mm (_why? b/c I wasn't aiming for a specific dimension, just 'small as reasonable'_)
- 1mm radius corners

![Schematic](/images/schematic.png)
![PCB Layout](/images/pcb-layout.png)


# Cooperation Interface
This document focus on the interface.

## Interface
From the [wikipedia](https://en.wikipedia.org/wiki/Interface_(computing)), an inteface is a shared boundary across which two or more separate components of a computer system exchange information.
Usually we design the interface for **boundary** for exchange **information** between subsystems efficiently.

## How to design interface
The form of interface is highly bind to the division of the work. If the work is well decoupled, the interface will be quite easy to design.

Standard interface should contains the requirement and product of one system.
The requirements could be data format, precise co-variance matrix, or some spatial volumn. Otherwise, the output should contain those information.


The core philosophy of interface is not to design the interface, but define a clear boundary between subsystems, for  better communication and responsibility allocation. Then avoid the mismatch of systems.  
So if your tasks are too complicated to decouple and design a clear interface, just define it coarsely, and keep on communication.
It is highly recommended that maintaining an interface version repository.
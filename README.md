## Solution Explained

The system assumes that by the time an inbound item arrives at the pickup position it has been assigned a slot in one of the racks in the cell – so I assigned a slot in the normal way before it reaches a shuttle. You can additionally request items for picking out of the racks by pushing the item to the global list ItemsToPick.

Currently each shuttle will store and/or pick one item in one trip with a dedicated position for each. When doing both in a single trip, the order in which this happens will depend where along the level the slots are located. In the event that there are no remaining tasks but items still need to exit the cell, the shuttles at the front of the queue will be asked to circulate empty through the system, thereby allowing the outbound items to advance to the exit position. The number of shuttles in the system is a process flow variable.
</br></br>

## 3D Animation 

https://github.com/GoodbyeKittyy/Elevator-Service-Rack-Solution/assets/161730857/18ac2748-6ef2-409f-abf6-6052a11efac4

</br></br>

## Live Process Flowchart

https://github.com/GoodbyeKittyy/Elevator-Service-Rack-Solution/assets/161730857/740a00b4-0a8f-45bd-b894-ee8eec1e46e6


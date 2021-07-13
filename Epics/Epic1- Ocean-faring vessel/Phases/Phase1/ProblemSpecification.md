#CPU Problem Specification
##Summary of the problem:
We need a computer system for our boat which will do a variety of tasks. This spec will just specify we need a cpu. The cpu must
be able to process lots of data b/w our cameras and our hard disks. The cpu will have to also constantly be reevaluating the direction of the boat
and ensure that it is following along its correct path. The boat will need to keep track of certain data such as errors. It will need to respond
to communication i.e. I/O from our command center. I am not sure what temperature range the boat will be in and how hot it may get, but that is
a factor as well. Lastly there will be interesting energy issues especially if we choose our power source to be batteries and solar panels. We must
also be aware of how much interference and electromagnetic interference. How long can the cpu run consistenly and reliably? How many cores do we need?
How big should the cache be? What frequency shall it run at?

##What are the requirements that the solution must have?
- We must be able to purchase 1,000s of this cpu or maybe a similiar cpu
- It must consume a low amount of power
- It must be able communicate with various I/O such as hard disk, video camera,
compass, propeller controller, led controller, gps module, satellite communication module
 and bluetooth module
 
##Why does this problem need to be solved?
To have an autonomous, self driving vehicle, it must have a cpu to orchestrate our stored
program of instructions to drive the boat, take video, and various other functions.

##Why is this the most important problem to solve next?
The computer system orchestrates and electronically commands the components of the boat.
We need to determine a good cpu, before we can determine other electronic components that
are compatible.


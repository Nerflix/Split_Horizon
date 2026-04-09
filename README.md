Python simulation of a Distance Vector routing network implementing the Split Horizon protocol with Poison Reverse to prevent routing loops and count-to-infinity problems. Parses custom topology input from stdin and handles dynamic route updates.

# Split_Horizon
Improving the performance of the routing protocol by simulating a network of routers performing route advertisement using a Distance Vector routing and Split Horizon protocol.

The program will need to read input from the terminal/command line's standard input.
The input should be exactly as shown below (The program is case sensitive): 
X
Y
Z
....
DISTANCEVECTOR
....
X Z 8
X Y 2
Y Z 3
.....
UPDATE
...
Y Z -1
X Z 3
END
...

Please read the attached PDF to gain more insights on the requirements of the program

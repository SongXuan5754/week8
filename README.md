1.What is the role of the permanent magnet in a motor?

Permanent magnet around the edge if the motor case remains static.

2.What is the role of the brushes in a DC motor?
Brushes are a pair of loose connectors, which carry current to commutator.

3.Imagine you have a robot and want that robot to scan the room for obstacles to decide how to move around. You have a proximity sensor that measures distance. What type of motor might you use to rotate the proximity sensor to scan the room -- a DC motor, a stepper motor, or a servo motor? Why?

Servo motor. Servo motors have a rotation sensor which provide feedback to controller. The controller keeps the motors synchronized. When robot detect the distance and obstacles, servo motor can help robot control position precisely. 


DC motors never synchronized. They turn at different speeds and stop at different places. There is no feedback or controller to synchronize them.

Stepper motors have some shortcoming. It can lose position.If there is a problem such robot detect obstacles or get jammed under router, the machine controller has absoulatly no idea where the machine actually is. Also, The talk curve falls off dramatically, which means the robot will lose speed so as to lose position. 

The aim of this project is to simulate the flight physics, weather system, and an AI that is flying the Airbus A320-214 airplane.
The "player" will be able to control the ATC to instruct airplanes, and the aim is to keep the airspace safe and operations running smoothly.

The AI at this stage, is pretty basic; it can takeoff, fly through checkpoints that have precalculated turn radiuses, and approach a runway.
It can also receive altitude, heading, and speed instructions and act accordingly.
In it's current form, the AI is not able to fly, as I am in the process of rewriting the wing physics to more closely act like
a real wing, with it's changing center of pressure based on the angle of attack.

The AI at this point is pretty bare-bones, utilizing PID controllers for controlling the aircraft, and making certain decisions
based on If-statements.

In the future, I plan on implementing a "command queue" for ATC commands, which the AI will prioritize based on events happening
in the cockpit at that moment. The goal is for the AI to act similar to a human, with reaction time, and decision-making.

Thank you for taking your interest in my project!

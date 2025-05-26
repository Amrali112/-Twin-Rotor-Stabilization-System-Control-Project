# -Twin-Rotor-Stabilization-System-Control-Project

As part of a collaborative control systems project, me and my friends contributed to the design, modeling, and implementation of a Twin Rotor System aimed at achieving dynamic balance using feedback control. The system consists of a rotating shaft mounted on a stable base, with two motors and propellers on either end, mimicking a simplified helicopter rotor setup. We employed a rotary encoder to provide real-time angular position feedback and used an Arduino Uno to control motor speed through PWM, ensuring stabilization through feedback correction.

The project involved 3D modeling in SolidWorks, simulation of equations of motion using MATLAB/Simulink, and real-world testing with open-loop and closed-loop responses. We tuned a PID controller both theoretically and through trial-and-error to achieve optimal performance. Hardware included high-RPM DC motors, an MD10C CYTRON motor driver, bearings, and a robust 12V/30A power supply.

Challenges we addressed included component limitations (temporary H-bridge constraints), power supply mismatches, and real-time PID tuning. The final system successfully demonstrated feedback-driven motor control to maintain equilibrium under disturbances—highlighting our team's ability to integrate mechanical design, sensor feedback, and embedded pro

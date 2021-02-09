## Introduction - 
A common actuator in control systems is the DC motor. It directly provides rotary motion and, coupled with wheels or drums and cables can provide translational motion. The electric circuit of the armature and the free-body diagram of the rotor are shown in the following figure:

![image used](https://github.com/souvik0306/DC-Motor-speed-control-using-Simulink/blob/master/Armature.jpg?raw=true)

For this, I have assumed that the input of the system is the voltage source (V) applied to the motor's armature, while the output is the rotational speed of the shaft say ***theta***. The rotor and shaft are assumed to be rigid. I further assume a viscous friction model, that is, the friction torque is proportional to shaft angular velocity.

## Physical Paramters taken into consideration - 
1) (***J***) - Moment of inertia of the Rotor     0.01 kg.m^2
2) (***b***) - Motor Viscous Friction Constant    0.1 N.m.s
3) (***Ke***) - Electromotive Force Constant       0.01 V/rad/sec
4) (***Kt***) - Motor Torque Constant              0.01 N.m/Amp
5) (***R***) - Electric Resistance                1 Ohm
6) (***L***) - Electric Inductance                0.5 H

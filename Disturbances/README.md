
This folder contrains projects concering disturbances in control systems
Written by Brian Lesko

12/2/22 Added project on model regulation/disturbance observation, DOB

Previous work:
The Qube servo plant used in this demonstrstion has been studied previously. During this previous work, time and frequency responses have been documented when implementing a variety of controller design methods. First, D-stability, margin bounds, and mixed sensitivity were used to achieve a multi-objective design by producing a controller parameter space. Next, analytical methods were used to produce a lead-lag and then PID controller - where the same procedures were repeated for numerous increases in the plant time constant.
Controls Background:
Disturbance observation or Model regulation is a 2 DOF method that achieves insensitivity against modeling erros. Modeling erros are common due to order reduction, linearization, and parameter uncertainties. The disturbance observer, in addition to aiding modeling error, rejects disturbances within its bandwidth of operation.

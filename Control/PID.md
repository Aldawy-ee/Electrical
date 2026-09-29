# PID Controller

## What is PID?

A PID controller is a feedback control method used to minimize
the error between a desired value (setpoint) and the measured value.

## PID Components

### Proportional (P)

The proportional term responds to the current error.

### Integral (I)

The integral term responds to the accumulated error over time.

### Derivative (D)

The derivative term responds to the rate of change of the error.

## PID Equation

$$
u(t) = K_p e(t) + K_i \int e(t)dt + K_d \frac{de(t)}{dt}
$$

## Applications

PID controllers are commonly used in:

- Motor speed control
- Temperature control
- Pressure control
- Position control

## Video

[PID Controller Explained](https://www.youtube.com/)

## References

- Control Systems textbooks
- MATLAB Documentation
- Manufacturer Documentation

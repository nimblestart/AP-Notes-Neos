Kinematics is the study of motion without considering the forces that cause it. It focuses on describing motion using quantities like displacement, velocity, and acceleration.
#### 1.1 Scalars and Vectors
- <u>Scalar</u>: A quantity with magnitude only (e.g., speed, distance, mass, volume, temperature, energy).
- <u>Vector</u>: A quantity with both magnitude and direction (e.g., velocity $\vec{v}$, displacement $\Delta \vec{x}$, acceleration  $\vec{a}$). Vector quantities can be added and subtracted using vector algebra, which takes into account both the magnitude and direction of the vectors. Be careful to not add vectors that represent different types of quantities. Remember to clearly define your coordinate system before doing any calculations with vectors. All coordinate systems are equally valid, so we can choose any system. The choice will affect the numbers in the calculation, but as long as we use the coordinate system consistently, the physical meaning of the answer won't change.
#### 1.2 Distance, and Speed
- <u>Distance</u>: Distance is how far something moves and it includes the path travelled.
- <u>Average Speed</u>: $\frac{Distance}{Time}$
#### 1.3 Displacement, Velocity, and Acceleration
| **Quantity**                                                                                                                          |  **Equation**                                            |
| ------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| <u>Displacement</u>: The straight-line distance from where the object started to where it ended. The change in position of an object. | $\Delta \vec{x} = \vec{x}_f - \vec{x}_i$                 |
| <u>Average Velocity</u>: The rate of change of displacement over a time interval.                                                     | $\vec{v}_{\text{avg}} = \frac{\Delta \vec{x}}{\Delta t}$ |
| <u>Instantaneous Velocity</u>: The velocity of an object at a specific moment in time.                                                | $\vec{v} = \frac{d\vec{x}}{dt}$                          |
| <u>Average Acceleration</u>: The rate of change of velocity over a time interval.                                                     | $\vec{a}_{\text{avg}} = \frac{\Delta \vec{v}}{\Delta t}$ |
| <u>Instantaneous Acceleration</u>: The acceleration of an object at a specific moment in time.                                        | $\vec{a} = \frac{d\vec{v}}{dt}$                          |
#### 1.5 Graphical Analysis of Motion
| **Graph**             | **Slope Represents** | **Area Represents** | **Key Observations**                                                 |
| --------------------- | -------------------- | ------------------- | -------------------------------------------------------------------- |
| Position vs. Time     | Velocity             | -                   | Steeper slope = higher velocity, Zero slope = object at rest.        |
| Velocity vs. Time     | Acceleration         | Displacement        | Steeper slope = higher acceleration, Zero slope = constant velocity. |
| Acceleration vs. Time | -                    | Change in velocity  | Area under the curve = $\Delta v$.                                   |
#### 1.4 Equations of Motion (UAM - Uniformly Accelerated Motion)
These equations apply when acceleration is constant.

| **Description**                                                             | **Equation**                           |
| --------------------------------------------------------------------------- | -------------------------------------- |
| Relates final velocity to initial velocity, acceleration, and time.         | $v=v_{0}+at$                           |
| Relates displacement to initial velocity, acceleration, and time.           | $x=x_0+v_{0}t+\dfrac{1}{2}at^2$        |
| Relates final velocity to initial velocity, acceleration, and displacement. | $v^2=v_{0}^2+2a(x-x_0)$                |
| Relates displacement to average velocity and time.                          | $\Delta x = \frac{1}{2} (v_i + v_f) t$ |
#### 1.6 Free Fall
- Acceleration due to gravity ($g$): $g = 9.81 \, \text{m/s}^2$ (downward direction is negative).
- In free fall, the only force acting on the object is gravity (ignoring air resistance).
- Equations of motion apply with $a = -g$.
- For an object that is projected upward and comes back down, the scenario can be split into two separate time intervals: going up and coming down. Then, the position at maximum height can be used as the initial position _or_ the final position.
- If an object is "dropped" or "released," the initial velocity $[v_0=0]$
- The vertical velocity at the maximum height of an object's trajectory is $[0]$
- For situations where a precise value is not necessary, the value of $[g=9.8\,\text{m/s}^2]$ can be rounded to $[10\,\text{m/s}^2]$ to make calculations simpler.
- An object's velocity at any point on the way up has the same magnitude as its velocity at that same vertical position on the way down.
- The amount of time an object takes to rise to its maximum height equals the time it takes to fall back to the height from which it was projected: $[t_{up}=t_{down}.]$
###### Common mistakes
- **Forgetting to assign and use a coordinate system.** If signs of the quantities in the kinematic equations do not match your coordinate system, they will not give the correct results.
- **Thinking the direction of acceleration points the same way the object is moving.** The direction of the acceleration due to gravity is always _downward_, even if the object is going up.
- **Thinking the acceleration at the top of the object's trajectory is zero.** At the top of an object's trajectory, the vertical _velocity_ is zero, but the acceleration is still $[g,]$ downward.
- **Using $[v=0]$ for the final velocity of an object when it "reaches the ground."** In problems with a falling object, this refers to the velocity _just before_ landing. It does not refer to what happens to the object once it physically makes contact with the ground. Once the object makes contact, it is no longer in free fall and the dynamics change significantly. It may come to rest, break, bounce, etc. These portions of the motion require separate analysis.
#### 1.7 Projectile Motion
- Projectile motion is the motion of an object launched into the air, subject only to gravity.
- The horizontal and vertical motions are independent.
- Horizontal motion: Constant velocity ($a_x = 0$).
- Vertical motion: Constant acceleration ($a_y = -g$).
- Component Vectors: You will have to be able to resolve, vectors into their component vectors using trigonometric functions. Remember to use the correct angle and appropriate Trig function. 
	- ${v_x}={v\,} cos {\theta}$
	- ${v_y}={v\,} sin {\theta}$
	- $v=\sqrt {{v_x}^2+{v_y}^2}$
	- $\theta=\tan^{-1}\left(\dfrac{{v_y}}{{v_x}}\right)$
![[assets/component-vectors.svg | center | 150]]
##### Equations:
| **Quantity**            | **Equation**                                               |
| ----------------------- | ---------------------------------------------------------- |
| Horizontal displacement | $\Delta x = v_{x0} t$                                      |
| Vertical displacement   | $\Delta y = v_{y0} t - \frac{1}{2} g t^2$                  |
| Time of flight          | $t = \frac{2 v_{y0}}{g}$ (for symmetric projectile motion) |
#### 1.8 Relative Motion
- The motion of an object as observed from a different frame of reference
- Relative velocity: $\vec{v}_{\text{A relative to B}} = \vec{v}_{\text{A}} - \vec{v}_{\text{B}}$
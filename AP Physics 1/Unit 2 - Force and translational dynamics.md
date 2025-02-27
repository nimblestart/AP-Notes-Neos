Dynamics is the study of forces and how they affect the motion of objects. It builds on the concepts of kinematics by introducing the causes of motion.
#### 2.1 Newton's Laws of Motion
##### Laws
- <u>First Law (Inertia)</u>: An object at rest stays at rest, and an object in motion stays in motion unless acted upon by a net external force. $\sum \vec{F} = 0 \Rightarrow \vec{a} = 0$
- <u>Second Law</u>: The acceleration of an object is directly proportional to the net force and inversely proportional to its mass. $\sum \vec{F} = m \vec{a}$
- <u>Third Law (Action-Reaction)</u> ( $\vec{F}_{12} = -\vec{F}_{21}$): For every action, there is an equal and opposite reaction. Forces always occur in pairs e.g., when you push a wall, the wall pushes back on you with an equal force. Third law can be counterintuitive, remember that two interacting objects exert equal and opposite forces on each other, even if they have very different masses or velocities.
##### Applications
- <u>Atwood's Machine</u>: A system of two masses connected by a string over a pulley.
- <u>Pulleys</u>: Used to change the direction of a force.
- <u>Elevators</u>: Analyze forces when an elevator accelerates upward or downward.
#### 2.2 Types of Forces
- <u>Gravitational Force</u> ($\vec{F}_g = m \vec{g}$): The force exerted by Earth (or any massive object) on another object.
- <u>Normal Force</u> ($\vec{F}_N$): The force exerted by a surface to support an object. It acts perpendicular to the surface.
- <u>Frictional Force</u>: The force that opposes motion between two surfaces in contact and depends on the normal force and the coefficient of friction.
	- Static friction ($F_{f, \text{static}} \leq \mu_s F_N$): Prevents an object from moving when a force is applied.
	- Kinetic friction ($F_{f, \text{kinetic}} = \mu_k F_N$): Acts on an object in motion.
- <u>Tension</u> ($\vec{T}$): The force exerted by a string, rope, or cable, acts along the direction of the string
- <u>Applied Force</u> ($\vec{F}_{\text{applied}}$): A force applied to an object by an external agent (e.g., pushing or pulling).
- <u>Spring Force</u>:
- <u>Centripetal Force</u> ($F_c = \frac{mv^2}{r} = m r \omega^2$): The net force directed toward the center of a circular path that causes circular motion.
	- <u>Centripetal Acceleration</u> ($a_c = \frac{v^2}{r} = r \omega^2$): The acceleration directed toward the center of the circle.
#### 2.3 Free Body Diagrams
- A diagram showing all the forces acting on an object.
- Steps to Draw:
  1. Identify the object of interest.
  2. Draw all forces acting on the object as vectors.
  3. Label each force (e.g., $\vec{F}_g$, $\vec{F}_N$, $\vec{F}_f$).
  4. Break forces into components if necessary (e.g., on an incline).
#### 2.4 Inclined Planes
Forces on an object on an inclined plane can be broken into components parallel and perpendicular to the surface.
- <u>Parallel to Incline</u>: The component of gravity acting down the incline. $F_{g, \parallel} = mg \sin \theta$
- <u>Perpendicular to Incline</u>: The component of gravity acting perpendicular to the incline. $F_{g, \perp} = mg \cos \theta$
![[assets/forces_on_inclines.svg | center | 150]]
#### Circular Orbits
#### 2.7 Translational Equilibrium
- An object is in translational equilibrium when the net force acting on it is zero.
- **Condition:** $\sum \vec{F} = 0$
- **Implications:** The object is either at rest or moving with constant velocity.
#### Problem-solving tips
##### Newtons Laws
- In any physical problem it's essential to clearly define your system. The system of interest can vary significantly. It may be a single ball, a bucket of balls, the entire Earth, or anything else. Define a system that's convenient for your problem, and remain consistent with that choice throughout the analysis.
- We will almost always deal with "objects" that are in fact systems of smaller objects. But the value in defining a system is that we no longer need to worry about each individual interaction between the smaller objects in the system. All of the internal force pairs are contained within the system. So, be sure to only label _external_ forces on the system's free-body diagram.
- When locating the center of mass for a system, start by looking for any lines of symmetry. If you identify one or more lines of symmetry for the system, you know the center of mass must lie somewhere along that line.
- A system remaining at rest is not accelerating. A system moving with constant velocity is also not accelerating. A system in either of these states of motion must be experiencing zero net force. (You may also see such scenarios described as being in **translational equilibrium**.)
- A system's acceleration points in the same direction as the net force acting on the system. However, the system's acceleration and velocity may not point in the same direction.
- A system may have zero $[\Sigma \vec{F}] and [\vec{a}]$ in one dimension, but nonzero $[\Sigma \vec{F}] and [\vec{a}]$ in another dimension. The system only accelerates in the direction of the net force.
- There may be cases when a system experiences forces directed at various angles. In those cases, trigonometry may be needed to resolve the force vectors into perpendicular components so $[\Sigma \vec{F}_x] and [\Sigma \vec{F}_y]$ can be determined.
##### Inclines
- For an incline that makes an angle $[\theta]$ with the horizontal, $[\boxed{F_{g\,\parallel}=mg\sin\theta}]$ and $[\boxed{F_{g\,\perp}=mg\cos\theta}.]$ Though you can re-derive this result using diagrams and trigonometry, it's helpful to remember offhand. Considering the limiting cases of $[0^\circ] and [90^\circ]$ can help you confirm which is which.
- An object on an incline does not accelerate perpendicular to the incline's surface (unless the surface is breaking or stretching). So, the forces perpendicular to the surface must be balanced.
- For an object at rest or sliding down an incline, the force of friction $[\vec{F}_f]$ points up the incline, parallel to the surface. (If the object was sliding up the incline, $[\vec{F}_f]$ would point down the incline, parallel to the surface.)
- The analysis above was for an object undergoing **translational motion** only. The entire block was moving together in the same way (i.e., no part of the block was moving differently than any other part of the block). Therefore, we could treat the block as a point object located at the block's center of mass. However, if we were analyzing something that could _rotate_ while moving down the incline (e.g., a disk or a ball), we'd need to consider additional factors when analyzing its motion.
##### Circular Motion
- The term "centripetal force" is sometimes used to refer to the net force in the radial direction, $[\Sigma\vec{F}_\text{rad},]$ acting on an object following a circular path.
- Similarly, centripetal acceleration refers to the acceleration _in the radial direction_ of an object following a circular path. Centripetal acceleration can be related to the net force in the radial dimension by applying Newton's second law to the radial dimension, $[a_c=\dfrac{\left|\Sigma\vec{F}_\text{rad}\right|}{m}.]$ The magnitude of centripetal acceleration is also $[a_c=\dfrac{v^2}{r}.]$ These expressions for $[a_c]$ often need to be equated when analyzing circular motion scenarios.
- The analysis above also applies to objects that only traverse _part_ of a circular path. For example, if a car rounds a circular curve, it's in circular motion while making the turn. This is true even if the car does not complete a full circle.
- An object in circular motion will move at constant speed if it experiences zero tangential force. However, if the object experiences a nonzero tangential force, it will change speed as well as direction.
# Kinematics

Kinematics is the discipline which assigns a mathematical model to the motion of an object, in order to describe and analyse its motion in a quantitative manner.  An object's motion is defined to be a function of its position with respect to time.  The position of an object may be described as a vector $\vec{x}$ within a (typically two- or three-dimensional) coordinate space.  For each time $t$ within the motion function's domain, there will be an associated position vector $\vec{x}$ which identifies the position of the object at time $t$.

For example, an object that moves at the rate of 50 ms<sup>-1</sup> north and 30 ms<sup>-1</sup> east, and has the position (250 m, 20 m) at t = 0 s, will have the motion function: 

$$\vec{x}(t) = (50t + 250)\hat{\imath} + (30t + 20)\hat{\jmath}\text{ m}$$

where $\hat{\imath}$ is the unit vector in the northerly direction, and $\hat{\jmath}$ is the unit vector in the easterly direction.

```{note}
An object's position is sometimes called its *displacement*, as in how far the object is *displaced* from the origin of the coordinate system.
```

## Velocity

Velocity is defined as the *rate of change* of an object's position.  Therefore, the **average velocity** of an object between times $t_0$ and $t_1$ is equal to the change in position of the object between these times ($\Delta \vec{x}$), divided by the duration of time between $t_0$ and $t_1$ ($\Delta t$) .  That is: 

$${\vec{v}}_{avg} = \frac{\Delta \vec{x}}{\Delta t} = \frac{\vec{x}(t_1) - \vec{x}(t_0)}{t_1 - t_0}$$

From calculus, it follows that the **instantaneous velocity** function of an object with position function $\vec{x}(t)$, denoted as $\vec{v}(t)$, will be the first derivative of $\vec{x}(t)$:

$$ \vec{v}(t) = \frac{d}{dt}\vec{x}(t)$$ 


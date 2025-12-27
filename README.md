# Lorenz-Attractor-Simulation
Simulation of Lorenz Attractor in python using matplotlib

Understanding of Chaos Theory and Attractors:

**Chaos Theory:
**
  States that within every random and arbitrary behaving dynamical system there lies an underlying pattern:
    Sensitive to initial conditions— changes made in the starting stages can have drastic effects in the long term (“Butterfly effect”)
    
    Dynamical Systems: systems in which one or more variables change over time
      To represent a dynamical system, you use ‘phase space
      The axes are the system’s variables
      Each point is a possible state of the system
      And the rate of change of these point are represented as vector originating from the point, which creates a vector field

Attractors: sets of points in the phase space which attracts all trajectories in an area surrounding it— the basin of attraction (the area surrounding the attractors).
  Van der Pol Oscillator: 
  self-sustaining oscillator that models continuous, stable oscillations found in biological and electronic systems. 
  Its behavior is governed by a differential equation featuring a variable damping term (-\mu(1-x^2)\frac{dx}{dt})that adds energy when oscillations are small and removes it when large, resulting in a stable limit
  cycle. This means that regardless of the initial conditions, the system will eventually settle into a periodic oscillation with a fixed amplitude and frequency, and the attractor will also follow this.
  While the basic oscillator is not chaotic, it is a key model in nonlinear dynamics, demonstrating how complex, even chaotic, behaviors can arise in forced or coupled systems.

Strange Attractor - an attractor that has a fractal structure, the lorenze attractor has fractal space

  Lorenze Attractor: Stumbled across by Edward Lorentz while trying to simulate the weather, realised that even minute changes in a dynamical system can drastically change the entire systems outcome over time. As he simplifed his simulation  
  into 3 variables (\sigma, \rho, and \beta) and made tiny changes to each state he came across the Lorenz Attractor.
  
    The lorenz attractor has infinite curves within the finite phase space, as none of the possible trajectories repeat themselves due to the slight change in the initial state. 
    The lorenz attractor has a fractal dimensional space, as no matter how much you zoom in you will always find fractals and similiar looking curves— i personnally dont understand (if anyone wants to help give me a pull request)
  

"The Lorenz System"
\dot{x}=\sigma(y-x)
​
\dot{y}=x(\rho-z)-y
​
​​z\:=\:xy\:-\:\beta z
​



​​
​





# Bouncing-Ball-Physics-Simulation

## The simulation features:

### User-controllable parameters:

* Initial height (0.1 to 10 meters)
* Elasticity coefficient (0 to 1)
* Gravity acceleration (default 9.8 m/s²)


### Physics simulation:

* Realistic gravity effects on velocity
* Elastic collisions with energy loss
* Accurate height and velocity calculations


### Real-time data display:

* Current height in meters
* Current velocity in m/s
* Bounce count
* Elapsed time in seconds


Controls:

Start button to begin the simulation
Reset button to return to initial state



The simulation uses requestAnimationFrame for smooth animation and delta time calculations to ensure consistent physics behavior across different devices. When the ball's velocity drops below a threshold, the simulation automatically stops to simulate the real-world energy dissipation.

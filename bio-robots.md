# Biologically Inspired Robotics

Dr. Arpan Charkraborty PHD - bio inspired computer vision

---

Applications
* search rescue
* too hostile for humans
* nano robots
* underwater robots
* medical applications (micro robots)

Modeling on animals taps into evolutionary solutions. They also provide a control for your output. Sometimes the application of the robot requires a biologically inspired design. Robots need to adapt to the environment that they find themselves in. Animals like cockroaches have failsafes also, which enables them to continue even when damages or missing appendages.

Actuators are any component that allows the robot to move. Traditional actuators area not as efficient as their bilogical equivalents. 

Batteries (dead weight) - Bio systems don't have batteries. Just now exploring bio-inspired energy storage. (using currents of see to charge)

Grasping and manipulation - Alot of complexity. Haptic feedback tells animal how hard to grasp (sheer), being used now in robotics.

Limitations of bio-inspirations - Hardware is different from robots to animals. Our design choices are limited to the materials we have. 

---

### Computer vision - parallels human vision. 2 eyes allow depth perception and focus. 
* Optic flow - how the image changes conveys movement
* Foveal vision - allows focused resolution with low res base
* Radial vision (polar coordinate system) with biological systems
* Bees use UV spectrum (easier to ID flowers) tuned for specific application
* Resilence in vision - Processing of info is distributed - moving and fixation allows cleaner visual signal

---

### Control and Learning
* Control systems form the mapping between perception and action
* how do you combine multiple sources of complexity (vision, actuation) and build behaviors that make sense?
* Behavior based robotics - breakdown overall functining of robots into simple behaviors then a mechanism that combine their performance
* Exploration 
> * low - avoid objects
> * middle - wander around
> * top - keep an eye on where it has been and encourage to go to new places

**Subsumption Architecture** - way to combine architecture solutions

**Reinforcement Architecture** - Exploration and exploitation (Trial and Error) - jointly optimize different parameters based on the end result. i.e., training a robot to play ping pong. Facilitated by a reward or reinforcing function letting the robot know that it was successful or not.

---

### First takeoff of a Biologically Inspired at-scale robotic insect

"meso" scale rapid fab method called SCM (smart composite microstructures)

* search and rescue
* haz mat
* surveillance/reconnaissance
* planatary exploration

---
### Cheeta-cub Quadruped Robot

Experimentation with locomotion and fast trotting gaits. 

Used a spring loaded, pantograph mechanism with multiple segments

Froude Number - The Froude number is the ratio of the centripetal force around the center of motion, the foot, and the weight of the animal walking.
# minimal_gazebo

To spawn the model, please run ```roslaunch minimal_control minimal_control.launch```

Current issue:
- [ ] the model is sliding at start. Despite changing the inertia to simple value. It still slide, but at a slower pace.
- [ ] rear wheel spins, but the model didn't move.
- [ ] contact point is blinking on one side of the tire.

Attempted solution (but unable to be sure i did it correctly or not):
- [X] changed the kp value
- [X] changed the fdir 
- [X] added `mu` constant to the surface

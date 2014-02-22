| Method        | Format             | Description  |
| ------------- |:------------------:| ------------:| 
| thrust        | {"motor": __number__, "direction": __number__} | Motor specifies which motor to thrust.  1 is the motor on the right of the ROV, 2 is on the left, and 3 is on the rear. Direction is the direction to thrust. 1 is backward thrust, pushing the ROV forward, -1 is forward thrust, pushing the ROV backward.  For the rear motor, 1 should thrust down, floating the ROV, and -1 should thrust up, sinking the ROV.        |
| extend        | {"arm": __number__, "direction": __number__}  | Arm specifies which component of the arm to extend. Direction is the direction to extend. 1 is to extend outward, extending the arm, -1 is to retract, retracting the arm |
| claw          | {"claw": __number__, "grasp": __number__}     | CLAW specifies the claw of the arm.Grasp is the action to take to either close/open. 1 is to close the claw, -1 is to open the claw. |
| camera        | {"Direction": __number__ }        | Direction is the direction to rotate the camera.  For 1, rotate the camera to the right from the camera’s perspective.  For -1, rotate the camera to the left. |


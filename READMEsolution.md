# While True: 
## if the silver variable is true: 
 search for a silver token
 
 find_markers _distance_and_rotation
 ### if no token is detect: 
  turn the robot
 ### else if the token is already paired: 
  turn the robot
 ### else if the token is close to the robot: 
  grab the token and but it's code to the already paired tokens
  
  set the variable silver to not true
 ### else if robot_well_aligned: 
  go_straight
### else if robot_on_the_left:
 turn_right
### else if robot_on_the_right:
 turn_left
 ## else:
  search for a golden token
  
  find_markers _distance_and_rotation
 ### if no token is detect:
  turn the robot
 ### else if the token is already paired:
  turn the robot
 ### else if the token is close to the robot:
  release the token and but it's offset code to the already paired tokens
  
  set the variable silver to true
 ### else if robot_well_aligned:
  go_straight
  
  turn_right
  
  turn_left
### else if robot_on_the_left:
 turn_right
### else if robot_on_the_right:
 turn_left

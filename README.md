## Vision-based-Driving-Model


# Implementation 
->             -----------
               | Image   |
image   ---->  |         |  --------------------->    E
               | Encoder |                            m     ------------
               -----------                            b --> | Waypoint | --> Trajectory
                                                      e     | Decoder  |
->                            ------------------      d     ------------
high level command,   ---->   | Measurement    |-->   d
speed,goal(x,y)               | Encoder        |      i
                              ------------------      n
                                                      g
          




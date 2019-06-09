# where_am_i
##first step:   creat a catkin workspace
             
              $ mkdir -p catkin_ws/src
	            $ cd catkin_ws/src

              $ catkin_init_workspace
              $ cd ..
              $ catkin_make

              $ cd src
              
##second step:
            
	      $ git clone https://github.com/ymiaoy/where_am_i
              
              $ cd catkin_ws
              $ catkin_make
              
              (if you didn't add workspace's path to bashrc, you should also do this:
                   $ source devel/setup.bash
              )
 
##third step: 
       
         $ roslaunch location world.launch    
         $ roslaunch location amcl.launch
         
         $ roslaunch teleop_twist_keyboard teleop_twist_keyboard.py
              
              
              

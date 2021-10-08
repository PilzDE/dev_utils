cmake_minimum_required(VERSION 3.0.2)
project(pilz_relay_utils)

find_package(catkin REQUIRED COMPONENTS)

###################################
## catkin specific configuration ##
###################################
catkin_package()

#############
## Install ##
#############

install(FILES
  launch/sainsmart_cmd_exec.launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

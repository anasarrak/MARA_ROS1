cmake_minimum_required(VERSION 2.8.3)

project(mara_description)
find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY meshes DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
#install(FILES visualize.rviz DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

# 3D-Orientation Space Practice
### Group 4: Martí Alcoberro, Clàudia Romera
## First operating performances diagnostic, 
At first, we could only move the planer or the surgical needle independently from the ESP32 as the code didn't relate both digital and physical objects and we had not connected the hardware. 
## Corrections you have made in the code
* In src, iside Endowrist_IMU: main_cpp file, line 9: we change the group name to ours (group 4)
* In src, inside Python_scripts: Receive_data_RPY_IMU_world.py file, line 17: we change the group name to ours again
* In src, inside Python_scripts: Receive_data_RPY_IMU_world.py file, line 19: We changed the variable 'object_NAME' to the plane or surgical_needle according to the object we wanted to view. 
## Final conclusions
Once we had made all the changes, the digital object moved according to the ESP32, so we only had to calibrate the system in order to align the axis from bot digital and physical objects, then we saw that the plane or needle moved properly along with the ESP32. Likewise, 
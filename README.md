# dVRK-ROS-Sharp-Launch-Files
This repository contains the launch files used on the ROS side to send the URDF data to Unity using the rosbridge suite. The launch file for each robot can be found in the table below:

|Robot|Launch File|Known Issues|
|---|---|---|
|ECM|publish_description_ecm.launch|Some joints do not have inertial references in URDF|
|MTML|publish_description_mtml.launch|None|
|MTMR|publish_description_mtmr.launch|None|
|Both PSMs (no tool attachments)|publish_description_both.launch|No inertial references for any joints in URDF|
|PSM with caudier|publish_description_psm_caudier.launch|No inertial references for any joints in URDF|
|PSM with sca|publish_description_psm_sca.launch|No inertial references for any joints in URDF|
|PSM with snake|publish_description_psm_snake.launch|No inertial references for any joints in URDF, import process does not work|

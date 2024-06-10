# Human-Recognition-in-Surveillance-Settings
Computer Vision Project - Based on bad quality face image, returns a front-side prediction 


## Dataset Structure

I have a called 'face_square' that hols my dataset. This folder have various sub-folders inside each one representing: 

<SUBJECT_ID>_<TYPE_VIDEO>_<VIDEO_INDEX>

SUBJECT_ID: ID Citizen number of the volunteer (subject in the video)

TYPE_VIDEO= “E” for enrolment (good quality) and “U” for unconstrained (poor quality).

VIDEO_INDEX= Session 1 or Session 2 of records.


Example:

001_E_1 #First good quality video of volunteer “001”

002_U_2.mp4 # Second poor quality video of volunteer “002”


Inside each subfolder of the user: is a conjunt of frames (.jpg images) corresponding to the user, the quality and the respective session.

All frames are with same size, and with face segmentation




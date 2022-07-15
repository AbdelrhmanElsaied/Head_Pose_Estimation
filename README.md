# Head_Pose_Estimation
implementing head pose estimation notebook using mediapipe for generating face mesh and using it to predict face angles (pitch, yaw, roll)

![image](https://user-images.githubusercontent.com/103740327/179195556-5ebd3dd4-c65f-436f-a8be-85db647c4202.png)


The project is to get the headpose from '2d' landmarks not 3d landmarks..
To do so with the classical way they have to fit the 2d points with a 3d  face model which is considered as a fitting technique. At the end, it is not a deterministic solution and has its problems.
Here comes the ML to replace the 3d fitting assumption, the camera parameters and the  projection equations.


Link for data http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip

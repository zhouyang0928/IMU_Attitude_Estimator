
/×××××××××××××××××××××××××××××××××××××××××××××××××××××××××××××××/
AHRS姿态解算数据：NAV1_data,NAV2_data,NAV_data
数据格式：
1.	Accx
2.	Accy
3.	Accz
4.	Gyrox
5.	Gyroy
6.	Gyroz
7.	Magx
8.	Magy
9.	Magz
10.	Roll
11.	Pitch
12.	Yaw

	因为数据集存在问题，Yaw轴真值要比EKF和ESKF解算出的角度小8.3°。

/×××××××××××××××××××××××××××××××××××××××××××××××××××××××××××××××/
陀螺仪Allan方差分析 Allan_Data
数据格式：
3,4,5三个轴向角速度测量值
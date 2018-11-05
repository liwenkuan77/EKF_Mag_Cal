# EKF_Mag_Cal
An EKF real-time magnetic field calibration algorithm based on the Android platform that uses gyroscope data to compensate magnetometer data. Compared with the traditional ellipsoid fitting algorithm, it realizes more accurate and convenient real-time magnetic field calibration.

一种基于安卓平台，使用陀螺仪数据补偿磁力计数据的EKF实时磁场校准算法。与传统椭球拟合算法相比，实现了更加精确，便捷的实时磁场校准。

本算法实在NDK示例程序sensorgraph的基础上进行更改，调用磁力计和陀螺仪数据，并采用EKF算法对磁场数据进行磁场校准，然后输出数据。

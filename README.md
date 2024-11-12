# BNO055 Bosch Sensortec IMU with integrated sensor fusion for AHRS (STM32G474RE)
All the credit goes to the authors of the library shared under the MIT license. Kudos to [Ivy Knob](https://www.ivyknob.com/) Team! The goal of my repo is just to collect in one place some general info on AHRS for my students and provide them with a ready to use STM32CubeIDE project (for a selected AHRS) to experiment with the idea.

![BMO055 in action](/Assets/Images/bno055_in_action.jpg)

# Missing files?
Don't worry :slightly_smiling_face: Just hit Alt-K to generate /Drivers/CMCIS/ and /Drivers/STM32G4xx_HAL_Driver/ based on the .ioc file. After a couple of seconds your project will be ready for building.

# Libraries in this project
* [stm32-ssd1306](https://github.com/afiskon/stm32-ssd1306) (MIT license)
* [BNO055 STM32 library](https://github.com/ivyknob/bno055_stm32) (MIT license)

# Possible other choices
* [Library for Bosch BNO055 IMU Sensor Unit written in and for the STM32 HAL](https://github.com/d-mironov/Bosch-BNO055-STM32) (not yet tested by me)

# Readings
* [How to Calibrate a Magnetometer | Digi-Key Electronics](https://www.youtube.com/watch?v=cGI8mrIanpk) (DigiKey)
* [Sensor Saturday - On-device Magnetometer Calibration](https://www.youtube.com/watch?v=ueiXWDtLmR0) (Adafruit Industries)
* [Adafruit SensorLab - Magnetometer Calibration](https://learn.adafruit.com/adafruit-sensorlab-magnetometer-calibration/magnetometer-calibration) (Adafruit Industries)
* [Magnetometer Calibration](https://www.mathworks.com/help/fusion/ug/magnetometer-calibration.html) (MathWorks)
* [GNSS Based Low-Cost Magnetometer Calibration](https://www.mdpi.com/1424-8220/22/21/8447) (Jan Andel at al.)
* [Bosch BNO055 gyro library for STM32](https://www.ivyknob.com/blog/bno055-gyro-library-for-stm32/) (Ivy Knob)
* [Smart sensor: BNO055](https://www.bosch-sensortec.com/products/smart-sensor-systems/bno055/) (Bosch Sensortec) [NRFND]
* [Attitude and heading reference system](https://en.wikipedia.org/wiki/Attitude_and_heading_reference_system) (Wikipedia)
* [The Difference Between IMU, AHRS, and INS](https://www.youtube.com/watch?v=4CZQQ0VLCG8) (Inertial Sense, Inc.)
* [Conversion between quaternions and Euler angles](https://en.wikipedia.org/wiki/Conversion_between_quaternions_and_Euler_angles) (Wikipedia)
* [3D Rotation Converter](https://www.andre-gaschler.com/rotationconverter/) (Andre Gaschler)
* [Euler angles](https://en.wikipedia.org/wiki/Euler_angles) (Wikipedia)
* [Quaternion](https://en.wikipedia.org/wiki/Quaternion) (Wikipedia)
* [AHRS: Attitude and Heading Reference Systems](https://pypi.org/project/AHRS/) (Python package)
* [Convert quaternion to Euler angles (radians)](https://www.mathworks.com/help/robotics/ref/quaternion.euler.html) (MathWorks)
* [Convert quaternion to Euler angles](https://www.mathworks.com/help/robotics/ref/quat2eul.html) (MathWorks)
* [Kalman filtering for beginners](https://www.mathworks.com/matlabcentral/fileexchange/75324-kalman-filtering-for-beginners) (MATLAB Central)
* [Understanding Kalman Filters](https://www.youtube.com/watch?v=mwn8xhgNpFY&list=PLn8PRpmsu08pzi6EMiYnR-076Mh-q3tWr) (MATLAB)

# Call for action
Create your own [home laboratory/workshop/garage](http://ufnalski.edu.pl/control_engineering_for_hobbyists/2024_dzien_popularyzacji_matematyki/Dzien_Popularyzacji_Matematyki_2024.pdf)! Get inspired by [ControllersTech](https://www.youtube.com/@ControllersTech), [DroneBot Workshop](https://www.youtube.com/@Dronebotworkshop), [Andreas Spiess](https://www.youtube.com/@AndreasSpiess), [GreatScott!](https://www.youtube.com/@greatscottlab), [ElectroBOOM](https://www.youtube.com/@ElectroBOOM), [Phil's Lab](https://www.youtube.com/@PhilsLab), [atomic14](https://www.youtube.com/@atomic14), [That Project](https://www.youtube.com/@ThatProject), [Paul McWhorter](https://www.youtube.com/@paulmcwhorter), [Max Imagination](https://www.youtube.com/@MaxImagination), [Nikodem Bartnik](https://www.youtube.com/@nikodembartnik), and many other professional hobbyists sharing their awesome projects and tutorials! Shout-out/kudos to all of them!

> [!WARNING]
> Control engineering - do try this at home :sunglasses:

190+ challenges to start from: [Control Engineering for Hobbyists at the Warsaw University of Technology](http://ufnalski.edu.pl/control_engineering_for_hobbyists/Control_Engineering_for_Hobbyists_list_of_challenges.pdf).

Stay tuned!

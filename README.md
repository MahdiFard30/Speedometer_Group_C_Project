Speedometer
Teamwork project.

This is an embedded programming project with the task of teaching us real time communication via:

1 Local network (TCP/IP)
2 Serial and CAN/BUS communication through ESP32-EVB microcontrollers

The GUI for both client and server are implemented via the QT framework. Serial communication was also implemented via QT.

To manage the different way of communication CMake is used.

Click and se how the speedometer works.



https://github.com/user-attachments/assets/8bec4795-4a9c-4058-8643-6109401f4147



Project description 

<img width="807" height="531" alt="381748527-801e42d1-bf1b-401b-abe1-357f56232af7" src="https://github.com/user-attachments/assets/4a62291d-39a8-4c96-a2da-c6e0265440c2" />


Command to use TCP/IP (from root of the project):

mkdir build (if it does not exist)

cd build

cmake ..

make use_tcp

make

./client && ./server


Commands to use UART and CAN, you need to have the two microcontrollers for this (from root of the project):

mkdir build (if it does not exist)

cd build

cmake ..

make use_uart

make

./client && ./server

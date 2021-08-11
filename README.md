# Esp32-L298N-2-DC-motor
an arduino ide code to control 2 dc motors using ESP32, the code is tested using Wemos d1 mini. ENA and ENB pins require PWM pins that might differ deppinding on the controller.
unlike arduino, ESP require additional library to support PWM and mototr driver, a library developed by robojax for l298n driver is uploaded. you neeed to install the library in arduino IDE before copiling.
the library will add noomerous examples for l298 drivers for defferent controll methodes and situations, trying it will help understanding the library.

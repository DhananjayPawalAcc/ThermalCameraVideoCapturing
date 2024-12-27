# ThermalCameraVideoCapturing
This project is capable of capturing video from Thermal Cam.

github link to clone repo: https://github.com/ThermoEye/ThermoCamLE

1. Firstly connect the thermal cam to the laptop using Lan cable (connect LAN cable to laptop) and then connect the 12V power adapter to the cam.
2. The ip address of cam is (192.168.2.250) and ipv4 gateway is (192.168.2.15) and set your laptop ethernet ip to 192.168.2.251.
3. Then run the camera.cs file from the cloned repo. In my above Camera.cs file i have added VideoWriter.
4. If some package issue occurs like opencv.extension not installed. Then rightclick on ThermoCamSDK and go in manage nugetpackagemanger and install opencvsharp4, opencvsharp4.extensions.


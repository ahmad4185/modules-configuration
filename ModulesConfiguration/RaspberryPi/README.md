
# Plug & Play Modules Configuration Files!
Hello people! I am glad to announce my brand new series of Plug & Play Module Configuration series. In this repository you will find number of Python codes developed for Raspberry Pi projects. 

## Why We Need this Repository?
Many IoT and Embedded engineers spent a lot of time in configurations of the sensors and modules. The purpose is to save their time and to get them focused on the real solutions. 

## Files Explanation
The explanation of files are given below: 

### MP06050.py
This is Python writtenm library for MPU6050 module to be used with Raspberry Pi. To use this library, make sure that you have installed **smbus** and **Rpi.GPIO** in your Raspberry Pi module:

#### Hardware Pins 
MPU6050 sends data through **I2C** protocol. The information of required pins is given below:

- Connect MPU6050's **VCC** to Raspberry Pi's **5V**
- Connect MPU6050's **GND** to Raspberry Pi's **GND**
- Connect MPU6050's **SDA** to Raspberry Pi's Pin No. **3**
- Connect MPU6050's **SCL** to Raspberry Pi's Pin No. **5**

#### Packages Required
Follow the steps below for installing the packages if you are using **pip** for **Python3**. Otherwise, just replace **pip** with **pip3**.  

```sh
$ pip install smbus
$ pip install RPi.GPIO
```

#### Let's Get the Output
After successfully installing all the packages. Please write following command given below to run the MPU6050.py: 

```sh
$ python3 MPU6050.py
```




*Yahooo!! We got our output now and we saved the precious 2 days our life. Let's utilize it in completing our projects!*

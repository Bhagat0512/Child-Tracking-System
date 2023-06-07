# Child-Tracking-System
This paper focuses on implementing kids trailing system for each kid attending faculty. but the prevailing systems aren’t powerful enough to forestall the crime against kids since these systems provide info concerning the children the youngster the kids cluster and not concerning every kid leading to low assurance concerning their child safety .

 Recently, everywhere the globe, crime against kids is increasing at higher rates and it’s time to supply a safety support system for the kids attending to faculties.
 This paper focuses on implementing kids trailing system for each kid attending faculty. but the prevailing systems aren’t powerful enough to forestall the crime against kids since these systems provide info concerning the children the youngster the kids cluster and not concerning every kid leading to low assurance concerning their child safety to parents and additionally doesn’t consider sensing the cry of the kid and intimating constant to its oldsters.
 The projected system includes a kid toddler a baby module and 1 receiver modules for obtaining the data concerning the lost child on a periodical basis.
 The child module includes the AT mega controller international positioning system. GPS is using to find the location of the kids the location was transmitted to the local host server method. The microcontroller is connected to a parent mobile Wi-Fi device. In this project, we created an IP address.
 When the parent search the IP address location of the kid is displayed on the webpage. If that webpage is not showing the location means the kid was away, form a parent location. In this project, we added one more future the kid has on the panic button if the kid was press the panic button means continually the buzzer circuit will blow until releasing the panic button.


 CHAPTER 1 INTRODUCTION---------------------------------------------------------------06
Introduction of Project
 CHAPTER 2 COMPONENTS REQUIRED-------------------------------------------------07-12
 Hardware Component
 ESP32
 GPS Module
 GSM Module
Breadboard
 Jumper Wires
Battery
Software Component
 Arduino IDE
 Arduino Cloud
CHAPTER 3 PROPOSED METHOLLOGY------------------------------------------------13
Circuit Diagram
CHAPTER 5 SIMULATION & OUTPUT---------------------------------------------------14
Hardware Connection.
 Describe all the output for different case.
 CONCLUSION, APPLICATION & FUTURE SCOPE-----------------------------------15
 Application
Future Scope

Introduction of Project
 To have a comprehensive data base of children from 0-14 years, the “Orissa Child Census-2005” was conducted during 2nd -10th October 2005 through door-to-door household survey.
 It covered each & every household in the state and a computerized database of all the children of 0-14years, with their name, age, sex, caste, educational status, the reasons for out of school and other indicators were built up by the end of November 2005.
 The objective of this Child Census was to track each and every child in 0-14 age group throughout the state, prepare the data base, use the findings through on-line “CHILD TRCKING SYSTEM” software and update it annually with a little effort.

COMPONENTS REQUIRED
Hardware Component
ESP32
 GPS Module
GSM Module
Breadboard
 Jumper Wires
Battery
 Software Component
Arduino IDE
Arduino Cloud

2.1 Hardware Component
2.1.1 ESP32
 ESP32 is capable of functioning reliably in industrial environments, with an operating temperature ranging from –40°C to +125°C. Powered by advanced calibration circuitries, ESP32 can dynamically remove external circuit imperfections and adapt to changes in external conditions.
 Engineered for mobile devices, wearable electronics and IoT applications, ESP32
achieves ultra-low power consumption with a combination of several types of proprietary software. ESP32 also includes state-of-the-art features, such as fine-grained clock gating, various power modes and dynamic power scaling.
 ESP32 is highly-integrated with in-built antenna switches, RF balun, power amplifier, low-noise receive amplifier, filters, and power management modules. ESP32 adds priceless functionality and versatility to your applications with minimal Printed Circuit Board (PCB) requirements.
 ESP32 can perform as a complete standalone system or as a slave device to a host MCU, reducing communication stack overhead on the main application processor. ESP32 can interface with other systems to provide Wi-Fi and Bluetooth functionality through its SPI / SDIO or I2C / UART interfaces.

 GPS Module  The Global Positioning System (GPS) is a satellite-based navigation system that provides location and time information. The system is freely accessible to anyone with a GPS receiver and unobstructed line of sight to at least four of GPS satellites. A GPS receiver calculates its position by precisely timing the signals sent by GPS satellites. GPS is nowadays widely used and also has become an integral part of smart phones.

 The GTPA010 module is easy to use, having RS232 as well as USB interface. It operates over 3.2 to 5V supply range thus enabling interfacing with microcontrollers with 3.3V as well as 5V. The module outputs GPS data in NMEA0183 format. Each of message string starts with ‘$’ and then the message identifier. Each parameter is separated using a comma so that the message can be parse with the help of the commas. Features  MediaTek MT3329 Chipset, L1 Frequency, C/A code, 66 Channels  3m position accuracy  Jammer detection and reduction  Data output Baud rate: 9600 bps (Default)  Low Power Consumption: 55mA @ acquisition, 40mA @ tracking  High Sensitivity, -165 dBm, TCXO Design, superior urban performances  Patch antenna  High sensitivity  DGPS(WAAS/EGNOS/MSAS/GAGAN) support
 GSM Module A GSM modem or GSM module is a device that uses GSM mobile telephone technology to provide a wireless data link to a network. GSM modems are used in mobile telephones and other equipment that communicates with mobile telephone networks. They use SIMs to identify their device to the network.

Breadboard A breadboard, or protoboard, is a construction base for prototyping of electronics. Originally the word referred to a literal bread board, a polished piece of wood used when slicing bread. In the 1970s the solderless breadboard became available and nowadays the term "breadboard" is commonly used to refer to these.
Jumper Wires Jumper wires are extremely handy components to have on hand, especially when prototyping.
 Battery

 Software Component
 Arduino IDE  Arduino IDE (Integrated Development Environment) is the software for Arduino.  It is a text editor like a notepad with different features.  It is used for writing code, compiling the code to check if any errors are there and uploading the code to the Arduino.  It is a cross-platform software which is available for every Operating System like Windows, Linux, macOS.  It supports C/C++ language.  It is open-source software, where the user can use the software as they want it to. They can also make their own modules/functions and add them to the software.  It supports every available Arduino board including Arduino mega, Arduino Leonardo, Arduino Ethernet and more.  Word file is called a Document similarly, Arduino file is called a Sketch where the user writes code.  The format of Arduino is saved as.

Arduino Cloud The Arduino IoT Cloud is a platform that allows anyone to create IoT projects, with a user-friendly interface, and an all-in-one solution for configuration, writing code, uploading and visualization.

 PROPOSED METHOLLOGY
 Block Diagram
 Circuit Diagram

SIMULATION & OUTPUT
Hardware Connection.
Describe all the output for different case.
Hardware Connection.

CONCLUSION, APPLICATION & FUTURE SCOPE
 Application
 Future Scope
 Application
 To estimate the volume of children- enrolled/ never enrolled/ Out of School/ dropout with different caste/gender/age, house-to-house survey was conducted in the state during 2001-02 by the teachers, as a pre-project activity before initiation of SSA.
 The data collected from the household survey were used for the preparation of perspective plans for SSA. The data is being updated manually through Village Education Registers (VER) on a piecemeal basis at the school point by the teacher concerned.
 But, the coverage was not 100% in the house-to house survey, due to various field problems. In some districts, the VER has not been maintained regularly because of its voluminous structure
 Future Scope
 The earlier system did not have a comprehensive list (village wise) for these children.
 The children who would enter the school at 5+ age need to be targeted much before the next academic session begins.
 There was the problem of duplication of enrolment in various institutions.
 There was a problem of complete coverage of all 6-14 years of children in all habitations/slums to provide them the schooling facilities.
 There was the possibility of fake names in the school register by mistake or intentionally for availing undue benefits, which was over reporting the enrolment.
 There was a need to provide the benefits of free text books, mid-day meal, uniform as well as aids and appliances for disable children to the exact child.

#include <TinyGPS++.h>
#include <SoftwareSerial.h>
float k1,k2;
static const int RXPin = 19, TXPin = 18;
static const uint32_t GPSBaud = 9600;
TinyGPSPlus gps;
// The serial connection to the GPS device
SoftwareSerial GPS(RXPin, TXPin);
#include "thingProperties.h"
void setup() {
// Initialize serial and wait for port to open:
Serial.begin(9600);
// This delay gives the chance to wait for a Serial Monitor without blocking if none is found
delay(1500);
Serial.begin(9600);
GPS.begin(GPSBaud);
// Defined in thingProperties.h
initProperties();
// Connect to Arduino IoT Cloud
ArduinoCloud.begin(ArduinoIoTPreferredConnection);
/*
The following function allows you to obtain more information
related to the state of network and IoT Cloud connection and errors
the higher number the more granular information you’ll get.
The default is 0 (only errors).

Maximum is 4
*/
setDebugMessageLevel(2);
ArduinoCloud.printDebugInfo();
}
void loop() {
ArduinoCloud.update();
// Your code here
while (GPS.available() > 0){
gps.encode(GPS.read());
if (gps.location.isUpdated()){
Serial.print("Latitude= ");
k1=(gps.location.lat());
Serial.print(" Longitude= ");
k2=(gps.location.lng());
location=Location(k1, k2);
}
}
}
/*
Since Location is READ_WRITE variable, onLocationChange() is
executed every time a new value is received from IoT Cloud.
*/
void onLocationChange() {
// Add your code here to act upon Location change
}

# Industrial Automation

Industrial Automation as the name reflects is a process of atomizing the present industries by using technology. It uses control systems such as computers and information technology for handling different processes and machineries in an industry to replace human beings. It deals primarily with the automation of manufacturing, quality control and material handling processes. 

## 🔨 Basic Working

Here in this project we have designed a simple circuit which will be helpful in the packaging processes. This project is used for detecting the colors of packages and other printed items after which a direction is displayed as to where the package is to be transported. By using the servo, a hand is provided which will place the boxes or item at required position. This will be very useful in the packaging sections of industries as it will reduce the human labor and also the time consumption would be less. Not just this but the manual errors which is a usual complaint of customers, gets way too minimize.   

Firstly, the color sensor is connected to arduino uno. The TCS230 color detector measures three primary colors Red, Green and Blue and also has a separate white light detector. Since any color can be created from different levels of these primary colors, you can find out the color composition of a light source. 

Here is the basic idea about how the sensor actually works.

![Color Sensor Diagram](colorSensor.png)


## Dependencies

- Arduino
- TCS230 colour sensor with 8*8 matrix
- LCD

## 📦 Install

Open the code Arduino software and save as '.ino' file, after downloading the required pacakages,like 'liquid crystal' in library.These pacakages are available on GitHub and other online platforms as per the choice of project builder. 

After saving the code and connecting the components together, run it and view the output 'Arduino Serial Monitor', as the leds on colour sensor starts blinking. 


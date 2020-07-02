# Arduino-ThermoresponsiveCup
In this project, I will be building a Thermoresponsive cup holder that will be able to detect the correct temperature of the liquid inside the cup and provide the users      with a visual output signifying if the liquid is too hot, too cold or is of the right drinkable temperature. 

# Project Resources

# Arduino board
<img src = "https://user-images.githubusercontent.com/36547662/86252274-4a669b80-bbb3-11ea-81da-6a2a19244d5c.png" width="250" height="200">

# Breadboard
<img src = "https://user-images.githubusercontent.com/36547662/86253474-e349e680-bbb4-11ea-8a69-446dd88548d5.jpg" width="250" height="200">

# 9 Jumper wires
<img src = "https://user-images.githubusercontent.com/36547662/86253570-02e10f00-bbb5-11ea-8c1e-25d0af3f5c21.jpg" width="250" height="200">

# 3 220Ω resistors
<img src = "https://user-images.githubusercontent.com/36547662/86254651-66b80780-bbb6-11ea-82e4-09840b91c713.png" width="250" height="200">

# 3 LEDs
<img src = "https://user-images.githubusercontent.com/36547662/86252435-80a41b00-bbb3-11ea-87a6-e32779b4c735.jpg" width="250" height="200">

# Temperature sensor DS18B20 ( This is the one that I used in the project)
<img src = "https://user-images.githubusercontent.com/36547662/86252057-ff4c8880-bbb2-11ea-98c1-2c21cd8046cc.jpg" width="250" height="200">

# Temperature Sensor TMP36 (This can be used as an alternative )
<img src = "https://user-images.githubusercontent.com/36547662/86252626-bf39d580-bbb3-11ea-97bd-f4de3cec6cb9.jpg" width="250" height="200">


# Conductive Fabric
<img src = "https://user-images.githubusercontent.com/36547662/86253987-869afb80-bbb5-11ea-988f-ac9ebe475733.jpg" width="250" height="200">

# Conductive Thread
<img src = "https://user-images.githubusercontent.com/36547662/86254090-a6caba80-bbb5-11ea-8694-f8386512b137.jpg" width="250" height="200">

# Prerequisites

Before running the code make sure that you have the below mentioned libraries installed 

#### [OneWire library]( https://www.arduinolibraries.info/libraries/one-wire) - Arduino Library


#### [DallasTemperature library](https://www.arduinolibraries.info/libraries/dallas-temperature) - Arduino Library




## Project Description 
 E-textile Thermoresponsive cup holder is a smart E-Textile cup that comprises of a few Led’s, and a temperature sensor. The main idea is to be able to detect the temperature of the Tea/Coffee in the cup and give Optical feedback to the users. It provides visual feedback by lighting up the Led’s depending on the temperature of the Tea/ Coffee inside the cup. For instance, If the temperature of the liquid inside the cup is above 70 degrees Celsius, the “RED” led would light up  displaying that the temperature of the liquid inside the cup is above the normal drinkable temperature. On the other hand, if the temperature of the Tea/Coffee lowers down between 12 degrees to 4 degree Celsius, then the “BLUE” led would glow depicting that the temperature of the liquid is too cold and If the temperature of the Tea/Coffee is between the two limits, then the “GREEN” led would glow which would signify that the liquid has reached the right drinkable temperature. This idea targets all those people who generally burn themselves while accidentally drinking something very hot, primarily keeping the children and the elderly in mind, who aren’t aware if it is safe to drink something this cold or hot. Therefore, coming up with something like this would visually provide feedback to its user without having to sip the tea/coffee to know its temperature.
 
 # Schematic 
 
 <img src = "https://user-images.githubusercontent.com/36547662/86257705-383c2b80-bbba-11ea-8aa5-8ac0e05a3818.png" width = "400" height= "340">


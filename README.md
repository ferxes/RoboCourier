#Brainstorm
For our final project, we propose to create a robot that delivers objects in a lab bench setting. Graduate researchers in lab settings require rapid access to small lab tools/equipment but are too lazy to walk across the lab and get it themselves. Some common objects that fit under this umbrella in a typical biological research lab include micropipettes, micropipette tips, serological pipettes, test tubes, etc. We propose to create a robot that follows a set path and carries the equipment to the users. Users should be able to tell a lab mate to place the object on the robot and send the robot to the other user. The robot would work like a parcel courier that is on a fixed path. There exist several solutions for robots that follow a set path already specified on the internet. Our contribution to the existing projects is to add the call and response logic, and to make the robot be able to carry lab objects. We will require a budget to purchase robot parts. We likely will buy a general kit and make reversible modification such that the kit can be reused for future classes.

#Abstract
Beer pong is a drinking game played typically on college campuses across the United States. Beer pong and its derivatives has simple rules where by arrangements of Solo® cups filled with alcoholic beverage are arranged on a table and players take turns shooting a ping pong ball into one of the cups. Use of multiple plastic cups and inconsiderate party guests litters the party location. This places a financial and psychological burden on the party host due to post-game cleanup. Here we present an alternative to beer pong that is just as, if not more, challenging. We propose the next generation of inebriated entertainment by designing a robotic cup that moves and detects successful shots. We use a previously described line following robot to follow a track. This robot features an infrared LED reflectance array and implements PID control to accurately follow the line created using a reflective tape such as electrical tape. We design a new feature to the line following algorithm for stopping on the line at certain predefined locations. The robot features a mounted cup on top of its chassis that detects successful shots using a photoresistor. After stopping at a location, the robot will wait for a successful shot into the cup. The robot will then advance to the next predefined location. The winner is the user who takes the fewest shots to advance the robot to all of the predefined locations. Although one game is described, many game modes can be programmed. 

#Hardware Requirements
The project has a major hardware component, which will be detailed in greater depth in the written report. This README will list the major components used.

- Arduino Uno
- Ardumoto Shield
- Zagros Gobbit Robot Kit
- Polou QTR IR Sensor Array
- IR Sensor
- TDK Piezo Buzzer
- White Paper
- Sharpie Pen

#Software Requirements
- QTRSensors folder must be placed in the Arduino Libraries folder before attempting to compile code
- tones2.h must be present in each sketch folder
- Arduino IDE for uploading code to Arduino (at least v1.6.5)

#Included Sketches
- TimeAttack: the time attack game mode
- _20151201_aroundtheworld: the around the world game mode
- _20151201_PracticeMode: practice mode
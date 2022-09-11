# Bachelor_project
The following code is the main source for my final bachelor project.

For the final project I used two Arduino UNO boards to design and make a device for disinfecting IT devices. 

The first code was used to display on a 2004 LCD screen relevant information including: date, time, temperature and humidity of the room. This data was acquired using DHT11 and Tiny RTC DS1307 sensors. It is independent of the disinfection cycle, keeping the data in a continuous update as long as it is connected to an electrical current source.

The second code was used to start the phone's disinfection cycle. According to the code, the stages of this process are:
- lowering the phone placed on the designated support, by means of the elevator operated by a NEMA 17 stepper motor
- once reaching the preset maximum point, the elevator in its final position activates two micro switches, one for isolating the enclosure with the help of a slider attached to a servo motor and one for activating the two UV-C LED arrays.
- the whole process was timed for a cycle long enough to disinfect the user's phone.
An important point to note is that a gear was attached to the motor to be able to engage the rack within the elevator. 

The entire assembly was designed using the CATIA V5 application and later printed using a 3D printer.

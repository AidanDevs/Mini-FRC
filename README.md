# A simple guide to Mini FRC software
# Step 1 - Downloading Driver Station Software
Download and run the latest version of [Alfredo Connect Desktop.](https://github.com/AlfredoElectronics/AlfredoConnect-Desktop/releases)
# Step 2 - Downloading Arduino Libraries
Download the Arduino Library for [Alfredo Connect Reciever](https://github.com/AlfredoElectronics/AlfredoConnect-Receive/archive/refs/heads/master.zip)

In the Arduino IDE, Click `Sketch` > `Include Library` > `Add .ZIP Library...`, and select the ZIP file you downloaded.

Download the Arduino Library for the [motor shield](https://github.com/adafruit/Adafruit-Motor-Shield-library/archive/refs/heads/master.zip)

In the Arduino IDE, Click `Sketch` > `Include Library` > `Add .ZIP Library...`, and select the ZIP file you downloaded.

# Step 3 - Drivetrain Code
In the Arduino IDE, go to `File` > `Examples` > `AlfredoConnect-Receive-Master` > `Uno` > `Adafruit-Motor-Shield-v1` > `ArcadeBotGamepadUno`
This will pull up code for a two motor drive train.

# Step 4 - Programming Motors For Your Robot
First, you will need to declare your motor as a variable, an example of this is below.

![Screenshot 2022-05-01 105839](https://user-images.githubusercontent.com/76411944/166153995-78831207-c520-4a8f-a683-194e15e0242c.png)

The number in the parentheses is the motor port that your motor is connected to on the motor shield.

Next, we will program our motor to run when the A button on an Xbox remote is held down. AlfredoConnect makes this very simple with their library, an example of this is below.

![Screenshot 2022-05-01 110740](https://user-images.githubusercontent.com/76411944/166154384-8e20c7e2-c749-4eb6-b140-91bd97abe837.png)

MAKE SURE THIS IS DONE IN THE LOOP FUNCTION!

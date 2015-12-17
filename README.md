# roboclaw
A class that enables you to use a roboclaw device

# usage

The best way is to use the serial id which is located in the /dev/serial/by-id directory

import roboclaw

robo = roboclaw.Controller('/dev/ttyACM0') or a better way is roboclaw.Controller('/dev/serial/by-id/deviceNameHere')



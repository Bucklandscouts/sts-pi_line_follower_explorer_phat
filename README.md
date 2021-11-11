# sts-pi_line_follower_explorer_phat
A guide showing how we created a line following robot with an sts-pi and explorer phat

parts list:

pimoroni sts-pi kit, 
raspberry pi 3b+ with sd card loaded with raspbian
pimoroni explorer phat,
waveshare lipo hat,
2 off tcrt5000 line sensors,
150mm female to male jumper cables,
2 off double sided sticky pads
4 off 2x1 lego pieces,
2 off 3x2 lego pieces,
1 off 8x2 lego piece (to help setup sensor mounts)
4 off m2.5 x 18mm pcb standoffs,
2 off m2.5 x 15mm pcb standoffs,
4 off m2.5 nuts,
usb c cable and adapter to charge lipo,
hot glue (to attach lego),

monitor (for initial setup)
wireless keyboard & mouse (for initial setup)

assembly:
(optional, carefully drill cable entry holes for the sensor cables on the left hand side, pre assembly required to find the correct position)
assemble sts-pi as per normal minus the rear battery mounts
solder the headers on the explorer phat
using the long m2.5 setscrews included with the sts-pi kit and the 18mm pcb standoffs loosely mount the raspberry pi to the chassis
fit the battery to the li-po hat and use sticky pads to hold it on
using the 15mm pcb standoffs fit the explorer phat
tighten down all the standoffs (starting at the lowest point) put on the m2.5 nuts to hold the explorer phat and li-po hat and tighten these too.
glue one 2x1 lego piece to the top of each of the line sensors, (hollow side to the sensor) you can use the other 2x1 pieces to adjust the height later
using the 8x2 lego piece click the two 3x2 lego pieces (endways) to the top with a 3x2 space between them
the 3x2 pieces are to be glued to the underside og the chassis behind the front roller use the 8x2 peice to just help keep them inline while you glue and remove it later
connect a 150mm jumper cable to each sensors out connector, the other end goes to input one (left sensor) or input two (right sensor)
we need to make two y shaped cables, they have two female ends and one male end, they will be connected between either the +5v or the gnd on the explorerphat and the sensors
the motor terminals need to be connected to the + and - terminals on the explorer phat, if these are the wrong way around when you try running it just switch the cables on the corresponding motor

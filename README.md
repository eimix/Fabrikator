# Fabrikator Marlin 2.0.5.3

I have installed the Marlin 2.0.5.3 firmware on my Fabrikator. If you wish to upgrade you will first need to download the basic Marlin 2.0 firmware from here -

https://marlinfw.org/meta/download/

Then get the modified configuration files from my repository here -
https://github.com/kintekobo/Fabrikator

Then copy the two .h files from my github to overwrite the files from the Marlin repository as these contain the definitions that are needed for the Fabrikator. Then build with the Arduino IDE and upload to the printer.

I have also included instructions on how to save the current firmware just in case there are problems with the new firmware. This allows you to re-install the original firmware in case of a problem. Obviously you will need to run this before updating the firmware.

Please note that this is still a work in progress. I have tested it on my printer but I can't offer any guarantees that it will work on yours although theoretically there should be no difference. However if you use this code then please note that you do so at your own risk and I can't be held responsible for any damage caused.

I have taken precautions while testing, such as placing a folded up wad of paper under the nozzle at the start to ensure that when it homes it doesn't crash the bed. Also one hand on the power switch at all times. Simple basic common sense precautions.
Anyway, let me know how you get on and if there are any bugs that you detect then please feel free to let me know. I can't guarantee to fix but I will try.

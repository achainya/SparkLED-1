This folder contains two python scripts:

led_server_emulator.py  :   this scripts emulates the Spark Core and LED display for offline testing. 
                            It uses pygame to show a 16x16 display that SuperLED.py can connect to 
                            for code testing. This is great if you want to check performance issues 
                            (it the python script or the Spark Core that is the bottleneck?) and for
                            testing stuff when you don't have physical access to the LED.
                            
logserver.py            :   this is the early beginning of a TCP server that is supposed to listen for
                            external events (example: someone rings the doobell), and then trigger a
                            message or animation on the LED display (for example showing an image of
                            a blinking doorbell). What becomes of this script is at the time of writing
                            not certain :)

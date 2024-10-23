This project aims to automatically detect the location of a collided or accidental
vehicle using a Node MCU module, GSM, and GPS modules. The Node MCU is programmed
to track the vehicle's location, and in the event of an accident, it transmits an alert message
with the vehicle's position, i.e., latitude and longitude, to a designated mobile phone. This
ensures that rescue teams can quickly reach the accident spot. Vehicle tracking involves
monitoring the vehicle's location using GPS coordinates, which can also help detect stolen
vehicles. The GPS data is fed to the Node MCU and displayed on an LCD. The vehicle is
continuously tracked, and in the event of a crash, location information is automatically sent to
the concerned mobile. The hit sensor circuit, designed with a limit switch and lever, activates
when the vehicle crashes, triggering the controller to collect and transmit the GPS data via the
GSM module. Two limit switches identify if the crash occurred at the front or rear, and a push
button sends a "safe" message if the occupants are unharmed.

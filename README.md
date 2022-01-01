# cs5484_raspi_cm4
Cirrus Logic's cs5484 energy measurement IC C++ library for raspberry pi. Can be used for energy meter project. WiringPi (https://github.com/WiringPi/WiringPi) is used for SPI interface between chip and raspberry pi.<br />

# Hardware
- cs5484 eval board v1
- raspberry pi compute module 4 (raspi-cm4)
- raspi-cm4 IO board


# Create Measurement Image
# get current deploy version
cat measurementversion.txt
# build with new version number. Changing the 0.0.1 to new number
sh ./buildmeasurement.sh 0.0.1
git commit -am "your note"
git push origin main


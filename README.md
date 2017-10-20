# CurrentRead.py
python code for calculating the amperage pull in an A/C circuit, using a CT transformer and a ADC  chip.


Code was based off of the code and the circuit for the arduino open energy monitor program, and adapted for use on a pi.
-> https://learn.openenergymonitor.org/

Adafruit has good resources for learning how to set up the ADC chip used for this program.
->https://learn.adafruit.com/raspberry-pi-analog-to-digital-converters/mcp3008



-------------------------------------------
#Set-up steps needed to get code to function on a PI

sudo apt-get update
sudo apt-get install build-essential python-dev python-smbus

git clone https://github.com/adafruit/Adafruit_Python_MCP3008.git
git clone https://github.com/adafruit/Adafruit_Python_GPIO.git
cd Adafruit_Python_MCP3008

sudo python setup.py install
sudo apt-get install python-pip
sudo pip install adafruit-mcp3008

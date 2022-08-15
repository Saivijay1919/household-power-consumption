# household-power-consumption
Predicting the measurements of electric power consumption.


    Data
Data can be downloaded from: http://archive.ics.uci.edu/ml/machine-learning-databases/00235/
Just open the zip file and grab the file 'household_power_consumption.txt' put it in the directory 

This dataset has 7 features and 2,075,259 instances which, among which we can find missing values as well.
The first two features are related to the date and time of the consumed electrical power during 47 months in Paris.
The missing values are about 181853 instances in the dataset.

0   Global_active_power    float64
 1   Global_reactive_power  float64
 2   Voltage                float64
 3   Global_intensity       float64
 4   Sub_metering_1         float64
 5   Sub_metering_2         float64
 6   Sub_metering_3         float64

Attribute Information:
1.date: Date in format dd/mm/yyyy

2.time: time in format hh:mm:ss

3.globalactivepower: household global minute-averaged active power (in kilowatt)

4.globalreactivepower: household global minute-averaged reactive power (in kilowatt)

5.voltage: minute-averaged voltage (in volt)

6.global_intensity: household global minute-averaged current intensity (in ampere)

7.submetering1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).

8.submetering2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.

9.submetering3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

Regarding the sub-meters and related variables, we can refer to the following attributes;

Sub_metering_1 (corresponds to the kitchen, containing mainly a dishwasher, an oven, and a microwave)
Sub_metering_2 (mainly washing-machine, a tumble-drier)
Sub_metering_3 ( water-heater and an air-conditioner)
Global_active_power
The maximum minute averaged active power is about 11.122 kilowatt, and the minimum is 0.076 kilowatt. The mean is approximately 1.092 kilowatt.
Regarding the distribution, I shall say that the lowest global active power has the highest frequency.

Global_reactive_power
The minimum household minute-averaged reactive power is zero kilowatts, and the maximum is 1.3900 kilowatts with 0.1237 as its average.
If we check the distribution of the data we find that the reactive power in most of the cases is less than 0.5 kilowatts

voltage
The lowest average voltage is 223.2 volt, and the maximum is 254.2 volt.

sub-meters
The first sub-meter is using the most power with 88 watt-hours of active energy, followed by the second one. The lowest consumed power is for the last sub-meter which is about 31 watt-hour.

I found that the sub-meters are important criteria to measure the net consumption of the households

Moreover, one may extract new variables from the sub-meters or rearrange them to the new groups.

Description :
=============
digital clock with feature for set and configure date and time in external RTC (DS1307) using I2C interface.

Program Description
======================
Digital Clock using Interface I2C with RTC DS1307. SET_RTC_SW is used to start set date and time. INC_VALUE_SW	is used to increment the selected RTC data.
NEXT_DATA_SW is used to select the RTC data.
1: After interfacing with DS1307 using I2C, after read RTC data, then RTC data is converted BCD to Decimal and displayed in LCD.
2: When SET_RTC_SW is pressed, its starts the process the set date and time, and goes to first select Year to set. By each press of INC_VALUE_SW,  Year is increment with roll back.
3: When NEXT_DATA_SW is pressed, year is set and selects month to set. By each press of INC_VALUE_SW, month is increment with roll back.
4: When NEXT_DATA_SW is pressed, month is set and selects date to set. By each press of INC_VALUE_SW, date is increment with roll back.
5: Day in numeric is calculated from date, month and year.
6: When NEXT_DATA_SW is pressed, date is set and selects hour to set. By each press of INC_VALUE_SW, hour is increment with roll back.
7: When NEXT_DATA_SW is pressed, hour is set and selects minute to set. By each press of INC_VALUE_SW, minute is increment with roll back.
8: When NEXT_DATA_SW is pressed, minute is set and selects seconds to set. By each press of INC_VALUE_SW, seconds is increment with roll back. 	
9: When NEXT_DATA_SW is pressed, seconds is set and converts selected date and time with Decimal to BCD and then configures date and time of DS1307 RTC. Then goto Step 1.

CAUTION:
========
Schematics and simulation is done by Proteus CAD. NOT EXPERIMENTED IN REAL TIME ENVIRONMENT.

Purpose :
=========
In all my respective repositories, I just shared my works that I worked as the learning path and practiced, with designed, developed, implemented, simulated and tested, including some projects, assignments, documentations and all other related files and some programming that might not being implement, not being completed, lacks some features or have some bugs. Purpose of all my repositories, if used, can be used for educational purpose only. It can be used as the open source and freeware. Kindly read the LICENSE.txt for license, terms and conditions about the use of source codes, binaries, documentation and all other files, located in all my repositories. 

Description :
=============
I just shared my works, which I worked as learning path and practiced Embedded C programming using AT89C52 (a 8051-based 8 bit CMOS controller) such as digital clock with feature for set and configure date and time in external RTC (DS1307) using I2C interface.

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

Purpose :
=========
In all my respective repositories, I just shared my works that I worked as the learning path and practiced, with designed, developed, implemented, simulated and tested, including some projects, assignments, documentations and all other related files and some programming that might not being implement, not being completed, lacks some features or have some bugs. Purpose of all my repositories, if used, can be used for learning and educational purpose only. It can be used as the open source and freeware. Kindly read the LICENSE.txt for license, terms and conditions about the use of source codes, binaries, documentation and all other files, located in all my repositories. 

Autography :
============
I, K.M. Arun Kumar alias Arunkumar Murugeswaran, in the year 2003, graduated (B.E. in Electronics and Instrumentation Engineering (EIE) at Government College of Technology (GCT), Coimbatore, India), was a C developer, with 2 years of work experience (2003-2005) at a company, based in Chennai, India, as a network programmer (using C programming language), in a role of Software engineer in Design & Development Team, in domain of Remote Access Server (RAS) in module of Point to Point Protocol (PPP), Telnet and SS7. I resigned from that company, due to work stress that I was unable to bear, which affected my health and then treatment given by a doctor, which was not suitable for my health, worsen my health. After a rehabitation process in my health, thanks to my mother, sister and family, healthcare, myself, god and all those who directly or indirectly help and/or support me and my family, which helped me to recover my health. I again practiced and refresh C programming.
 
I have a career break from 2005 - 2023, in 2018-2019, I also learned some Embedded C Programmming using AT89C51, PIC16F887, PIC18F4680 and LPC2138 to practice Embedded C programmming and searched for the job. But in vain, mainly due to my career break and my age. 

I just shared my works that I used as the learning path and practiced, with designed, developed, implemented, simulated and tested, including some projects, assignments, documentations and all other related files. 
  
My Thanks and Tribute :
========================
I thank to my family, Friends, Teachers, People behind the toolchains and references that I used, all those who directly or indirectly supported me and/or helped me and/or my family, Nature and God. My tribute to my family, Friends, Teachers, People behind the toolchains and references that I used, Nature, Jimmy Dog, God and all those, who directly or indirectly help and/or support me and/or my family.

Toolchains that I used for AT89C51 Application design and development are as follows :
======================================================================================
1: IDE and Simulator for Application development of AT89C51           - Keil uvision 4 for C51 Development Tools
2: Desktop Computer Architecture and OS for development of AT89C51    - Intel X64 & Windows 7 (32 bit).
3: Code editor                                                        - Notepad++.
4: Documentation                                                      - Microsoft Office 2007 (alternative LibreOffice) and Text Editor.

Some reference that I refered for AT89C51 Application design and development, are as follows :
==============================================================================================
1: Schaum's Outline of Programming with C, 2nd Edition - Book authored by Byron Gottfried.
2: Understanding and Using C Pointers: Core Techniques for Memory Management - Book authored by Richard M. Reese. 
3: Embedded C - Book authored by Michael J. Pont.
4: AT89C51 product datasheet
5: https://www.electronicwings.com/8051/inside  - 8051


Note :
======
Kindly read in the source codes, if mentioned, about the Program Description or Purpose, Known Bugs, Caution & Notes and documentations. 

Repository Web Link :
=====================
https://github.com/k-m-arun-kumar-5

#Wifi scan 
#https://github.com/JIANGYIFENGPI/wifiscan
1.1 Hardware Configuration:
 This project is biult on a Raspberry Pi3.And you must have wifi adapt network on your Raspberry Pi3 or other Linux machines.
1.2 Software Configuration:This project can scan wifi networks in your area.
2. Installation instruction:
  
a) Download all the source code and store in one directory
  
b) Open Terminal window,change directoy to you folder above
 
c) Type "make" to compile
  

3. Operation instruction:
  a) Type "./wifi.a"  excute whole project.
b) If you wish to see the list of wifi (include ESSID, Channel, Frequency, MAC), open file wifiscan.h, and type #define DEBUG
  

4. List of project files:
  a) makefile
  b) main.c
  c) wifiscan.h
  d) wifiscan.c
  e) screen.h
  f) screen.c
  


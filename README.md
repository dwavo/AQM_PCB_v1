# AQM_PCB_v1

Thu Oct 15 19:47:02 PDT 2020


printed circuit board from kevin - sent to china for production.  We did version zero on an 'other mill'.  It proved to be a little too fickle. 

This is the first commercially spun pcb board for AQM luft.data project, now known as sensor community: https://sensor.community/ 

CA design PCB-v1 supports NodeMCUv2 and NodeMCUv3 esp8266 microcontroller.  

Set up with DHT and SDS011 sensors, also supports BM*280; and PMSx003 series sniffers.  P1 allows soldering screw terminals or pigtail, with positive shown as +++.  

Top diode (D1) is for reverse polarity protection.  Fusex at .25 Amp.  dc:buck (LM2596) allows external power source of  9-24V dc source (old wall warts) for long runs (over 5 meters).  This solves the potential low voltage problem of driving the 5v fan on the SDS011.  

Using two 1A 40V Shottky diodes (D2,D3) to protect computer if usb and external power are applied at the same time. Test points added for ground, 5v and 3.3v.  

When building these, adjust the lM2596 to 5v at the test point.  Put black fingernail polish or hot glue and label the power converter "5V".    

A second version is contemplated, which will allow mounting the SDS011 on the same board.   
 
comments: dclark@clarkco.com 


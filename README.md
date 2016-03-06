# eztrac_ibeacon_ios_example_swift
Example Application to see functionality of eztrac iBeacons

This example is compiled with v7.2.1 of Xcode and is completely functional.

1) When iPhone enters a Beacon region of UUID EBEFD083-70A2-47C8-9837-E7B5634DF524,
it will show near, far and distance of the beacon from the iPhone.

2) Application also demonstrates how notification can be sent when iPhone enters
a Beacon region.

3) For Corelocation library to work you have to make changes in Info.plist. Do following

  a) Open Info.plist and add a new entry by clicking on the + that appears when
     you select the Information Property List row.

  b) Add the key NSLocationAlwaysUsageDescription and make sure the Type is set to String.

  c) Add a phrase you want to show to the user to tell them why you need location
     services on, for example: “eztrac iBeacon Region”. 

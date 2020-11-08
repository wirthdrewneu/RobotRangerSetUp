# Robot Ranger Set Up
## Description
This is a guide to help you qucikly set up the Arduino IDE and connect it to the mbot ranger so it can be programmed using arduino c for Mac and Linux. Its probably fair to assume that it will also work on Windows as well. I put this together because I felt that the documentation online was not consistent and am confident it will help you get up running in less than hour rather than days, using my teams lessons learned.  
## Steps
1. This [make bot tutorital](http://learn.makeblock.com/en/learning-arduino-programming/) is a great starting point. Use it to get a brief overview of what you will be doing. \ 
   **Note: I found that in the tutorial listed above I did not need the driver for Mac in order for it to run. I would suggest skipping this step if you come accross a need for this step please share it. Step 2 in the tutorial came off to me as instructing the user to copy and paste folders into directories that didnt specifically exist. I would also not reccomend following this step (Refer to Step 6 of this documentation.) **
3. Download the [Arduino IDE](https://www.arduino.cc/en/software), you can also use the link in the tutorial above or just google Arduino IDE
4. Install Arduino IDE\
   Linux: \
   a. Extract the download into a folder of your choice.\
   b. Navigate(cd) into the extracted folder from the terminal.\
   c. Run ./install.sh\
   Mac:\
   a. Double click the compressed folder. This should give you the option to extract.\
   b. Mac will automatically generate an application shortcut in the current folder. 
5. Download [the makerbot firmware](https://github.com/Makeblock-official/Makeblock-Libraries/archive/master.zip) you can also find the link in the tutorial in Step 1 the library is hosted on github at the Makeblock-official account. 
6. Install the library. This was a step as a time drain for me I reccomend you refer to the README.md in the Makeblock Library .zip
rather than the tutorial above. I will also guide you through the steps here. \
   a. Open Arduino IDE \
   b. Go to Sketch->Include Library ->Add .zip Library Select the zip you downloaded in the previous step. \
   c. Restart Arduino IDE **Note: If you performed these steps correctly  you should be able to navigate to Include Library and see MakeBlockDrive in the list of libraries.** 
 7. Connect

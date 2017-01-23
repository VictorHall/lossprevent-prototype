# lossprevent-prototype
Loss prevention web application allowing you to track items in the customers possession throughout the store.



Project Notes

Track products an mapped indoor region. When product is scanned it is removed from visual. When product moves the vibration sensor will trigger and display that position on the map. 

My goals are to implement feature the arduino is shaken, print text on screen web site “moving”. I will eventually need to automatically update the arduino in the database. I will also need to add an ID to each and associate it with a product. Finish angular section of this tutorial which will show you how to build client and server interaction https://www.youtube.com/watch?v=PFP0oXNNveg. Add a map to interface. Get map to show a dot when triggered

My accomplishments were node server communication with arduino. When the server started it inialized the LED to begin blinking.Added 3 items to the Mlab database. To view items login to MLAB. For mlab login information go see docs
	
Setup
“Upload” program into arduino. Go to Examples > firmata > standardfirmata. See video for help, https://www.youtube.com/watch?v=8s2--hfsJDY. See documentation http://johnny-five.io/. Run node server.js for server load
Or “nodemon” for fast server reload.

My challenges were finding working code for arduino and server communication. It took 2 days for me to find it and get it working. My next change is figuring out how to get the location of the arduino to show up indoors.

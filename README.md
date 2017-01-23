# lossprevent-prototype
Loss prevention web application allowing you to track items in the customers possession throughout the store.



Project Notes

Track products an mapped indoor region. When product is scanned it is removed from visual. When product moves the vibration sensor will trigger and display that position on the map. 

To-Do’s
When shack print text on screen web site “moving”
Finish tutorial - angular js part of tutorial -  https://www.youtube.com/watch?v=PFP0oXNNveg
Add map and get map to show a dot when triggered

Mlab login 
see docs

Accomplishments
Wrote first blinking light arduino uno program
When  you move the fast vibration sensor it makes a beeping noise.
Web server communicates with arduino
Added 3 items to the database Mlab database. To view items login to MLAB
	
Setup
“Upload” program into arduino
Go to Examples > firmata > standardfirmata
https://www.youtube.com/watch?v=8s2--hfsJDY
See documentation - http://johnny-five.io/
Cd in to test
Run node server.js for server load
Or “nodemon” for fast server reload

Challenges
Finding working code for arduino and server communication and took 2 days for me to find it and get it working
Figuring out how to get the location of the arduino to show up indoors.

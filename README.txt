Got Eggplant - Grocery list application

CMPE 137: Swift Programming for Mobile Devices

Project members:
Thinh Le, #010641462, timothyle85@gmail.com
Cherie Sew, #010108800, cheriemeiyee@gmail.com
David Tran, #009962771, dtran0419@gmail.com
Timothy Wu, #008867170, msgtimwu@gmail.com

Process to build app:
Got Eggplant? uses several SDKs and components, which are the camera, UIKit, CloudKit, and MapKit. The purpose of this submission is to ensure that the UIKit, CloudKit, and MapKit can be accessed. We require the use of MapKit as users should be able to view grocery stores nearby through a map. CloudKit is used to store user’s data, such as their grocery history. UIKit is just the front-end framework/view architecture used for iOS development. 

Approach of code:
For UIKit, it was just a simple line of code: import UIKit. Testing whether it works is a given as our application has labels, buttons and textfields that are functional. 

For CloudKit, we used the code provided on canvas to test out if we have access. Initially, the connection could not be establish but the issue was solved after CloudKit was manually added to our app id by the TA. 

For MapKit, the application tracks the user's location on request through User Location Authorization. Based on that, the user's default location (or current location) should have directions to the 'Black Power Statue' landmark on the SJSU campus as a test. The statue feature a location indicator and bubble text when pressed on to display information about the landmark through the file 'Artwork.swift'. 

For the camera, a separate class was created for access. This is so further into development, we can configure the use of the camera based on what is required by our app, which in this case only the back camera is used for scanning barcodes. 


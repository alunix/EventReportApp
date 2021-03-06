# EventReportApp
The CityPulse Event Report Application for Android enables the user to see ongoing events reported by the CityPulse framework and other users. On a map view events created by CityPulse's Event Detection component and by other users of the application are shown. For user created events a possibility to change adn/or delete this events is offered. The application is connected to the CityPulse framework via a message bus and requires an installed CityPulse framework. Within a configuration dialog the connection to the framework can be changed.


## Requirements and Dependencies
- Android 5.1 smartphone
- Android Studio
- Running CityPulse framework and a running instance of the Message Bus

## Installation
For installation import the provided files into Android Studio as a new project. You have to add your google maps API key.

# Screenshots and Video
The following screenshots show different screens of the application. The first one depicts the main view with a map where the events are placed. Events commited by other users are changeable/deleteable and are marked with an additional user icon.

<img src="https://github.com/CityPulse/EventReportApp/blob/master/screenshots/screenshot1.png" width="400">

The second screenshot provides the dialog to report a new event. The user can select between three preconfigured event types, and select the intensity of the event (only for traffic jam and congestion).

<img src="https://github.com/CityPulse/EventReportApp/blob/master/screenshots/screenshot2.png" width="400">

Within the event details it is possibe to see the report time of the event and the intensity. For events commited by users it is possible to change the intensity or to delete the event. For events created by CityPulse Event Detection component the event is read only.

<img src="https://github.com/CityPulse/EventReportApp/blob/master/screenshots/screenshot3.png" width="400">

An additional screenshot providing a view of the menu structure of the application.

<img src="https://github.com/CityPulse/EventReportApp/blob/master/screenshots/screenshot4.png" width="400">

Within this dialog it is possible to change connection details and to see some statistics related to the received events.

<img src="https://github.com/CityPulse/EventReportApp/blob/master/screenshots/screenshot5.png" width="400">

In the last screenshot a simple dialog is shown allowing the users to change his name.

<img src="https://github.com/CityPulse/EventReportApp/blob/master/screenshots/screenshot6.png" width="400">

A short demonstration video is available on Youtube: https://www.youtube.com/watch?v=Xw1QhOrtYzA

## Contributers
The Event Reporting App has been developed as part of the EU project CityPulse. The consortium member University of Applied Sciences Osnabrück provided the main contributions for this application.



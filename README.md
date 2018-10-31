# SmartFarm

An app prototype designed as a solution for challenge 2 of Digital Fields Hack, an hackathon competition held on 27 and 28 October 2018 in Bologna (Italy). For further information about this event, refer to [**Hackathon Infos**](https://github.com/MrOverflOOw/SmartFarm/tree/master/Hackathon%20Infos) folder.

## Challenge 2

As participants involved in the second challenge, we needed to improve and enhance user-experience following these criteria:
* Ease of use and fast comprehension of in-app data, taken from field sensors
* Possibility to further analyze field data, visualizing correlation between them and trends
* Graphic restyling to help user associate physical characteristics of crop and fruits with data

## Solution

Our solution is a prototype of an app with the Justinmind prototyping software. It's composed by:
1. [Splash](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Splash.png): a simple splash screen for app loading
2. [Home](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Home.png): the main screen. It's composed by many components:
   - [Drawer menu](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Menu%20hamburger.png): classic hamburger-like menu. It allows to reach to the home screen, to the fields screen ("Campi"), to the requests screen("Richieste") and to the data screen ("Storico")
   - [Notifications](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Notifications.png): an hamburger-like menu to display important messages like a sensor fault or new data calculated for one of the fields
   - Map: a satellite map displaying fields linked to the account of the farmer logged in the app. They are divised and singularly clickable, to obtain specific insights based on the selected field
   - Infos: buttons visualized on the upper right of the screen, reporting fundamental field data for an immediate visualization 
   - Tab bar: the menu in the lower part of the screen, composed by 3 buttons. Each one of them enables a particular visualization of the data, regarding a specific selected field or the entirety of the possessed fields. They are:
     1. [Coltura](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Coltura.png): it allows to check for which crop a specific selected field is being cultivated for (rice, mais, ecc.)
     2. [Difesa](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Difesa.png): it allows to assess the risk and the type of infection for a specific selected field (high, medium, low)
     3. [Irrigazione](https://github.com/MrOverflOOw/SmartFarm/blob/master/Screenshots/Irrigazione.png): it allows to assess the urgency of irrigation for a specific selected field (high, medium, low)
3. Richieste: it allows to check for requests from colleagues about field works, and take charge of any of it, if necessary (like a shared to-do list)
4. Storico: just a screen displaying various type of data and their trend in past days/hours
5. Campi: a setting screen, by which a farmer can set legal/practical infos regarding fields linked to his account

## License and more

SmartFarm is published under **GNU General Public License v3.0**.

Copyright (©) **Andrea Nicholas De Montis** & **Enio Di Mauro** & [**Davide Di Donato**](https://github.com/MrOverflOOw) & **Emanuele Grimaldi** & [**Giacomo Nasi**](https://github.com/GiacomoNasi).

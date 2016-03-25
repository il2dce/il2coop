# Introduction #

_IL-2 Sturmovik: Cliffs of Dover_ doesn't offer a dedicated co-op mode like _IL-2 Sturmovik: 1946_. Therefore some features of the old co-op mode are missing. For example it is not possible for the players to select a predefined aircraft before the mission has actually started. As a result the mission is already in progress while the players select their aircraft.

To close this cap _IL2Coop_ uses a lobby mission that allows the players to select the aircraft of the upcoming mission before it is actually loaded.

# Details #

To start the lobby mission the server has to load the _IL2Coop.mis_ that is contained in the download archive. The lobby mission is operated by the _Mission_ menu of the _Order Menu_ which is opened by the tab key.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/00_OrderMenuMain.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/00_OrderMenuMain.png)

To be able to access the _Order Menu_ the player has to be within an aircraft. Therefore the lobby mission features a list of dummy aircraft which are assigned to players when players connect to the server and select a army.

## Host ##

First the host has to select the mission by the _Select Mission_ menu.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/01_OrderMissionMenuHostMainBeforeMissionSelection.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/01_OrderMissionMenuHostMainBeforeMissionSelection.png)

The list contains all mission files that are in within the _missions folder_ (e.g. "C:\Users\SomeUsername\Documents\1C SoftClub\il-2 sturmovik cliffs of dover\missions") or any sub-folder. The _Page up_ and _Page down_ option is used to scroll through the list.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/03_OrderMissionMenuHostSelectMission.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/03_OrderMissionMenuHostSelectMission.png)

Once the mission was selected the _Select aircraft_ menu is available.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/04_OrderMissionMenuHostMainAfterMissionSelection.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/04_OrderMissionMenuHostMainAfterMissionSelection.png)

The list contains all player aircraft of the selected mission file. The _Page up_ and _Page down_ option is used to scroll through the list.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/05_OrderMissionMenuHostAircraftSelection.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/05_OrderMissionMenuHostAircraftSelection.png)

Once the aircraft was selected the _Start mission_ can be used to load the selected mission and place all players into their selected aircraft.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/06_OrderMissionMenuHostMainAfterAircraftSelection.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/06_OrderMissionMenuHostMainAfterAircraftSelection.png)

The dummy aircrafts are removed and the mission commences.

![http://il2coop.googlecode.com/svn/wiki/UserGuide/img/07_AfterMissionStart.png](http://il2coop.googlecode.com/svn/wiki/UserGuide/img/07_AfterMissionStart.png)

## Client ##

The client do not have the option to select or start a mission. They are limited to the _Select aircraft_ menu.
# Athena Ticket Scanner
An android application that reads information from greek public transport tickets, using NFC.

# Short description
Athena ticket scanner, is an application that reads info from OASA tickets, and shows it to the user in an convenient and friendly GUI.
Using it is extremely easy, just tap an ATH.ENA TICKET or ATH.ENA CARD on your device's NFC sensor, and the app will show ticket information (trips left, time left on active trip, ticket ID, user profile etc.)

# Languages
Currently, available languages are Greek and English

# Device requirements
* Android 4.3 or newer
* NFC sensor

# User interface
Main screen (upon app launch) :<br>
![mainscr](mainscreenx.jpg) <br>
To change language, select the "Language/Γλώσσα" button <br>
Language picker screen : <br>
![lang](langpicker.png) <br>
<br><br>
After the completed scan of a ticket, its information will show in the Show Info activity.
The UI has a color scheme so users can easily tell which product is active, and how much time they have left.
In retrospect :
Green color = ACTIVE
Red color = EXPIRED
Gray color = INACTIVE/EXPIRED

If the trip has expired, the live timer will have a RED color and the ticket will be marked as expired in the product slots with GRAY color.<br>
If a trip is active, the live timer will have a countdown of the remaining time with GREEN color, and the active ticket will be marked with GREEN color in the product slots.<br>


UI after scanning an expired ticket : <br>
![expired](ticketscanexpired.png) <br>


# Installation
Latest app version is available on Google Play Store, link : https://play.google.com/store/apps/details?id=com.tonyTsoftware.nfctagreader2<br>
or the release section of this repository (in APK form).

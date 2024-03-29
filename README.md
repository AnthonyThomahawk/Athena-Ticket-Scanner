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

## Main UI
### Main screen (upon app launch) :<br>
![mainscr](mainscreenx.jpg) <br>
### Language picker screen : <br>
![lang](langpicker.png) <br>
The app saves the language preference in a config file and provides a restart button using a snackbar (android UI component), for the changes to take effect

## Ticket result UI

After the completed scan of a ticket, its information will be shown in the Show Info activity.

The remaining trips can either be a number (>=0) or "Unlimited" meaning the ticket is time based (expires after a certain amount of time, for example 1 month).

The UI has a color scheme so users can easily tell which product is active, and how much time they have left.<br>
In summary :<br>
Green color = **ACTIVE**<br>
Red color = *EXPIRED*<br>
Gray color = *INACTIVE/EXPIRED*<br>

If the trip has expired, the live timer will have a RED color with text "The trip has expired" and the ticket will be marked as expired in the product slots with GRAY color.<br>
If a trip is active, the live timer will have a countdown of the remaining time with GREEN color, and the active ticket will be marked with GREEN color in the product slots.<br>

The interface also features 2 product slots, one of which is the active product and the other being the expired/unused.<br>
It also contains information about the users category (if the user can get a discount or free tickets), the card ID (number found on the card) and some technical information (memory size, date issued, manufacturer of tag).

## UI Examples

### UI after scanning an active ticket : <br>
![active](ticketscanactive.png) <br>

### UI after scanning an expired ticket : <br>
![expired](ticketscanexpired.png) <br>


# Installation
Latest app version is available on Google Play Store, link : https://play.google.com/store/apps/details?id=com.tonyTsoftware.nfctagreader2<br>
or the release section of this repository (in APK form).

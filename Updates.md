# ***Update Version 0.0.2[A]**

### **Contents and Features**

- [ `/staff_id` ] has been given another feature to view all the Staff IDs that have been used

- [ `/check_flight` & `/flight` ] will be able to execute only in **Captain Lounge**

- Reduced cooldown for [ `/check_flight` ] to 30 seconds to prevent spamming and to use the command quickly as possible

- Increased cooldown for [ `/flight` ] to 30 seconds to once again prevent spamming and to use the command quickly as possible


### **Bugs and Typos Fixes**

- Fixed the issue of being able to use `/end_check` continously that deleted previous Flight Results

- [ `/end_check` ] can be used only by a special role given by the Bot

- Fixed few issues where the Bot was not configured properly to the main Delta Server's Settings


------------------------------------------------------------------------


# ***Update Version 0.0.2***

### **Contents and Features**

- Delta Airline Informer has been renamed to Delta Airline

- All commands has been switched over to Slash Commands
    > If you have been using the normal prefix, you'll be directed to use slash commands!

- Script has been simplified [ `There's more work to be done in simplifying the work!` ]

- Nearly all the messages sent by the Bot when using Commands will be sent in Embedded Messages

- Most of the Embeded Messages have GIFs in them to help Users in understanding the instructions much better

- Flight Announcements have been improved into features such as:
   >  Delta Planes representing the Aircraft chosen
   
   > Reminder for Passengers to use the Bot Command to book tickets and how to
        
    ```yaml
    First make sure you buy the ticket of your preference, [using !buy 1 <ticket type> and then !use 1 <ticket type>] 
    ``` 

- Delta Logo itself in the Flight Announce to further make it more customised for the Flight

- Changed titles of all Updates to Update Version 

- Few changes has been made over in GitHub adding new Files for future use

- Added in a new command [ `/bot_updates` ] that directs you over to GitHub to check for possible Updates or upcoming features

- Incoming members will be greeted with Plane GIF [ `Check in Credits for more info` ]

- Members that leave will be given the favour of having an angry shark after them :D

- New command called [ `/check_flight`] can only be used by **Captains** and has a cooldown of 10 mins. It'll only ping Flight Announcement Pings to prevent everyone from being pinged [ `Check in Credits for more info` ]

- New command called [ `/end_check` ] that deletes the Flight Check Announcement 

- New Command Names for [ `end` ] to [ `flight_end` ]
    
    > [ `flight_end` ] command has been removed and if you use it, you'll be directed to use the **End Flight Button**

- Error on commands if used in the wrong channel, you'll be guided to using the correct channel, if you can't view the channel, you are **not** the Host!

- [ `/flight` ] have a cooldown of 10 seconds howevever that doesn't mean you'll be able to spam to get your Flight Hosted

    > We got special measures in place :)

- When HRs are deciding whether to accept or reject Flight File, whoever judges it will have their username sent by the bot.

- HRs won't be able to Review their own Flight File, it'll give an invalid interaction

- On the console, it'll print the HR that has Reviewed the Flight and whose Flight you have Reviewed

- If you **Captains** are doing the Flights and want to cancel it, there'll be 2 Colours:

    > Red -- if Flight is cancelled

    > Green -- if Flight is successful

- Flight Departed Button has been added onto the Flight Button and The Host will be able to Delete the Button once the Plane has taken off, HR and the Flight Host itself can use the disable the **Flight Departed** Button which will delete the Private Server Link

- Staff IDs can be given by Cringley | lilmaniac | Owen **only**
    
    > Able to give Staff IDs and Delete Staff IDs from the Database


### **Bugs and Typos Fixed**

- Fixed the overlapping text in Gate Number during the filling of Flight File


### **Credits**

- [ `DiamondIsPro` ] and [ `lilmaniac573` ] suggesting sending GIFs for members that join the Server, and messages for those that leave the Server D:

- [ `MacArt542` ] suggesting Captains can use command to check if it is safe to host flights to prevent flights from being cancelled

- [ `MacArt542` ] suggesting Deleting the Private Server Link Button

### **Notices**

- Changing cooldown for [ `/flight` ] will be abandoned and a new cooldown of 10 seconds will be implemented


------------------------------------------------------------------------


# ***Update Version 0.0.1***

### **Contents and Features**

- Only **Captain** role can use `?flight` commmand in Staff Lounge or Captain Lounge

- For now, 2 hours cooldown between flights, and a message will ping you on how long left until you can host the flight once again

- Application will come in and you'll be required to follow the Format as stated in the Form

- Higher Ranks able to **`Authorise`** or **`Reject`** your Flight File

- Some Flight Buttons will automatically get disabled during inactivity, roughly `5-10 seconds`

- Automatic Embeded message to the Flight Announcement with all the details included
    
    > If your Flight File has been rejected, the Questions that you messed up on will be told by you in DMs

    ```yaml
    Make sure you have DMs open in the Server to receieve Bot DMs!!
    ```

- Link button will be able to give you the Private Server link, Make sure to click on it!

    > Flight Review button will give you a role that you will be able to review the flight!

    ```yaml
    Be sure to follow the Format Pinned in the Channel that you'll receive message, Once you sent a single message, You won't be able to send message in the Channel anymore
    ```

- Use `?end` in the flight end channel to delete the FLight Announcement and replace it with Different Message
    > Follow the intruction sent by the Bot in that channel!!


### **Credits**

- Thanks to [ `MacArt542` ] for the Suggestion of Flight Reviews, After a while, you'll get a badge to reflect it in the near future 

- Thanks to [ `DiamondIsPro` ] for the Suggestion of Deleting Flight Messages and replacing it with something else to prevent VIP Server being used for different purposes


### **Bugs**

- Logic Error in Cooldown for the Flight File being incorrect, this has been pushed to either `0.0.1[A]` update or later


### **Notices**

- If you have clicked outside the Form Border and it gets taken off your screen, nothing can be done at the moment to prevent it and the duration to reuse the command is 2 Hours, as stated in the Bugs

- Improved Flight Message in Flight Announcement will arrive `no ETA `currently

- `?help` command is not customised properly to understand the commands available in the bot

- When Ending Flight in End Flight channel, make sure to click on the Flight Reason button, as soon as possible to avoid the automatically from deleting the Message and Removing the Host Role

OpenFFBoard Profile Manager

A simple program used to automatically select different profiles based on the program currently open into the OpenFFBoard Configurator, making it easier to change games and without having to manually switch between different profiles each time.

MAKE SURE YOU BACKUP YOUR CURRENT "profiles.json" IN ANOTHER FOLDER. THIS WILL DELETE ALL YOUR CURRENT PROFILES.

Functions:  
1) Profile Creation & Loading:
When a program has started for the first time, the OpenFFBoard Profile Manager will create a profile text file that is linked to that program and
then load that into the OpenFFBoard Configurator. If a program has started previously then it will simply load the profile into the Configurator with the previous settings. 

2) Profile Saving:
When the settings inside of the OpenFFBoard configurator are saved it will automatically save it to the text file linked to the program.
This includes when you shut down the game as well it will save it to the last active program.  

3) Easy Configuration via config.json:
The Profile Manager will automatically create a file called `config.json` which allows the user to modify and add new programs to create a profile. 

4) It will work with every version of OpenFFBoard configurator unless there's a revision of how it saves and loads profiles.



Instillation and usage:

Place the Profile Manager within the same directory as the OpenFFBoard configurator.
The program will run in the system tray. 


Minor annoyances:

The only way I have found out how to load up new profiles automatically is by restarting the Configurator, so if you have made any changes to the profile 
and have not saved the profile then any changes will disappear without warning.

If you use different profiles for certain cars within the same game then this program may not be good for your use case, as this is only 1 profile per game. 


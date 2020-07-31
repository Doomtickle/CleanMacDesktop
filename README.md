# Clean Mac Desktop
Get all of those screenshots off of your desktop. I made this because I'm lazy and my desktop usually fills up with screenshots before I know what happened. 

This will take all of the screenshots saved on your desktop and put them in one folder called "Screenshots". I also set it on a cron so it just runs every day after work.

### Usage

**Download it**

`cd ~ && curl -O https://raw.githubusercontent.com/Doomtickle/CleanMacDesktop/master/.cleandesktop`


**Make it executable**

`chmod +x ~/.cleandesktop`

**Run it**

`~/.cleandesktop`

### Run it on a schedule

**Open crontab**

`crontab -e`

Add the following line to run it every day at 5pm

`0 17 * * * ~/.cleandesktop`

**Save and Close**

For more information about how crontabs work, check out this [Geeks for Geeks guide](https://www.geeksforgeeks.org/crontab-in-linux-with-examples/)


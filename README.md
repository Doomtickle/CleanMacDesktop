# Clean Mac Desktop
## Quick bash script to get all of those screenshots off of your desktop

### Usage

**Download it**

`cd ~ && curl -O https://raw.githubusercontent.com/Doomtickle/CleanMacDesktop/master/.cleandesktop`


**Make it executable**

`chmod +x ~/.cleandesktop`

**Run it**

`~/.cleandesktop`

### Run it on a schedule

**Open crontab**

`env EDITOR=nano crontab -e`

Add the following line and save to run it every day at 5pm

`0 17 * * * ~/.cleandesktop`

**Save and Close**

> For more information about how crontabs work, check out [Geeks for Geeks guide](https://www.geeksforgeeks.org/crontab-in-linux-with-examples/)


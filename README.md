[![image](https://github.com/user-attachments/assets/2dff01e7-b67b-40f0-9aa3-dfac455e172a)
](http://winhelp2002.mvps.org/hosts.htm)

## MVPS Hosts

You can use a modified HOSTS file to block ads, banners, 3rd party Cookies, 3rd party page counters, web bugs, and even most hijackers and possibly unwanted programs. This is accomplished by blocking the connection(s) that supplies these little gems. The Hosts file is loaded into memory (cache) at startup, so there is no need to turn on, adjust or change any settings with the exception of the DNS Client service. Windows automatically looks for the existence of a HOSTS file and if found, checks the HOSTS file first for entries to the web page you just requested. The 0.0.0.0 (prefix) is considered the location of your computer, so when an entry listed in the MVPS HOSTS file is requested on a page you are viewing, your computer thinks 0.0.0.0 is the location of the file. When this file is not located it skips onto the next file and thus the ad server is blocked from loading the banner, Cookie, or some unscrupulous tracker, or javascript file.

Using a well designed HOSTS file can speed the loading of web pages by not having to wait for these ads, annoying banners, hit counters, etc. to load. This also helps to protect your Privacy and Security by blocking sites that may track your viewing habits, also known as  "click-thru tracking" or Data Miners. Simply using a HOSTS file is not a cure-all against all the dangers on the Internet, but it does provide another very effective "Layer of Protection".

---

#### Example: `0.0.0.0 ad.doubleclick.net`

The example entry blocks all files supplied by that DoubleClick Server to the web page you are viewing. This also prevents the server from tracking your movements. In certain cases "Ad Servers" like Doubleclick (and many others) will try silently to open a separate connection on the webpage you are viewing, record your movements, and follow you to additional sites you may visit.

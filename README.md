ozweather
=========

Ozweather source code.
The app is compiled with my framework, submitted to GGplay, Win store n Appstore as free app.

The JQ scripts are:
1- Zara's weatherfeed, modifed to yql as it used YahooQL to suit Au weather code. My first attemtp to get geo location fails, somehow it reports my location -melbourne- is somewhere in NT hence resulting incorrect weather report. I will look at it again when I have time. 
2-Background scrolling from Simon Kusterer, https://github.com/xat/jQuery-bgScroll. I used it without modification for the cloud horizontal scrolling. Infact, there must be better way to present the Json data from Yahoo. Unfortunately, I discover I dont have that graphic gift. So if you guys can present this app in better way, pls let me know.

To make this into your app, there are few things to do:
1-delete the copyright div in the index.html ;-), or change it into yours.
2-The setting.html stores the list of Au weather codes. I got them from here http://edg3.co.uk/snippets/weather-location-codes/australia/
This list is not completed, I cannot find Foodscray, Richmond in Vic or Banktown in Nsw. Basically, i need to know the weather there to do shopping in weekend anyway. So you can change them as much as you like. The second time, reloading the app will detect new locations. Looks like a bug there.

Something seems not right:
1-It works fine in Android, I tested it on my GS4 and tablet. On IOS, when the app is called from background, it crashes, I dont know why, perhaps I set it onfocus().reload?
2-my friends at work said the setting screen-JQueryMobile 2.3- seems not propotional right after they got it built with Phonegap. I built it with my own framework, code generated to run with Ant for android, and Xcode for IOS so have no glue why it doesnt work with Phonegap. On other hand, phonegap has ... so many versions, dont know what to track or debug. Sorry guys.

What next from here?
Drop me a line or two if you got into new issues. ofcourse, if I make any new version from it, you will get update if u folk me.

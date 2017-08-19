# Timer for Websites That Steal Your Time

Have you ever experienced sudden timewarps during reading of interesting sites? This project helps to control time was spent on sites. It requires special extension for Chrome browser.


![timer working](https://raw.githubusercontent.com/ADemkin/34_timemachine/master/screenshots/timer_00.png)
![timer stopped](https://raw.githubusercontent.com/ADemkin/34_timemachine/master/screenshots/timer_01.png)
![popup message](https://raw.githubusercontent.com/ADemkin/34_timemachine/master/screenshots/timer_03.png)


Anton Demkin, 2017

# Installing

Install extension for Chrome browser [Custom JavaScript for websites](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija).

Open configuration of [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) browser extension on the site you want to control. Click on the link "your own external scripts", add [path](http://cdn.rawgit.com/ADemkin/34_timemachine/master/index.js)
. Don`t forget to press "**enable cjs for this host**" to enable custom JS.

Next time you open a website, you specified, the timer will appear in top-left corner. It will count down form 3 minutes, turn red and after time runs out it will show alerts every 30 seconds. This should help you stop procrastinating and loosing time. If your browser does not allow to run a mixed content, a message may appear in address area on the right. Click it and allow to run unsafe content. Dont worry, the script is safe.

# Tourbleshooting

If script seems not to be working as external script, you may cope and paste code form its [source](https://raw.githubusercontent.com/ADemkin/34_timemachine/master/index.js) right into cjs text field. Just open url, select all, copy and paste it.

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)

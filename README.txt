Usage:
1. put HTML element in your page: <div id="digit"></div>
2. import rollingNumberCreator from 'package'
3. init instance: let rollingNumberInstance = rollingNumberCreator();
4. create rolling number: rollingNumberInstance.default({ el: document.getElementById('digit'), from: '?', to: '1', animationDelay: 0 })
5. please note: I changed some variables in the original file, see comments in index.js, if animationDelay is not 0, there will be blinks at the start and the end of the animation. If there is any other character you want you roll, find u = "?0123456789" and include them.

Example:
![image](https://github.com/iamGeoWat/slot-rolling-number/blob/master/demo.gif)

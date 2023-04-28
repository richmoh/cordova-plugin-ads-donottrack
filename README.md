# Cordova-Plugin-Ads-DoNotTrack

jump to: [PLUGIN USAGE](#plugin-usage) | [ADD ADS](#add-ads) | [cozycode.ca](#more-cozycode) | [Open Source License](#license) 
<hr/>

Updated __2023__ for [Cordova](https://cordova.apache.org/) with no tracking consent requested <br>
Make sure to turn off `"user metrics"` in advertising settings to disable tracking <br>
To include ads with tracking, see: [cordova-plugin-ads](https://github.com/cozycodegh/cordova-plugin-ads)

***Cordova*** plugin to add ***ads*** (by Google AdMob) into an app. <br>
Use JavaScript to include ads in your app.

If you notice any issues, submit here: [github issues](https://github.com/cozycodegh/cordova-plugin-ads-donottrack/issues)<br>

Have a good one!

# PLUGIN USAGE<a id="plugin-usage"></a><br>

[see cordova-plugin-ads for full documentation](https://github.com/cozycodegh/cordova-plugin-ads#plugin-usage)<br>

<ins>banner ads</ins> <br>
[`adMob.banner(bannerId)`](docs/banner.md) <br>
[`adMob.removeBanner()`](docs/banner.md#remove-banner) <br>

# ADD ADS with no tracking<a id="add-ads"></a><br>

1. Add the plugin<br>
```properties
cordova plugin add cordova-plugin-ads-donottrack
```

2. Turn off `user metrics` while creating AdMob apps with ad units

3. Add calls to the plugin to load ads
```js
adMob.banner("test").catch(function(err){});
```

[see cordova-plugin-ads documentation](https://github.com/cozycodegh/cordova-plugin-ads#add-ads)

# More from [cozycode.ca](https://cozycode.ca)<a id="more-cozycode"></a><br>

  * [make apps with JavaScript](https://cozycode.ca/post?pon=make-an-app-with-cordova)
  * [how to make an in-app purchases with Cordova](https://cozycode.ca/post?pon=cordova-plugin-inapppurchases)
  * [a testing app for in-app purchases](https://cozycode.ca/post?pon=cordova-plugin-inapppurchases-TEST-APP)
  * [a demo app for in-app purchases](https://cozycode.ca/post?pon=cordova-plugin-inapppurchases-DEMO-APP)

# Open Source License<a id="license"></a><br>

MIT Licensed (MIT)

Copyright © 2023 [cozycode.ca](https://cozycode.ca)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do  so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

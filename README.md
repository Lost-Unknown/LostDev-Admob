# LostDev-Admob
Documentation for the Admob Ads plugin by Lost Dev for Unreal Engine.
<a href="com.epicgames.launcher://ue/marketplace/product/0f62fb48fedd4f02abcf0f3053f208b9"><h3 color="Blue">Marketplace Link<h3></a>
<h2>Admob Ads</h2>
<h3>Lets get you throught the process of setting up Admob ads in your Unreal Engine 5 Project with This plugin.</h3>

<h2>SETUP</h2>

<h4>Lets begin by setting up neccessary details for the plugin to run.</h4>
<h4> - Go to your Project settings > Plugins > Admob.</h4>
<h4> - To Enable the plugin Enable the Android options (Caution: Disable the default Admob ads support by Unreal engine to prevent errors)</h4>
<h4> - After that fill necessary details for the Admob app. Like App-ID, Ad Id's.</h4>
<h4> - if you want to enable test ads on production Ids, Enable the Test Ads options and fill the Test Device ID field with the your device's advetisement id.(Only 1 device id)</h4>
<h3>With that the basic setup is done.</h2>

<h2>Banner Ads</h2>
<img scr="Gallery/Banner.jpg" height="800" widht="450">
<h4> - To show banner ads in your project make a widget blueprint</h4>
<h4> - Add 3 Buttons to the widget and add OnClick Event to them</h4>
<h4> - To show the banner ad just attach the 'GMA Show Banner Ad' node to one of the buttons OnClick Event.</h4>
<h4> - To Hide the banner ad attach the 'GMA Hide Banner Ad' node to the other button's OnClick Event.</h4>
<h4> - To close the banner ad attach the 'GMA Close Banner Ad' node to the last button's OnClick Event.</h4>

<h2>Interstitial Ad</h2>

<h4> - To show interstitial Ad in your project make two buttons in the widget blueprint.</h4>
<h4> - call the 'GMA load Interstital Ad' Node on the first button's OnClick Event to load a Ad.</h4>
<h4> - the 'GMA load interstitial Ad' node has two delegates in it named 'Success' and 'Failed'. bind events to both of them . Success is Executed when the ad is loaded successfully and failed is called when ad fails to load.</h4>
<h4> - Similarly there are two node named as 'GMA interstitial ad Available' and 'GMA interstitial ad Requested' these two nodes provides whether the ad is available or requested respectirespectively.</h4>
<h4> - Finally to show the interstitial ad call the 'GMA show interstital ad' node from the second button's OnClick Event . if the ad is loaded then it will show.</h4>

<h2>Rewarded Ad</h2>

<h4> - To show rewarded Ad in your project make two buttons in the widget blueprint.</h4>
<h4> - call the 'GMA load Rewarded Ad' Node on the first button's OnClick Event to load a Ad.</h4>
<h4> - the 'GMA load Rewarded Ad' node has two delegates in it named 'Success' and 'Failed'. bind events to both of them . Success is Executed when the ad is loaded successfully and failed is called when ad fails to load.</h4>
<h4> - Similarly there are two node named as 'GMA Rewarded ad Available' and 'GMA Rewarded ad Requested' these two nodes provides whether the ad is available or requested respectirespectively.</h4>
<h4> - Finally to show the rewarded ad call the 'GMA play rewarded ad' node from the second button's OnClick Event . if the ad is loaded then it will show.</h4>
<h4> - In Rewarded Ad the 'GMA play rewarded ad' node also have two delegates 'Success' and 'Failed' . Bind Events to both of them.  Success is Executed when the ad is showed successfully and failed is called when ad fails to show. </h4>

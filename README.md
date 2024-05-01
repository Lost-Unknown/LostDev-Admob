# LostDev-Admob
Documentation for the Admob Ads plugin by Lost Dev for Unreal Engine.
<a href="com.epicgames.launcher://ue/marketplace/product/0f62fb48fedd4f02abcf0f3053f208b9"><h3>Marketplace Link<h3></a>
<h2>Admob Ads</h2>
<h3>Lets get you throught the process of setting up Admob ads in your Unreal Engine 5 Project with This plugin.</h3>

<h2>SETUP</h2>

<h4>Lets begin by setting up neccessary details for the plugin to run.</h4>
<h4> - Go to your Project settings > Plugins > Admob.</h4>
<h4> - To Enable the plugin Enable the Android options (Caution: Disable the default Admob ads support by Unreal engine to prevent errors)</h4>
<h4> - After that fill necessary details for the Admob app. Like App-ID, Ad Id's.</h4>
<h4> - if you want to enable test ads on production Ids, Enable the Test Ads options and fill the Test Device ID field with the your device's advetisement id.(Only 1 device id)</h4>'

<h3>With that the basic setup is done.</h2>

<h2>Banner Ads</h2>

<h4> - To show banner ads in your project make a widget blueprint</h4>
<h4> - Add 3 Buttons to the widget and add OnClick Event to them</h4>
<h4> - To show the banner ad just attach the 'GMA Show Banner Ad' node to one of the buttons OnClick Event.</h4>
<h4> - To Hide the banner ad attach the 'GMA Hide Banner Ad' node to the other button's OnClick Event.</h4>
<h4> - To close the banner ad attach the 'GMA Close Banner Ad' node to the last button's OnClick Event.</h4>

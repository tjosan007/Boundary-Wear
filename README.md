# Boundary-Wear
Simple boundary manager for Android Wear watch faces.
This is a simple class which creates and handles screen inclusive boundary rectangles for Android Wear devices, for both circular and square devices.
The main purpose of this was to easily render text based watch faces on different types of Android Wearable devices.
The class was suited to be used for drawing text in Drunk O' Clock, but can be adjusted to be used with any type of watch face which needs this type of rendering style.

Some simple trigonometry is used to created the boundary on circular devices. The main boundary (Rect object) lets you to further create sub-boundaries (more Rect objects, essentially). Good robust precision layout for items which needs to be centered on the screen (especially for round devices)

Sample image on square device:<br>
<a href="http://imgur.com/TkfqyAU"><img src="http://i.imgur.com/TkfqyAU.png" title="source: imgur.com" /></a>

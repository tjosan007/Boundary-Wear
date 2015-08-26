# Boundary-Wear
Simple boundary manager for Android Wear watch faces.

This is a simple class which creates and handles screen inclusive boundary rectangles for Android Wear devices, for both circular and square devices.

The main purpose of this was to easily render text based watch faces on different types of Android Wearable devices.
This class is suitable to be used in any Android Wear watch face project where precision is needed.

Some simple trigonometry is used to created the boundary on circular devices. The main boundary (Rect object) lets you to further create sub-boundaries (more Rect objects, essentially). On round devices, the boundary is a square (Rect object) which encompasses the most area it can on the display.
Good robust precision layout for items which needs to be centered on the screen (especially for round devices)

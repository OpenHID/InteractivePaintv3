![alt text](http://img00.deviantart.net/d0ab/i/2016/335/8/5/interactive_paint_logo_by_alaingalvan-daq9db8.png "Interactive Paint")

Interactive Paint is a showcase of what can be done using input devices such as the Intel RealSense, Leap Motion, Kinect and Multi-touch Display.
It also serves as a framework for future projects involving these input devices.

Interactive Paint allows users to draw to a canvas just like Microsoft Paint but it allows you to do so with a variety of input devices. Drawing can be done with a mouse as well as a Multi-touch Display but it can also be done using the hand tracking functionality of these input devices.

This application can also be controlled using the various gestures supported by the input devices. While not all supported gestures are used in the application, they are being recognized by the application and can be given functionality in future iterations.

Input Devices

Multi-Touch Display Guide
```
Drawing -
	Drawing is performed by touching the screen and dragging your fingers
    around the screen. Up to 10 fingers are supported at the same time.
```

Kinect Guide
```
The Kinect gave us multiple issues as only one of our Windows computers was
able to recognize the Kinect and it didn't recognize it with good
consistency. Not sure if it is an issue with my Kinect or the Microsoft SDK.
Drawing -
	Drawing is performed by lifting your hand up in front of the Kinect
    and moving it around to draw.
```

Leap Motion Guide
```
Drawing -
	Drawing is performed by lifting your hand over the Leap Motion and
    moving it around to draw.
Gesture Recognition -
	The Leap Motion can recognized different hand gestures. While the
    component that handles input from the Leap Motion can recognize all
    different gestures only the swipe gesture is supported. Swipe your
    hand over the Leap Motion to change your currently selected tool.
```

Intel Real Sense Guide
```
Drawing -
	Drawing is performed by lifting your hand up in front of the RealSense
    and moving it around to draw.
Facial Expression Recognition -
	The RealSense provides facial expression recognition and our component
    that handles input from the RealSense can recognize facial expressions
    but currently our application does not use that.
```

Tools

Color selection tool:
```
Click to select a color that will be used for all other tools.
```

Pencil tool:
```
While selected, dragging the mouse or using any input device will produce a (small) circle
at the location of the mouse pointer.
```

Rotation tools:
```
When clicked, the view rotates around the center, either 90 degress or -90 degrees.
```

Circle tool:
```
When selected, dragging the mouse out from the center can be used to create a circle
of a given radius.
```

Square tool:
```
Same as the Circle tool, but creates a square with the given radius.
```

Text tool:
```
When selected, clicking any point will bring up a dialouge that will ask for Text input.
Once the dialouge is confirmed, text is displayed on the screen.
```

Straight line tool:
```
When selected, clicking once will selected the starting point of the line, and a second click will
determine the end point.
```

\* a note on the square, circle, and line tools:
> Before the second click (meaning, while still holding down the original click) dragging around the cursor will enable a "live preview" of the shape before you commit it to the drawing.

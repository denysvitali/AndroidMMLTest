# Memory Leak Test  
This is the most simple android application to monitor how memory leaks are handled by the Garbage Collector (GC)  
To view how android manages the memory leak simply open Android Studio, import the project and start the application. Then switch to the "Android Monitor => Memory" tab and start to rotate the screen.  

This is the result from a Google Pixel C:  
![Memory leak test](http://i.imgur.com/bQB0zn0.png)  

The falling edges are due to the automatic GC of Android.

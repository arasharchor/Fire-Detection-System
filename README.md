# Fire-Detection-System

### Capstone Design
지도교수 김윤관




### The Goal
to build the high performance system that can detect fire object by using image data from both visible light and infrared light. 

### Algorithm
* labeling 
* time-series dynamic filter ( the change amount of centroid of each object, whether or not the centroid from visible light coincides with the centroid from infrared light, whether or not RGB and YCbCr of the object coincide with the fire model ) 
* the structure of client-server to imitate the system which can process both visible light and infrared light


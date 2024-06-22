# Automatic_Car_Headlight_Dimmer

**Adaptive Front Lighting System**

<br/>

**Abstract:**
While driving on the highway, vehicles make use of high beam lighting for better illumination of the road. Often times, the intensity of this beam causes glare in the opposite driver’s windshield. This is a problem for other drivers on the road and may lead to accidents. In addition to this, the system reduces the total power consumption by switching to low beam whenever the road is adequately illuminated, thus offering higher efficiency.

**------------------------------------------------------------------------------------------**

**Block Diagram:**

![Aspose Words 1179bb0e-e9ac-4b5b-b1f7-40779b524560 001](https://github.com/sourabhshanbhogue/Automatic_Car_Headlight_Dimmer/assets/84284202/90f99cdc-1662-459b-a6f3-42d87dd3179d)


**------------------------------------------------------------------------------------------**

**Working Principle:**

- A camera is mounted on the front side of the vehicle which captures image of the surrounding every two seconds. 
- The captured image is processed using Matlab. 
- From the image the region of interest is selected and then converted to grayscale(0 to 1).
- Based on a predetermined threshold value, this image is assigned to black and white values(0 or 1).  
- If adequate light is present on the road or there if is vehicle approaching from opposite direction can be determined and the front lights will be switched to low beam from high beam.

**------------------------------------------------------------------------------------------**

**Expected Outcome:**

The front lights of the vehicle must automatically adjust from low beam to high beam with respect to the change in illumination of the road or oncoming traffic.



# Self Driving Robotic Car
In the United States, over six and a half million car accidents happen every year. Over 90% of those accidents are caused by human pilot
error, according to the U.S. General Services Administration. A car that operates on artificial intelligence and is attentive 100% of the
time can drastically reduce the number of vehicle accidents every year.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Mark L | Stratford Preparatory | Mechanical/Aerospace Engineering | Incoming 7th Grader

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)

<!---

# Final Milestone

**This video is not mine, just a placeholder for until i film mine**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

-->

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/LvG_XtgDk1o?si=GcD0zFd1mAOB8xgC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

From the first milestone, not much has changed on the physical side, but in terms of software, I've added a preprogrammed loop that makes 
the motors run and thus the car move. I think the most fun part about the project is designing custom parts like an external switch 
connected to the battery, which involves soldering which is one of the things that I have not done a lot. I thought that connecting the 
L298N module to the board was impossible and extremely time intensive, involving drilling holes. However, I realized that I can just attach 
the wires and 3d design a custom adapter for the module to fit on the pre drilled holes of my board. I need to finish coding the obstacle 
avoidance features in order for my project to be officially considered a self driving car.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/KbAKzpfG8K0?si=2EWMpHW01JAYsbqv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The microcontroller is the head of the car: it sends commands to the rest of the components, in addition to supplying power. The general 
concept is that the ultrasonic and infrared sensors sent signals to the microcontroller which then send signals to the motor driver and 
then the motors. I have finished building the car and wiring everything together. The L928N module requires an adapter, and I'm still 
working on printing it. Now it's just about coding the self driving features and implementing a remote control switch system to manually control the car.

<!---

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

# Bill of Materials

| **Part** | **Description** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| SunFounder R3 Board | Microcontroller | 15.99 | <a href="https://www.sunfounder.com/products/arduino-unor3-control-board"> Sunfounder </a> |
| L298N Module | Motor Driver | 6.99 | <a href="https://www.sunfounder.com/products/l298n-motor-driver-board"> Sunfounder </a> |
| TT Motor | Motor/Main Propulsion | 8.88 | <a href="https://www.amazon.com/Wishiot-2pcs-DC3-6V-Motor-Reduction/dp/B07VBXXT9M/ref=sr_1_6?crid=9EWJOGQ6ME61&dib=eyJ2IjoiMSJ9.yoxb_qM_lXKGkbdWCflA79t88uxHUir1dSeKNdbO5S2zAusmSWVBNZAq_UB3WvBlwFu3_Snl1zz0H43mtqkquAsQMBEYHANJfDmr1__H0xLgEjSFuI5Uqxw_REBxbFS4ksy8gQP5d-IpQj3Ar2oXSDmOd7UGGBuGNnc3NBND6R6n9ccBzYKWzqOxqtZaJIZRhdc-_k1EhnpD51P5FNeY7Ffxfi6K3uR0c3WprGpiedfzBv9dRrhFO1Ccq2kuyvJVQ-AfdJUMRcsrxlZDOuA2Pk6jiMoBse_hdDaaDbplf_A.C2V4VeYSqoytwuzl5VbcriSn6KMISLZcmYwi4U5A22g&dib_tag=se&keywords=tt+motor&qid=1718743027&s=industrial&sprefix=tt+motor%2Cindustrial%2C133&sr=1-6"> Amazon </a> |
| HC-SR04 Module | Ultrasonic Sensor | 6.99 | <a href="https://www.amazon.com/WWZMDiB-HC-SR04-Ultrasonic-Distance-Measuring/dp/B0B1MJJLJP/ref=sr_1_3?crid=RRD1BCLW5MA2&dib=eyJ2IjoiMSJ9.e5Yfpkja9gNArv99GdcfIbPkHEwnA5_v-S2dX3lHPU1h-CE0FMngmPIN-RWz6_85D7uy5lUjfES3fg8KH2LiWyd5kh_eYecUzivuSBQgQ-7V5q75bfTPT1c-Dw9xsK92pB3EvvorlFjzTcLxt8t1LBe64BRysrk8liNih8EQ-6P1PoQiFy3AevOLQyCa-a_bTAyFF3-a0RvuelPeJLR0WkLGTGlJXGuw4VWhcJvB1eVelgDc1Xq--b0qQDFmUbUmmA2B4V3DlQ8IWgl-SM02pAbIlgLx1abBgCv4Nho5a1c.BtzBEEH9LEJkV-BPYB2_uFIboXIgEIp9MKHCdeLmm8E&dib_tag=se&keywords=hc%2Bsr04%2Bultrasonic%2Bsensor&qid=1718743144&s=electronics&sprefix=hc%2Bsr04%2Celectronics%2C131&sr=1-3&th=1"> Amazon </a> |
| FC-51 Module | Infrared Sensor | 8.99 | <a href="https://www.amazon.com/ALMOCN-Infrared-Obstacle-Avoidance-Raspberry/dp/B08ZMJGKQP/ref=sr_1_15?crid=19UUMAOAS76Q9&dib=eyJ2IjoiMSJ9.2SYg7ZngTzI3kV3jYMQbeoQveQACXH5_b3CRBBWVW1x_kNlywPaRAJ_PTJ6oPY2q-DUClHKUjYl6ZpcNQLPXEKu867TGuBM0wNwJ3hiQMBa25ESKUnvE2mN77JhgGFXtJJzab5h8_Uu2Ly5v73qwNxMMvYpWrswW5SB9RQ5yVeXsrLhkWGZQ2UqwlkJsArE-9SnV1ssFYPy6ANCptEGdsdfURJar9Cv2Q2vEM5dMz4mGQ8BW1VuPVhlDeWv0S6Qh4zUST9i3erZpyejEIokC-3zITgLdMf9rlqtnrsB03kM.UxvVeUpxsl3QbaVVhUdt1KDcI2JOQuOjC_FE0qOPK2g&dib_tag=se&keywords=obstacle+avoidance+module&qid=1718743405&s=electronics&sprefix=obstacle+avoidance+moudle%2Celectronics%2C122&sr=1-15"> Amazon </a> |
| Tiny Premium Breadboard | Solderless Circuitboard | 3.95 | <a href="https://www.adafruit.com/product/65"> Adafruit </a> |

<!---

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

-->

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/qB56Gisgcb0?si=aOHxcnctfWgcvuFH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This is my starter project. I practiced soldering by putting together a cool color mixing experiment/lab with RGB. The kit came with 5
pieces: a 4-pin RGB LED, a mini white PCB with pre-cut holes, and three linear potentiometers. Soldering was difficult at first, but with
practice I started to get the hang of it. I believe that learning to solder will greatly benefit me in making my final project.

# 

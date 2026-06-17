# High Voltage Launch Controller
 A NAR-compliant rocket launch controller with multiple safety controls and a large red launch button for reliable motor ignition.

 <img width="4032" height="3024" alt="IMG_6979" src="https://github.com/user-attachments/assets/06cc1761-62f1-4185-8944-72ed4325b92c" />

In action! -> https://youtu.be/g5O2mOlEx04

**Inspiration** 
I've worked with few launch controllers, and they all are expensive, so I decided to make my own for cheap, and add all my gadets. 
**Features**
1. Key locked safety
2. Red Safety Flip-Cover Switch
3. Led which lights to ensure continutity with the ignitor
4. momentarty button which is requiered to be held during igniton
5. THE big red button which requires a secondary button(momentary button) to be able to let the current pass through the ignitor.

A cad example of my project: <img width="962" height="620" alt="Screenshot 2026-06-16 at 8 58 18 PM" src="https://github.com/user-attachments/assets/4c501b4d-7e4b-4be6-a46c-98a4807812b8" />


**How to Works**
The launch controler in simplicity is one giant circut with multipe pathways which allow different amount of amps flow through the ignitor. First the launch controller needs to be able to provide the operator a signal which gives the sign of the ignitor being hooked up propely. This is done by having one of the switches come pre built with a led which allows a minimal amount of current to flow through the ignitor when the safety key swtich is closed. this current is extreme minimal, and is not able to set of the pyrotechnic gel on the ignitor. With the led on, the operator now knows its properly connceted, and closes the red cap switch. Now for the max current to flow, the momentarty button(Black small on left side) needs to be pressed down. This will set up the final step, along with a buzzer which will signal that the ignitor saftey features are off, and ready to launch. While holding down the momentary button, the red button is able to be pressed. When pressed after is ok, the rocket will launch via the max current which is flowing through the ignitor setting the pyro gel off in the motor. 

**Build Process** 
I used CAD to copy the emblem, and create the outer shell. the box is just 3d printed with some lead holes for the M2 screws to be placed. Wiring took awhile, due to the lack of expierene, and the constant change of design as I had learned about the coninutity regulation mid build. 

**Wiring**
<img width="1262" height="799" alt="Launch Controller specifications " src="https://github.com/user-attachments/assets/79f836dc-0c27-4165-b2eb-1f5bec1acb3e" />



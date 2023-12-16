# Final Project

**NAMES OF COLLABORATORS HERE**

Kazim Jafri (khj23)\
Rei Chen (rc884)\
Zixin Li (zl865)\
Rowan Wu (rww99)\
Arystan Tatishev (at855)\
Qianxin Gan (qg72)


## Project plan

Peer feedback on Project plans: November 21

Functional check-off - November 28 & 30

Final Project Presentations - December 12

Write-up and documentation due - December 15 

## Objective
For the final project we created a cat food dispenser. It is able to recogize cats, goose, and human. 

 
## Description


## Deliverables

1. Project plan: Big idea, timeline, parts needed, fall-back plan.

## Big Idea

<img src="./img/img1.png" width="800">\

Our interactive device uses image recognition technology to identify cats and geese with a webcam, and dispenses treats for each animal depending on what the system recognizes. We plan to place the device at the Roosevelt Island cat sanctuary to live test it. 

## Timeline

November 14 - Project plan

November 16 - MakerLAB 3D printing training

November 21 - Peer feedback on Project plans

November 28 & 30 - Functional check-off

December 5 & 7 - Final Project Presentations

December 14 - Write-up and documentation due

## Expected Challenges:

- Constructing hardware of food dispenser with 3D printing
- Computer visioning of recognizing animals vs humans

## Parts needed
- Cat and goose photos
- Raspberry Pi
- LED light strip
- Webcam
- 3D printed cat and goose food dispenser
- Water bottle as food container
- Qwiic Servo Controller and Micro Servo Motor SG5


## Fall-back plan
Making changes to the feeder if the feeder is too complicated. We can make it simpler by making cardboard boxes that flip open. 

## Documentation of design process

1. 3D Printing of Components: Our project began with the design and 3D printing of various parts for our automated cat feeder. This included the main body, dispensing mechanism, and other structural elements. We identified a design that suited our needs on Thingiverse, and split up the printing in Maker Lab. Printing all the raw parts took about 40-45 hours total over the course of a week.
2. Assembly and Cleaning: Post-printing, we carefully cleaned and assembled these components, ensuring they fit together seamlessly and functioned properly. This involved sanding down rough edges and imperfections from the printer,  and screwing and gluing different parts to attach together.
3. Integration of Motor: A crucial step was the integration of a motor into the feeder. This motor is responsible for rotating the dispenser, enabling the controlled release of cat food. We also had to sauder wires to connect the motor to the Pi and breadboard.
4. Machine Learning Model Development: We developed a machine learning model capable of differentiating between humans, cats, and geese based on an image library. This model is vital for the feeder's smart operation, allowing it to respond appropriately to different animals. When it sees a cat, it meows and dispenses a treat.
5. Testing Phases:\
Phase 1 - Photographic Testing: We initially tested our device using printed and digital (phone) photographs of cats and geese. This phase helped us to fine-tune the model's accuracy in differentiating between these animals.\
Phase 2 - Real-World Testing: The final testing phase involved real cats. This step was crucial in understanding the practical functionality and reliability of our feeder in a real-world scenario.



## Archive of all code, design patterns, etc. used in the final design. (As with labs, the standard should be that the documentation would allow you to recreate your project if you woke up with amnesia.) :

Code: https://github.com/zl2877/Interactive-Lab-Hub/tree/Fall2023/Final%20project/finalCode

3D model of the dispenser: https://www.thingiverse.com/thing:3298177

   
## Video of someone using your project:

https://www.youtube.com/watch?v=19dnZaIqe7E
   
## Reflections on process (What have you learned or wish you knew at the start?)

Model Limitations: We discovered that our model's accuracy is contingent on the type of image used. It was trained primarily on full-body images of geese, resulting in limited capability to recognize images showing only the heads of geese. We would have trained the model on more images of cats and geese with only the top parts of their body if we knew this at the start or had more time. 

Mechanical Challenges: The feeder's dispensing mechanism, particularly the rotator, was designed for average-sized cat food pellets. We observed that larger pieces of cat food tend to jam the mechanism. This issue suggests the need for a more adaptable design to accommodate varying sizes of cat food.

Placement of Video Camera: The video camera needs to be positioned at an appropriate angle to recognize objects better. If we had more time, we would have built a stand to position the camera so it is at a better angle. 

Live Testing at Sanctuary: We were not able to test our device at the Roosevelt Island Cat Sanctuary because they do not allow feeding of the wildlife. However, we were able to test the device on live cats through some willing cat owners. We have not tested the camera and dispenser on live geese due to concerns about disturbing the wildlife by getting to close or feeding them improperly.


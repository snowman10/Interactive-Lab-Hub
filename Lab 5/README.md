# Observant Systems

**NAMES OF COLLABORATORS HERE**

Kazim Jafri (khj23)\
Rei Chen (rc884)\
Zixin Li (zl865)\
Rowan Wu (rww99)\
Arystan Tatishev (at855)


### Construct a simple interaction.

* Pick one of the models you have tried, and experiment with prototyping an interaction.
* This can be as simple as the boat detector showen in a previous lecture from Nikolas Matelaro.
* Try out different interaction outputs and inputs.

We tried out the teachable machines. The AI was trained on recognizing if the person is in front of the camera or if the person is holding a bottle in their hands. The user can stand in front of the camera and the AI will recognize their poses. 

Video: https://youtu.be/DjKtj3Q0j5g


### Part C
### Test the interaction prototype

Now flight test your interactive prototype and **note down your observations**:
For example:
1. When does it what it is supposed to do?
   
The prototype tells whether the person in front of the camera is just sitting there or is holding a bottle in their hands. 

1. When does it fail?

It fails sometimes when there are more than one person in front of the camera. Although no one is holding a bottle, the AI still thinks that a person is holding up a bottle. It also fails at times when the person is holding up their hand but there is not water bottle in their hand. The AI still thinks that the person is holding up a bottle.
   
1. When it fails, why does it fail?

It is likely because the AI was only trained on the data of one person and one bottle. So it is harder to tell the pose of the person from another user. Also, the AI might be more sensitive to the pose of the person, so even if there is no bottle, the AI still thinks the person is holding a bottle if their hand is held up. 

1. Based on the behavior you have seen, what other scenarios could cause problems?

When there are many users in front of the camera at once. 

**\*\*\*Think about someone using the system. Describe how you think this will work.\*\*\***
1. Are they aware of the uncertainties in the system?

It is not hard for users to tell that the system isn’t accurate if they can see the feedback from the AI, as they will know that the AI is not telling their poses right. However, it will be more difficult if they cannot visually see the AI’s feedback. 
   
1. How bad would they be impacted by a miss classification?

It depends on the situation. It would not be very bad if the user is not using it to complete a task. 


1. How could change your interactive system to address this?

Allow only one person into the scene at a time.
  
1. Are there optimizations you can try to do on your sense-making algorithm.

Train the AI on more images/data of different people, bottles and poses. 

We want to create a system that classifies geese and cats. This is a good system for the cat shelter where there are so many geese and ducks. It might not be a good environment where there are a lot of animals and no goose or cats. 


### Part 2.

Following exploration and reflection from Part 1, finish building your interactive system, and demonstrate it in use with a video.

Continuing from last week, we build a Cat or Goose detector. This can be placed at the cat sanctuary on the Island. When a cat approaches, the device plays a cat sound. When a goose approaches the device plays a cat sound. 

Link to our video: https://youtu.be/16cqiLQ8eG8


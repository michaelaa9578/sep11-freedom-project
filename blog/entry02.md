# Entry 2
##### 12/18/24

### Content

I wanted to move on from tinkering with the model of a scene for a bit to focus more so on the scene itself:

* These are some of the components I added my separate values:

###### Sky Scene
```JS
const skybox = BABYLON.MeshBuilder.CreateBox("skyBox", { size: 100.0 }, scene);
const skyboxMaterial = new BABYLON.StandardMaterial("skyBox", scene);
skyboxMaterial.backFaceCulling = false;
skyboxMaterial.disableLighting = true;
skybox.material = skyboxMaterial;
```

*With this body of code, I'm able to install a sky type sandbox with varying size. This type of scene code is significant in creating a foundation  for my future freedom project. This would bring together my various code within the sanbox to formulate a unison model. I was able to create other scenes

###

##### Realizations

* Components like light intensity and model positions, for example, are similar in function to the components I used in my tool from last year's freedom project, which helped me better familiarize this tool because both tools use similar code to display variables.

* The components that I tinkered with (light intensity, position, etc.) helped me visualize functions and their outputs. When seeing any code relating to positioning a variable, I can picture moving around a certain shape within a parameter.

###### Over the course of the following week, I continued to research and test out functions in Babylon and in my IDE. I planned to create my own brief model consisting of these functions and the ones I have already tinkered with.

* I used [Babylon's Node Material Editor](https://nme.babylonjs.com/) to gain a more complex idea of modeling in Babylon. These aee some of the components I added my separate values into:

###### Color

<img width="1588" alt="Screenshot 2024-10-28 at 6 17 25 AM" src="https://github.com/user-attachments/assets/9124a46e-e9c8-40dc-9413-d909bea6b9e1">


Changing the colors helped me get familiar with the editor as a whole as I was able to practice connecting the color blocks to the variable blocks which was a key mechanism in executing any other general function within the program.

###### Shape

<img width="298" alt="Screenshot 2024-10-28 at 6 47 45 AM" src="https://github.com/user-attachments/assets/c9109e34-a4c4-4248-bdd7-c4d9bb091b06">
<img width="292" alt="Screenshot 2024-10-28 at 6 47 27 AM" src="https://github.com/user-attachments/assets/79699b6d-72e1-4e0a-bbcc-a764b6215a26">
<img width="304" alt="Screenshot 2024-10-28 at 6 47 13 AM" src="https://github.com/user-attachments/assets/d52f9933-4680-4d9e-ae1c-fa8b00ec96e6">

The simple act of switching through the different builds helped me visualize different potential model prototypes for my medical simulation. Although I didn't have any success attaching specific color properties to the models, seeing the different properties and their sub-properties also aided me in visualizing potential model types for my final simulation.

##### Further Realizations

* Even attempting the simplest functions was difficult for me, hence, I couldn't successfully add other properties like gradience, for example, to my color variables.

* I noticed that the Node Material editor added functions and properties more visually through connective blocks.

### Summary

I mostly tinkered with code revolving around the subject. This code generally included measurments and positioning. I was essentially managing the scenery and environment in which my project would be laid out on. I feel that this is a sufficient beginning to learning my tool in that I'm now able to create a foundation for my freedom project (which a signifcant part of it will deal with scenery).

### Engineering Design Process

I have moved on to the fourth step of the engineering design process which means that I'm organizing my information to devise solutions to my given problem in step 1 (brainstorming). I have already brainstormed possible solutions which means that I have to plan the most efficient solution. During this part of the project, I begin to execute information which I have found through brainstorming. By testing these ideas, I'll be able to better structure a final solution to my topic of medicine by seeing which body of code is most effective. Once I complete testing out different code, I plan to create a prototype using my tool (step 5).

### Skills

One skill I was able to work on throughout this stage of the project was paying attention to detail. Having to pick a particular tool out of a wide variety of other tools required having to rule out certain aspects in my plan. For example, when looking through Tailwind (a tool), I had to focus on the type of code which was being utilized to gather an overall idea of the tool. Eventually, I realized that Tailwind, as I mentioned in my content, focused more so on organization rather than model designing which I happen to be more interested in and which Aframe (my chosen tool) was more involved with. Focusing on smaller components helped me in other situations outside of those in SEP. When I first started babysitting for my niece, I was solely focused on playing with her and making her happy, which even though her happiness is just as important, I should have also been focused on the smaller tasks such as regulalry cleaning her bowls, observing her sleep schedule, looking for any abnormal behaviors, etc. These smaller tasks make up for her overall development which I eventually realized in the midst of tinkering. Through tinkering, I'm now able to efficiently care for my niece resulting in her being both happy and healthy.

### Reflection

I look forward to continue finding new potential solutions even with an existing primary solution to ensure the continuation of medicine.

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)

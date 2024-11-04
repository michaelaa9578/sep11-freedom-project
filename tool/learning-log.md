# Tool Learning Log

## Tool: **Babylon**

## Project: **Medical Technology Simulation**

---

### 10/21/24:

##### Links you used today (websites, videos, etc)

* I used [Babylon's playground feature](https://playground.babylonjs.com/) to get a brief idea of a model of Babylon.

##### Things you tried, progress you made, etc

* I wanted to begin tinkering with the background of the given model as well as the model itself in the link and change factors like light intensity, variable diameters, and general variable shapes to see what each function did.

* These are some of the components I added my separate values:

###### Model Diameter

```JS
<var sphere = BABYLON.MeshBuilder.CreateSphere("sphere", {diameter: 6, segments: 32}, scene);
```

###### Model Position

```JS
sphere.position.y = 5;
```

###### Camera Position

```JS
var camera = new BABYLON.FreeCamera("camera1", new BABYLON.Vector3(0, -10, -10), scene);
```

###### Light intensity of the Model

```JS
light.intensity = 5;
```

* With these particular values, I was able to change the initial position of the model to be higher within the parameters, the shape to be larger, and the color to be lighter.

##### Challenges, a-ha moments, etc

* Components like light intensity and model positions, for example, are similar in function to the components I used in my tool from last year's freedom project, which helped me better familiarize this tool because both tools use similar code to display variables.

* The components that I tinkered with (light intensity, position, etc.) helped me visualize functions and their outputs. When seeing any code relating to positioning a variable, I can picture moving around a certain shape within a parameter.

##### Questions you still have

* What other foundational functions are there to display a model?

##### What you're going to try next

* Over the course of the upcoming week, I'm going to continue to research and test out functions in Babylon and in my IDE. I'll create my own brief model consisting of these functions and the ones I have already tinkered with.

### 10/24/24:

##### Links you used today (websites, videos, etc)

* I used [Babylon's Node Material Editor](https://nme.babylonjs.com/) to gain a more complex idea of modeling in Babylon.

##### Things you tried, progress you made, etc

* I tried tinkering with Babylon Node Material Editor. Although I could only partially figure out the entire editor, the mechanism was similar to code.org, where you had to piece together certain pieces of code in a puzzle format. I attached inputs like the color block, which outputs a fragment block of the color that I input, essentially changing the color of my variables. I ended up simply making a colored square shape within a colored background. In previous classes, I tinkered with the position of the variables where I changed the altitude and camera position of my variables by altering x, y, and z dimensions.

* These are some of the components I added my separate values into:

###### Color

PictureXXX

Changing the colors helped me get familiar with the editor as a whole as I was able to practice connecting the color blocks to the variable blocks which was a key mechanism in executing any other general function within the program.

###### Shape

PictureXXX

The simple act of switching through the different builds helped me visualize different potential model prototypes for my medical simulation. Although I didn't have any success attaching specific color properties to the models, seeing the different properties and their sub-properties also aided me in visualizing potential model types for my final simulation.

##### Challenges, a-ha moments, etc

* Even attempting the simplest functions was difficult for me, hence, I couldn't successfully add other properties like gradience, for example, to my color variables.

* I noticed that the Node Material editor added functions and properties more visually through connective blocks.

##### Questions you still have

* Are there other methods of displaying code?

##### What you're going to try next

* I'm going to continue to tinker with the Node editor to further test my success with understanding the various blocks and functions for the remaining week. After that, I'll go back to tinkering with regular typed-out code and exploring the different functions through that. I'll most likely leave out the editor in the process of doing my final project because of my lackibg understanding of the mechanism but it helped me get familiar with certain properties which is why I'll keep it in mind.

### 10/24/24:

##### Links you used today (websites, videos, etc)

* I used [Babylon's Node Material Editor](https://nme.babylonjs.com/) to gain a more complex idea of modeling in Babylon.

##### Things you tried, progress you made, etc

* I tried tinkering with Babylon Node Material Editor. Although I could only partially figure out the entire editor, the mechanism was similar to code.org, where you had to piece together certain pieces of code in a puzzle format. I attached inputs like the color block, which outputs a fragment block of the color that I input, essentially changing the color of my variables. I ended up simply making a colored square shape within a colored background. In previous classes, I tinkered with the position of the variables where I changed the altitude and camera position of my variables by altering x, y, and z dimensions.

* These are some of the components I added my separate values into:

###### Color

PictureXXX

Changing the colors helped me get familiar with the editor as a whole as I was able to practice connecting the color blocks to the variable blocks which was a key mechanism in executing any other general function within the program.

###### Shape

PictureXXX

The simple act of switching through the different builds helped me visualize different potential model prototypes for my medical simulation. Although I didn't have any success attaching specific color properties to the models, seeing the different properties and their sub-properties also aided me in visualizing potential model types for my final simulation.

##### Challenges, a-ha moments, etc

* Even attempting the simplest functions was difficult for me, hence, I couldn't successfully add other properties like gradience, for example, to my color variables.

* I noticed that the Node Material editor added functions and properties more visually through connective blocks.

##### Questions you still have

* Are there other methods of displaying code?

##### What you're going to try next

* I'm going to continue to tinker with the Node editor to further test my success with understanding the various blocks and functions for the remaining week. After that, I'll go back to tinkering with regular typed-out code and exploring the different functions through that. I'll most likely leave out the editor in the process of doing my final project because of my lackibg understanding of the mechanism but it helped me get familiar with certain properties which is why I'll keep it in mind.


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

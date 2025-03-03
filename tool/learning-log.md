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

<img width="1588" alt="Screenshot 2024-10-28 at 6 17 25 AM" src="https://github.com/user-attachments/assets/9124a46e-e9c8-40dc-9413-d909bea6b9e1">


Changing the colors helped me get familiar with the editor as a whole as I was able to practice connecting the color blocks to the variable blocks which was a key mechanism in executing any other general function within the program.

###### Shape

<img width="298" alt="Screenshot 2024-10-28 at 6 47 45 AM" src="https://github.com/user-attachments/assets/c9109e34-a4c4-4248-bdd7-c4d9bb091b06">
<img width="292" alt="Screenshot 2024-10-28 at 6 47 27 AM" src="https://github.com/user-attachments/assets/79699b6d-72e1-4e0a-bbcc-a764b6215a26">
<img width="304" alt="Screenshot 2024-10-28 at 6 47 13 AM" src="https://github.com/user-attachments/assets/d52f9933-4680-4d9e-ae1c-fa8b00ec96e6">

The simple act of switching through the different builds helped me visualize different potential model prototypes for my medical simulation. Although I didn't have any success attaching specific color properties to the models, seeing the different properties and their sub-properties also aided me in visualizing potential model types for my final simulation.

##### Challenges, a-ha moments, etc

* Even attempting the simplest functions was difficult for me, hence, I couldn't successfully add other properties like gradience, for example, to my color variables.

* I noticed that the Node Material editor added functions and properties more visually through connective blocks.

##### Questions you still have

* Are there other methods of displaying code?

##### What you're going to try next

* I'm going to continue to tinker with the Node editor to further test my success with understanding the various blocks and functions for the remaining week. After that, I'll go back to tinkering with regular typed-out code and exploring the different functions through that. I'll most likely leave out the editor in the process of doing my final project because of my lackibg understanding of the mechanism but it helped me get familiar with certain properties which is why I'll keep it in mind.

### 11/12/24:

##### Links you used today (websites, videos, etc)

* I looked through various [Babylon demo projects](https://www.babylonjs.com/community/) to gain insight into the specific models I want for my freedom project.

##### Things you tried, progress you made, etc

* I tested out numerous demos throughout the week to help me decide on the final layout of my project. I focused on things like the camera movement, function, subject of the demo, and the background.

* These are some of the findings I've compiled based on the different demos:

###### Visam 3D Hub

<img width="834" alt="Screenshot 2024-11-12 at 7 08 51 AM" src="https://github.com/user-attachments/assets/9d68324b-38f4-433d-8149-213606f80974">
<img width="882" alt="Screenshot 2024-11-12 at 7 09 13 AM" src="https://github.com/user-attachments/assets/31c2b68c-75bd-449d-aabe-6e6fb0af2ea8">



Through moving around the camera, I discovered the sole functionality of the demo was to observe the subject, seemingly a custom 3D model. This is ultimately the type of functionality I want to set on for my final project in which I incorporate various models with the purpose of analyzing them. The only things I would've changed would have been the camera movement in which I would have added the ability to free movement throughout the sandbox instead of staying in a fixed position. That means that I still have to look for a project that uses a similar type of camera movement to the one I'm looking to establish if I want to include that feature.

###### Retail

<img width="978" alt="Screenshot 2024-11-12 at 7 10 01 AM" src="https://github.com/user-attachments/assets/5273d452-3a4c-43e3-8cb2-f176023f7ae1">
<img width="978" alt="Screenshot 2024-11-12 at 7 10 24 AM" src="https://github.com/user-attachments/assets/0912425c-0f5b-42b2-b810-8cbf02f6ba67">


This demo uses the type of camera movement I want for my final project in which it freely moves throughout the sandbox. Although, the project is more simulation based rather than an observatory model where the purpose of the project is to display one or multiple subjects. To use this as a foundation would mean that I would have to switch out the entire concept of the project being that I only find the camera movement to my interest.

##### Challenges, a-ha moments, etc

* I tested out other demos as well, although, I've found these two projects to contain the key factors I wanted to include in my person project and hence, I acknowledged that my primary focus was on their given sets of features that included free movement of the camera and the particular presentation of a subject.

* By being able to confirm these key points of the basis of my freedom project, I now have a better layout plan for my incorporation of the Babylon tool.

##### Questions you still have

* What factors are there to consider outside the camera movements, subject presentation, genre, etc.?

##### What you're going to try next

* I'm going to compile sets of code that match up to the free camera movement and subject display represented in these models so that I can try to create a protoype which combines both of these features being that I wasn't able to find one that completely aligned with my vision.

### 12/20/24:

##### Links you used today (websites, videos, etc)

* I looked through various [Babylon demo projects](https://www.babylonjs.com/community/) to gain insight into the specific models I want for my freedom project.

##### Things you tried, progress you made, etc

* I tested out numerous demos throughout the week to help me decide on the final layout of my project. I focused on things like the camera movement, function, subject of the demo, and the background.

* These are some of the findings I've compiled based on the different demos:

###### Visam 3D Hub

<img width="834" alt="Screenshot 2024-11-12 at 7 08 51 AM" src="https://github.com/user-attachments/assets/9d68324b-38f4-433d-8149-213606f80974">
<img width="882" alt="Screenshot 2024-11-12 at 7 09 13 AM" src="https://github.com/user-attachments/assets/31c2b68c-75bd-449d-aabe-6e6fb0af2ea8">



Through moving around the camera, I discovered the sole functionality of the demo was to observe the subject, seemingly a custom 3D model. This is ultimately the type of functionality I want to set on for my final project in which I incorporate various models with the purpose of analyzing them. The only things I would've changed would have been the camera movement in which I would have added the ability to free movement throughout the sandbox instead of staying in a fixed position. That means that I still have to look for a project that uses a similar type of camera movement to the one I'm looking to establish if I want to include that feature.

###### Retail

<img width="978" alt="Screenshot 2024-11-12 at 7 10 01 AM" src="https://github.com/user-attachments/assets/5273d452-3a4c-43e3-8cb2-f176023f7ae1">
<img width="978" alt="Screenshot 2024-11-12 at 7 10 24 AM" src="https://github.com/user-attachments/assets/0912425c-0f5b-42b2-b810-8cbf02f6ba67">


This demo uses the type of camera movement I want for my final project in which it freely moves throughout the sandbox. Although, the project is more simulation based rather than an observatory model where the purpose of the project is to display one or multiple subjects. To use this as a foundation would mean that I would have to switch out the entire concept of the project being that I only find the camera movement to my interest.

##### Challenges, a-ha moments, etc

* I tested out other demos as well, although, I've found these two projects to contain the key factors I wanted to include in my person project and hence, I acknowledged that my primary focus was on their given sets of features that included free movement of the camera and the particular presentation of a subject.

* By being able to confirm these key points of the basis of my freedom project, I now have a better layout plan for my incorporation of the Babylon tool.

##### Questions you still have

* What factors are there to consider outside the camera movements, subject presentation, genre, etc.?

##### What you're going to try next

* I'm going to compile sets of code that match up to the free camera movement and subject display represented in these models so that I can try to create a protoype which combines both of these features being that I wasn't able to find one that completely aligned with my vision.

1/13/25:

##### Links you used today (websites, videos, etc)

* I used [Babylon's Node Material Editor](https://nme.babylonjs.com/) again to gain a more thorough idea of modeling in Babylon.

##### Things you tried, progress you made, etc

* I tried tinkering with JS code that revolved around shaping which I could later link with the Babylon editor and compile the codes.

###### Shape

``` Js
function setup() {
  createCanvas(500, 500);
  background(200);
}
```
Here I called angleMode() in setup() which allowed me to use degrees to draw the perimeter of all arcs in the given scene. This code seems fairly explanatory to me as it uses a function, a topic I'm familiar with from class and parameters, another concept I'm somewhat familiar with. I inputted various colored shapes in the attachment to this body of code to create a canvas of shapes.

```Js
unction draw() {
 fill("lightBlue");
 rect(20, 20, 35, 37);

 fill("yellow");
 rect(20, 100, 35, 70);
}
```

##### Challenges, a-ha moments, etc

* I had trouble manipulating the overall canvas as I was unable to accommodate certain shapes with other shapes to create a specific visual. I need to reflect on this issue as it will hugely pertain to my final project.

##### Questions you still have

* Is this process similar with 3D shapes?

##### What you're going to try next

* I'm going to continue to tinker with these fill-in shapes and try to successfully create a coordinated ending visual to be able to get an idea for my freedom project because, again, creating a coordinated visual is significant in my final project.

3/3/25:

##### Links you used today (websites, videos, etc)

* I used [Babylon.js](https://nme.babylonjs.com/) to browse through more demos and examples.

##### Things you tried, progress you made, etc

* I tried tinkering more with the scenes of a subject rather than the subject itself to begin working on the foundation of my freedom project.

``` JS
const createScene = function () {
    // Creates object
    const scene = new BABYLON.Scene(engine);
    // Creates and positions a camera
    const camera = new BABYLON.FreeCamera("camera1",
        new BABYLON.Vector3(0, 5, -10),
        scene);
    // Creates light
    const light = new BABYLON.HemisphericLight("light",
        new BABYLON.Vector3(0, 1, 0),
        scene);
    // Creates 'sphere' shape.
    const sphere = BABYLON.MeshBuilder.CreateSphere("sphere",
        {diameter: 2, segments: 32},
        scene);
    // Move sphere upward 1/2 its height
    sphere.position.y = 1;
    // Built-in 'ground' shape.
    const ground = BABYLON.MeshBuilder.CreateGround("ground",
        {width: 6, height: 6},
        scene);
    return scene;
};
```
Here I combined a few of the scene sub-topics I have tinkered with before and conjoined them to create a basic prototype. I conjoined topics including light, positioning, inputting width and height, etc.

##### Challenges, a-ha moments, etc

* I didn't know what the necessary parts were to include within the scene until I looked back at the demos and their assigned code in which I noticed that most of them were made up of positioning and installations of objects.

##### Questions you still have

* How can I diversify the installed objects? Are there different versions of an object I can install?

##### What you're going to try next

* I'm going to continue to tinker with these basic scenes and try to add more concepts within them to complexify them.

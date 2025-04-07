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

3/10/25:

##### Links you used today (websites, videos, etc)

* I used [p5js.org/](https://p5js.org/) to browse through more test code.

##### Things you tried, progress you made, etc

* I tried tinkering with the given refrence 3D models to be able to later implement into my freedom project when creating the 3D medical simulation. Below is one of the refrence models I utilized:

``` JS
const octahedron_model = `
v 0.000000E+00 0.000000E+00 40.0000
v 22.5000 22.5000 0.000000E+00
v 22.5000 -22.5000 0.000000E+00
v -22.5000 -22.5000 0.000000E+00
v -22.5000 22.5000 0.000000E+00
v 0.000000E+00 0.000000E+00 -40.0000
f     1 2 3
f     1 3 4
f     1 4 5
f     1 5 2
f     6 5 4
f     6 4 3
f     6 3 2
f     6 2 5
`;
//draw a spinning octahedron
let octahedron;

function setup() {
  createCanvas(100, 100, WEBGL);
  octahedron = createModel(octahedron_model, '.obj');
  describe('Vertically rotating 3D octahedron.');
}

function draw() {
  background(200);
  rotateX(frameCount * 0.01);
  rotateY(frameCount * 0.01);
  model(octahedron);
}
```
Here, I observed that the first half of the code (before the commented line) creates the octrahedral shape by using x, y, and z coordinate numbers. In the second half of our code (below the commented line), functions like `rotateX(frameCount * 0.01)` and `rotateY(frameCount * 0.01)` apply rotation to the octahedron.

##### Challenges, a-ha moments, etc

* I was surprised that you could apply animation to 3D models using simple functions. Before testing the octahedron code out, I assumed that the code would just display the shape rather than a visible canvas and rotating aspect until I further inspected the attached functions which allowed those factors to coexist with the model.

* The coordinates to apply the shape to the canvas using a lot more numbers than I anticipated. I thought that that portion of the code would only use three numbers maximum consisting of x, y, and z. I'm assuming that the multiple numbers account for multiple vertices of the 3D octahedral.

##### Questions you still have

* What other functions can coexist with a 3D model within a canvas?

* What do the various numbers account for?

##### What you're going to try next

* I'm going to continue to tinker with p5js.org to grasp a better idea of 3D models so that I'm able to include them in my future medical simulation.

3/24/25

##### Links you used today (websites, videos, etc)

* I used [babylon.js](https://www.babylonjs.com/featureDemos/) to browse through demo code.

##### Things you tried, progress you made, etc

* I tried tinkering with the more given refrence 3D models to be able to later implement into my medical simulation for my freedom project. Here is one of the models I tinkered with:

``` JS
        var mv = new BABYLON.Vector3(Math.cos(time * 0.1) * Math.cos(time * 0.17) * 0.09,
            Math.sin(time * 0.08) *0.1+ Math.cos(time * 0.12) * 0.15,
            0);
            bodyTransform.position = mv;

        skinRoot.position.copyFrom(handleTransform.position);
        skinRoot.position.addInPlace(mv);
        skinRoot.rotationQuaternion = handleTransform.rotationQuaternion;

        for(let j = 0;j<tentacles.length;j++)
        {
            let boxes = tentacles[j];
            const curlyFactor = Math.cos(j *16789.287 + time * 0.0571);
            for(let i = 0;i<boxes.length -1;i++)
            {
                constrain(curlyFactor, i, boxes[i], boxes[i+1], idealLength);
            }
            var angle = j * Math.PI * 0.25;
            boxes[0].rotationQuaternion = BABYLON.Quaternion.FromEulerAngles(0.8 + Math.cos(j*4.8 + time*0.1) * 0.2, angle, 0);

        }
```
Here, I observed an animation being set for a moving octopus. Although I didn't understand a majority of this code at first, I learned that it is greatly similar to a lot of the p5js methods we learned being that the code utilizes concepts like operators with variables (just like using operators with x and y coordinates to manipulate a moving mouse). The code also used a lot of other unrelated p5js methods including math functions and for loops.

##### Challenges, a-ha moments, etc

* Realizing that the animation code is used primarily for loops and math functions, I know now that I will use the following methods when creating animation for my simulation as those methods can create the moving, animated features within the models.

* I still struggle to fully understand the methods used despite having learned their basic functions. For example, I'll have to further research the code to comprehend what `Math.PI` and `Math.cos` is.

* A lot of the code also consists of downloading Babylon meshes which means that I have to learn to execute that particular action to expose detailed animation in my medical simulation. But I'd consider this a beyond MVP feature.

##### Questions you still have

* What other code methods can I input into animation code besides math functions and p5js variables?

##### What you're going to try next

* I'm going to try to combine p5js variables with Babylon ones to try to create functional code.

4/01/25

* I tried tinkering with given reference 3D models to be able to stitch them into a Babylon scene. Here is one of the models and scenes I tinkered with:

``` JS
    var ctx = scene.getMeshByName("plane").material.diffuseTexture.getContext();
    ctx.clearRect(0, 0, 0, 0); // Clear the previous frame
    ctx.fillText(frameCount, 0, 0); // Update the text with the current frame count
    engine.resize(); // Resize the engine
    scene.render(); // Render the scene
```
Here, I tried to implement a frame count into my Babylon scene. I had to convert my initial o5js code which was:

``` JS
    function setup() {
    createCanvas(100, 100);
    background(200);
    textSize(30);
    textAlign(CENTER, CENTER);
    text(frameCount, 50, 50);
    }
```

In my converted code, I had to begin to loop a function to be able to update the dynamic texture with the current frame count.

##### Challenges, a-ha moments, etc

* I didn't initially know that I had to convert my code for it to be compatible with Babylon.

* I still struggle to fully understand the methods used despite having learned their basic functions. For example, I'll have to further research the code to comprehend what `.material.diffuseTexture` and `.getContext` is.

* A lot of the code is seemingly similar to the unconverted code which indicates to me that the only difference I have to recognize is how elements are being written out.

##### Questions you still have

* How can I convert other coding elements into Babylon using what Babylon functions?

##### What you're going to try next

* I'm going to further experiment with converting p5js elements into Babylon.

04/07/25

* I browsed through and touched on a few potential 3D models I can incorporate into my medical simulation.

``` JS
        const box = BABYLON.Mesh.CreateBox("box", 2, scene);
        box.rotation.x = -0.2;
        box.rotation.y = -0.4;

        const torus = BABYLON.Mesh.CreateTorus("torus", 2, 0.5, 15, scene);
        torus.position.x = -5;
        torus.rotation.x = 1.5;

        const torusMaterial = new BABYLON.StandardMaterial("material", scene);
        torusMaterial.emissiveColor = new BABYLON.Color3(0.4, 0.4, 0.4);
        torus.material = torusMaterial;

        const cylinder = BABYLON.Mesh.CreateCylinder("cylinder", 2, 2, 2, 12, 1, scene);
        cylinder.position.x = 5;
        cylinder.rotation.x = -0.2;
```

alt="models.png" src="models.png">

Here, I compiled certain 3D shapes I found throughout the Babylon website to try to visualize my 3D medical gallery and gain inspiration from it.

##### Challenges, a-ha moments, etc

* I observed more relations between p5js and the given code including the operators with shape variables. I changed the values of the numbers, and I noticed that the two aspects also functioned the same: the speed of the rotations would either slow down or speed up.

* I also observed similar code we recently learned when applying functions, essentially teaching the computer how to draw certain functions. Example: `function drawBody(x, y, w, h)` is similar to `BABYLON.Mesh.CreateCylinder("cylinder", 2, 2, 2, 12, 1, scene);`.

##### Questions you still have

* What other ways can I alter the involved animation other than changing the speed of the linked variables?

##### What you're going to try next

* I'm going to continue to tinker with more 3D model variants.

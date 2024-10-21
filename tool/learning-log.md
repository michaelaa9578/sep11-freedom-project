# Tool Learning Log

## Tool: **Babylon**

## Project: **Medical Technology Simulation**

---

### 10/21/24:

##### Links you used today (websites, videos, etc)

* I used (Babylon's playground feature)[https://playground.babylonjs.com/] to get a brief idea of a model of Babylon.

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

### X/X/XX:
* Text


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

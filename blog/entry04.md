# Entry 4
##### 3/17/25

### Content

##### Part 1

Throughout this portion of my learning, I tried to tinker more with the scenes of a subject rather than the subject itself to begin working on the foundation of my freedom project.


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
Analysis: Here I combined a few of the scene sub-topics I have tinkered with before and conjoined them to create a basic prototype. I conjoined topics including light, positioning, inputting width and height, etc. Challenges I faced with the foundational factors of my scene is that I didn't know what the necessary parts were to include within the scene until I looked back at the demos and their assigned code in which I noticed that most of them were made up of positioning and installations of objects. With this information in consideration, I was planning to then continue to tinker with these basic scenes and try to add more concepts within them to complexify them.

##### Part 2

Alongside conjoining components including light, positioning, inputting width and height, etc. to create a basic prototype of foundational objects, I also practiced using [p5js.org/](https://p5js.org/) to incorporate more Javascript factors into the foundation of my freedom project. To start this off, I tried tinkering with the given reference 3D models to be able to later implement into my freedom project when creating the 3D medical simulation. Below is one of the reference models I utilized:


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
Analysis: Here, I observed that the first half of the code (before the commented line) creates the octahedral shape by using x, y, and z coordinate numbers. In the second half of our code (below the commented line), functions like `rotateX(frameCount * 0.01)` and `rotateY(frameCount * 0.01)` apply rotation to the octahedron. I was surprised that you could apply animation to 3D models using simple functions. Before testing the octahedron code out, I assumed that the code would just display the shape rather than a visible canvas and rotating aspect until I further inspected the attached functions which allowed those factors to coexist with the model. Additionally, the coordinates to apply the shape to the canvas using a lot more numbers than I anticipated. I thought that that portion of the code would only use three numbers maximum consisting of x, y, and z. I'm assuming that the multiple numbers account for multiple vertices of the 3D octahedral. With these observations, my next steps consisted of continuing to tinker with p5js.org to grasp a better idea of 3D models so that I'm able to include them in my future medical simulation.

### Summary

I'm continuing to manage the scenery and environment in which my project would be laid out. Tinkering with the fundamental subject is a sufficient beginning to learning my tool in that I'm able to create a foundation for my freedom project. A new element of this process of managing my environment was learning the visual aspect of Javascript. I used these newly learned elements including 3D shapes and basic concepts like text, color, and fonts to generally transition the learning of my tool to a further visual level of processing.

### Engineering Design Process

I'm beginning the fourth step of the engineering design process which means that I'm slowly beginning to plan and test the most promising solution to my given problem in step 1 (brainstorming). At this point in time, I have the resources of Javascript alongside plug in scenes from Babylon (my tool) which I can combine to create an optimized and precise model pertaining to medical technology. If I continue to utilize my skill of correlating, as I've established in my previous blog, I can correlate  these aspects into eventually creating a functional prototype (step 5). Before I get to that step, however, I still want to continue to practice using more `p5js` methods.

### Skills

One skill I was able to work on throughout this stage of the project was googling. Although I had notes of the various Javascript components organized and written down, it was hard to find out which components specifically were best to apply in certain situations. I used google to narrow down my options. Specifically I used websites like W3Schools and P5Js.org to research specific `p5js` aspects like the functions of shapes, stroke, fonts, text, etc. I executed the skill of googling in my other classes, especially in history. I am currently participating in a mock jury trial in which I have a significant amount of evidence I have to organize and digest. I used google to separate evidence into certain sections (pros and cons). This has helped me  factor out the key points in my discussion and help me defend my side efficiently with being able to share relevant information to the given topic. Another skill I was able to work on throughout this stage of the project was reading properly. This was an adjacent skill to googling being that when I had to google something, I had to make sure I was correctly interpreting the provided information. While reading through the various functions of `p5js`, I made sure to re-read the functions multiple times to enhance and confirm my understanding of those functions. This skill not only helped me better understand `p5js` functionality but it also helped me in English class as we read multiple articles everyday. With better reading, I was able to identify key components of these articles including the subject, occasion, audience, and purpose to synthesize a clear and opinionated conclusion on what I read.

### Reflection

I look forward to putting a lot of my existing information together to begin a working prototype of my freedom project.


[Previous](entry03.md) | [Next](entry05.md)


[Home](../README.md)

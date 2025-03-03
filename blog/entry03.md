# Entry 3
##### 2/15/25

### Content


I wanted to move on from tinkering with the model of a subject for a bit to focus more so on the scene itself:


* These are some of the components I tinkered with:


###### Sky Scene
```JS
const skybox = BABYLON.MeshBuilder.CreateBox("skyBox", { size: 50.0 }, scene);
const skyboxMaterial = new BABYLON.StandardMaterial("skyBox", scene);
skyboxMaterial.backFaceCulling = false;
skyboxMaterial.disableLighting = true;
skybox.material = skyboxMaterial;
```


*With this body of code, I'm able to install a sky type sandbox with varying size. This type of scene code is significant in creating a foundation  for my future freedom project. This would bring together my various code within the sandbox to formulate a unison model. I was able to create other scenes besides the sky variant.


```Js
var createScene = function () {
   var scene = new BABYLON.Scene();
   // Positions a free camera
   var camera = new BABYLON.ArcRotateCamera("camera1", 0,  Math.PI / 2, 10, BABYLON.Vector3.Zero(), scene);
```
Here, I'm also able to install a a differing sandbox with an added free camera so that the scene is interactive.


##### Javascript Components


Alongside tinkering with the simulation itself, I also wanted to begin to plan out my project's overall layout so that both factors are able to functionally coexist.


* These are a few of the javascript components I tinkered with:


<li> CSS <li>


```JS
.style.backgroundColor
```
My initial thought process: Using this syntax: `.style(backgroundColor)
Realizations: I was getting confused with the syntax of query selectors in which you utilize parentheses. However, styling the background would require just periods as we're indicating the class.


<li> HTML <li>


```JS
.querySelectorAll()
```


My initial thought process: Suggested the idea of selecting all elements with the same id
Realizations: Suggests selecting all elements of the same type or class


##### Realizations


* In terms of scenery, I've learned about camera positioning which will be a key factor to making the scene within my simulation interactive. I also know what goes into making a basic scene.


* In terms of Javascript, I was able to learn about DOM (Document Object Model) and utilize its factors into manipulating CSS and HTML. Although, I struggled with correlating the right syntax to the given method.


### Summary


When I first started tinkering, I mostly tinkered with code revolving around the subject itself. This code generally included measurments and positioning. I want to now start managing the scenery and environment in which my project would be laid out. Tinkering with the fundamental subject is a sufficient beginning to learning my tool in that I'm able to create a foundation for my freedom project. However, the transition from the foundation to the subordinate factors which include subjects surrounding the main subject alongside the entirety of the sandbox would help tie everything together and create a smooth conjecture of parts in my final simulation.


### Engineering Design Process


I'm still currently on the fourth step of the engineering design process which means that I'm organizing my information to devise solutions to my given problem in step 1 (brainstorming). At this point in time, I have medical models from last year's freedom project alongside new coding methods I acquired this year. If I continue to utilize my skill of correlating, I can correlate both of these aspects into eventually creating a functional prototype (step 5). Before I get to that step, however, I still want to continue to practice using more DOM methods.


### Skills


One skill I was able to work on throughout this stage of the project was on making connections. When practicing to manipulate HTML and CSS using DOM, I had to type out certain syntax which linked to a certain DOM method. Practicing this skill is reflected in my daily life, particularly in school. When transitioning into a new lesson in geometry relating to finding volumes of 3 dimensional shapes, I would use the given formulas and mindlessly plug in values to those formulas. As I was forced to understand the results of certain code while tinkering with DOM, I began to question what I was plugging into my formulas and how these plug-ins affected the product of that formula in geometry. Overall, I understood the consequences better in both classes as a result of questioning the results. Consequently, another skill I'm improving in is my ability to understand context. In order to understand the connection between formulas for geometric shapes and values within those formulas, I had to utilize what I already knew alongside connecting those existing ideas. Without prior knowledge, I wouldn't have been able to understand why I was using the values I was using. This same idea applied under the circumstance of coding. I wouldn't have known how to connect `.querySelectorAll()`, for example, to any general coding challenge without knowing its function firsthand.


### Reflection


I look forward to putting a lot of my existing information together to begin visualizing a vague prototype of my freedom project.


[Previous](entry02.md) | [Next](entry04.md)


[Home](../README.md)

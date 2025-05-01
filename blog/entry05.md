# Entry 5
##### 5/1/25

### Content

##### Finishing MVP

Working on the actual simulation of my project has generally taught me the most out of my entire learning path linked with my tool, the SEP course, etc. Although I've made past prototypes to work up to this moment of the year, I haven't actually had a steady flow of concurrent ideas to make an entire functioning simulation utilizing the skills I've learned throughout the year. Alongside utilizing skills I have already leared throughout this course, I had to adopt an entire new set of ideas throughout this project being that my tool was a whole new system from course lesson including p5js, basic html and css, etc. This included coding concepts such as:

###### Babylon Types

``` JS
function createBase(parent, { height, width, depth }, position) {
        const base = BABYLON.MeshBuilder.CreateBox("base", { height, width, depth }, scene);
        base.material = new BABYLON.StandardMaterial("baseMaterial", scene);
        base.material.diffuseColor = new BABYLON.Color3(0.5, 0.5, 0.5);
        return base;
    }
```
Analysis: As shown, the Babylon mesh builder is a specific Babylon type my project partner and I found associated with the tool in its demos where this babylon class specifically creates a box base with particular dimensions. BABYLON.StandardMaterial is another specific Babylon type we found associated with the tool. This one helped us set the color of the given dimension to a light gray. In this scene alone of my simulation, I was made to use two separate babylon types at once. Although they appeared a lot different in the initial demos I've studied earlier in the year, I was able to grow accustomed to them, especially after we learned p5js elements, which used these very same color and material elements. These functions within Babylon were essentially recycled JavaScript concepts with a twist.

###### Parameters, Arguments, Parents

Although parameters, arguments, and parents are coding concepts I shouldn't have had to re-learn even with my new tool, I realized I wasn't well equipped with these concepts coming into this projectas they made up about 90% of it. Almost every function I created involved either one or all of these elements and the constant repetition has led me to finally fully adopt these concepts.


``` JS
function createComponent(component, parent) {
        switch (component.type) {
            case 'base':
                createBase(parent, component.params, component.position);
                break;
            case 'cylinder':
                createCylinder("cylinder" + Math.random(), component.params.height, component.params.diameter, component.position, parent);
            case 'sphere':
                createSphere("sphere" + Math.random(), component.params.diameter, component.position, parent);
                break;
        }
    }
```
Analysis: In this part of my simulation, I set up components which would be the objects containing types of different shapes in my arrays (cylinder, base, sphere) alongside parameters which would be attached to those components. Meanwhile the parent would hold that component. This process consisitng of all of these properties would be linked to a certain shape of my model meaning that I could refer back to these concepts through their shape. Again, through this process of continous referal, I was able to identify the connection between parameters and certain arguments and their role in functions and whole bodies of code.

### Engineering Design Process

I'm nearing the end of my EDP, where I'm now on the sixth step of the process, and I'm evaluating my prototype. I'm going to review my final prototype, which I've finished creating in step 5 of my EDP, and based on those reviews, I'm going to move on to the seventh step of the process, which includes improving on my prototype. During the current step of my EDP, I hope to gain meaningful insight so that I can surpass my expectations and standards of my project and take it to even higher levels and potentially max out its functionality.

### Skills

One skill I was able to work on throughout this stage of the project was partnership. I've had to rely on my partner for this part of the project the most because we were made to constantly push and pull on our coding web spaces. A lot of merge conflicts interrupted our process to the point where we've harmed our schedule and ended up severely missing certain deadlines. We were able to resolve this by practicing our partnership in other classes. In English, we would peer review each other's work every chance we got and were, as a result, able to observe each other's work methods and perspectives. With this, we returned to our coding project and valued each other's thinking process when considering what roles and parts we would assign to each other to get our simulation done. Another skill that came hand in hand with partnership was communication and contact. To effectively and continuously consider each other's work methods and schedules, we had to incorporate digital communication into our daily schedules. With whatever time we had available, we made sure to have scheduled conversations in which we made sure to listen to each other and reflect upon exchanged ideas instead of arguing or rejecting potential ideas. We put these very same conversational skills to the test during our time working on the Freedom Project and noticed that we weren't stuck on the same steps anymore. Progress went a lot faster.

### Reflection

I look forward to improving my Freedom Project and developing new ideas to add to it.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)

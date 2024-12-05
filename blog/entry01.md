# Entry 1
##### 12/2/24

### Determining my Topic and Tool

I've always pictured myself in the medical field and decided to continue researching the topic further especially considering my involvement with the same topic last year (which serves as valuable insight for my upcoming freedom project). I therefore decided to choose medicine as my leading topic once again to help me further acknowledge the importance of healthcare for me and billions of other people. This topic will help realize the significant impact medicine could have on the world with its reciprocal relationship to technology. Currently, technology is already making a notable and global difference in the medical industry. The article, '[Top 10 Medical Technologies 2022: Innovations In The Medical Field](https://www.techbusinessnews.com.au/top-10-medical-technologies-2022-innovations-in-the-medical-field/)' emphasizes the congruity between technology and medicine by listing the few most commonly utilized innovations used in hospitals including health monitoring devices, genomic sequencing, MRNA technology, robotics, etc. The [National Center for Biotechnology Information](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4048524/#:~:text=The%20new%20technologies%20will%20allow,several%20other%20benefits%20that%20would) offers the prospective future technology can offer regarding the healthcare system. This consists of remote monitoring, medicine administration, medication compliance, and the overall development of more efficient medical concepts. Having chosen a topic I was passionate about, I also had to choose the right tool in which I'll be able to fulfill my vision for the future of medicine. The tool I ended up choosing was [Babylon.js](https://www.babylonjs.com/). The ultimate goal is to visualize the future of potential medical technologies through a simulation. By scrolling through the website and tinkering with several of the tool's models and functions, I learned that it was efficient in visuals and 3D modeling which were significant aspects to forming a simulation.

###### I wanted to begin tinkering with the background of the given model as well as the model itself in the link and change factors like light intensity, variable diameters, and general variable shapes to see what each function did.

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

I mostly tinkered with code revolving around the subject in these and my following learning logs. This code generally included measurments and positioning. I was essentially managing the scenery and environment in which my project would be laid out on. I feel that this is a sufficient beginning to learning my tool in that I'm now able to create a foundation for my freedom project (which a signifcant part of it will deal with scenery).

### Engineering Design Process

I am currently on the first and second steps of the engineering design process. This means I'm defining my topic and conducting research on the given problem in step 1. I have already defined my problem in the research from my last year's freedom project which is the fear of adaptability alongside a new issue of lacking technology in the medical field. While conducting my research last year, I was able to learn that humans biologically often perceive uncertainty as a threat which is why change is feared by many. Technology, particularly electronic, is a very recently developed conception that's gradually taking over the globe. Multiple concerns arise from this rapid evolution (mostly the product of fear). Will AI surpass human beings? Will cybersecurity worsen with time? Is technology more harmful than helpful? Although these questions can't yet be fully answered, I'm left to finish my second step in the engineering design process, which combines research to try to find any answers as well as to solve adaptability's accompanying issue of lacking technology in the medical field. Although there is existing medical technology In the field currently, many health problems are still left unsolved, which could potentially be solved through ameliorated technology. Eventually, once I collect information on the given topics, I'll brainstorm a plan to create possible solutions to my problem, which will be the third step in the engineering design process.

### Skills

One skill I was able to work on throughout this stage of the project was asking questions and general communication. While I was decent in communication in past years of my life, I significantly improved how I asked questions and how often I asked questions. I used to hardly communicate with my peers in my classes, but as I continued to tinker with my tool and reflect in my learning logs, I found myself asking more questions than I asked last year when working on the same project. I also acknowledged that I asked questions more efficiently by not generalizing my questions and asking follow-up questions, which, in turn, helped me receive a more efficient response. Improving upon this skill has helped me improve in other classes, particularly my math class, as my more efficient communication in the class has led me to better prepare for upcoming tests and projects. Another skill I was able to build on was upkeeping with my assignments. I noticed that I was able to turn in more learning logs for my project on time than I was able to last year. Last year, I was unable to effectively organize a schedule for due dates to consider, while now, I'm able to turn in more assignments on time in most of my classes versus last year by prioritizing this practice with the learning logs. Despite the leap, I still frequently miss assignments, which leaves me to set a goal to further reflect on and try to perfect my upkeep in my next blog.

### Reflection

I look forward to continue finding new potential solutions even with an existing primary solution to ensure the continuation of medicine. I also look forward to improving my skill. of managing throughout the rest of my engineering design process.


[Next](entry02.md)

[Home](../README.md)

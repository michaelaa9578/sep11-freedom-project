# Entry 6
##### 5/30/25

### Content

##### Finishing Remaining BMVP (Beyond Minimum Viable Product)

My partner and I finally finished our minimum viable product, though, our product still wasn't up to our intial standards in that the model was evidently, minimally viable.There weren't any attractive features to it and its physicality was generally lacking. We therefore decided to add texture to the model to try to diversify it. 

###### Babylon Types

``` JS
const material = new BABYLON.StandardMaterial("baseMaterial", scene);

  material.emissiveColor = new BABYLON.Color3(0.5, 0.5, 0.5);

  // apply working texture
  material.diffuseTexture = new BABYLON.Texture("metal.jpg", scene);

  base.material = material;
    }
```

![Screenshot 2025-05-30 10 21 19 AM](https://github.com/user-attachments/assets/0a521f8b-7e25-4686-89b4-7967c56cb5d7)

Analysis: In this particular case, we were adjusting the base aspects of our model which we wanted to make appear metal. To do this, we had to first create an image and later refer to that image to be able to apply it to our base. We applied this same process to make our blood spheres grasp a fluid like texture by creating a fluid texture image and later referring it to our sphere variable. 

###### Presenting Our Product

We found many difficulties in trying to plan our presentation to both the class and in the expo. These issues stemmed from mainly miscommunication and the lacking abiloty to find proper connections between our assigned roles.

![Screenshot 2025-05-30 10 25 43 AM](https://github.com/user-attachments/assets/f772aa56-c00b-47a1-968f-eb304b54a3be)

![Screenshot 2025-05-30 10 25 33 AM](https://github.com/user-attachments/assets/42024efa-ca61-4042-aad6-fe4cb04d9d68)

Analysis: Ultimately, we had to clearly communicate to each other our progresss and make clear what role we were committing to. We did this through assigned slides which helped us the most in determining our connections and differences in formulating an overall product. Being able to identify our standpoints helped us to clearly connect our combined efforts throughout this project and tie that progress back to our primarily goal and aspirations.  
### Engineering Design Process

I've reached the end of my EDP, where I'm now on the final step of the process, and I'm communicating my results. I've already shared and will continue to share the final product with my peers for feedback which I can take advantage of for future projects. I plan to utilize this feedback in a general sense where I can apply it during my classes, to my schedule, and to my general life both in and out of school. Feedback I've received so far include COTNINUE









### Skills

One skill I was able to work on throughout this stage of the project was partnership. I've had to rely on my partner for this part of the project the most because we were made to constantly push and pull on our coding web spaces. A lot of merge conflicts interrupted our process to the point where we've harmed our schedule and ended up severely missing certain deadlines. We were able to resolve this by practicing our partnership in other classes. In English, we would peer review each other's work every chance we got and were, as a result, able to observe each other's work methods and perspectives. With this, we returned to our coding project and valued each other's thinking process when considering what roles and parts we would assign to each other to get our simulation done. Another skill that came hand in hand with partnership was communication and contact. To effectively and continuously consider each other's work methods and schedules, we had to incorporate digital communication into our daily schedules. With whatever time we had available, we made sure to have scheduled conversations in which we made sure to listen to each other and reflect upon exchanged ideas instead of arguing or rejecting potential ideas. We put these very same conversational skills to the test during our time working on the Freedom Project and noticed that we weren't stuck on the same steps anymore. Progress went a lot faster.

### Reflection

I look forward to improving my Freedom Project and developing new ideas to add to it.

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)

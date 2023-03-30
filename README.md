# EDwiz 🪄


## Inspiration 💡


Boring PowerPoint slides and drab Zoom webcams. This is the “cutting edge” technology being used to teach classes remotely today. However, as the topics and concepts taught in schools become increasingly abstract, these tools may not be sufficient to engage and support student learning. According to a survey of Canadian schools, [only 37%](http://cea-ace.ca/sites/cea-ace.ca/files/cea-2012-wdydist-report-1.pdf) students feeling invested in learning. Statistics show that [25% of students](http://www.statcan.gc.ca/pub/81-004-x/2004006/7781-eng.htm)  of students who drop out of school cite low self-efficacy and disengagement as reasons for leaving. Disengagement with school can begin as early as age 9 and may worsen as students get older.


To address this issue, some methods have been developed to help students enjoy learning. Given that 40% of students are visual learners, visualizations can be particularly effective for retention. However, incorporating visualizations into lessons can be challenging, as it often requires teachers to spend time learning complex software.


**We believe that visualizations should be summoned magically with simple gestures. We went ahead and built just that.**

[![gestures.png](https://i.postimg.cc/Bb4n4nJw/gestures.png)](https://postimg.cc/k6Ymy96x)

## What it does 🤔

EDwiz is a browser based visualization tool that allows educators to better prepare for their lessons by mapping Gestures --> Visualizations.

After logging in, teachers can view a Canvas where they can preset three unique gestures to visualizations of their choice. We have recognized the value of Generative image AI applications such as Dall-E 2 and Stable Diffusion and have offered teachers a way to map their **gestures to Generative Images** based on their prompt or lesson requirements. Moreover, we enable teachers to map their **gestures to GIFS** because GIFs are often liked by students and convey the concept in an interactive manner
  

## How we built it ⚙️


First and foremost, it is Crafted with 💙.  We have built a ML-enabled full-stack application that solves a real world problem. The whole process can be broken into the following points :-

- React, Next.js on the front-end with styling done in Tailwind and DaisyUI

- Prisma Client, MongoDB on the back-end

- External services like MongoDB Atlas, Google Cloud, Giphy, Lexica

Our application is technically complex, polished, original, useful, and built with excellent execution.
[![logic-flow.png](https://i.postimg.cc/brh6dWrd/logic-flow.png)](https://postimg.cc/MM90Fsy8)




## Design 🎨

We were heavily inspired by the revised version of **Double Diamond** design process, which not only includes visual design, but a full-fledged research cycle in which you must discover and define your problem before tackling your solution & then finally deploy it.

![DD](https://i.postimg.cc/W4bvXqDj/image-148.png)

  

> 1. **Discover**: a deep dive into the problem we are trying to solve.
> 2. **Define**: synthesizing the information from the discovery phase into a problem definition.
> 3. **Develop**: think up solutions to the problem.
> 4. **Deliver**: pick the best solution and build that.


Moreover, we utilized design tools like Figma, Photoshop & Illustrator to prototype our designs before doing any coding. Through this, we are able to get iterative feedback so that we spend less time re-writing code.



![breaker.png](https://i.postimg.cc/YSvrrWnc/breaker.png)

  

# Research 📚

Research is the key to empathizing with users: we found our specific user group early and that paves the way for our whole project. Here are a few of the resources that were helpful to us —

  
-  https://www.curiousneuron.com/learningarticles/2016/9/6/september-a-program-that-aims-to-engage-students-in-learning#:~:text=Canadian%20students%20are%20disengaging%20from,known%20as%20self%2Defficacy).
- https://www.frontiersin.org/articles/10.3389/fcomp.2021.706939/full
  

**CREDITS**

- **Design Resources** : Freepik, Behance
- **Icons** : Icons8, fontawesome
- **Font** : Urbanist / Roboto / Raleway



## Challenges we ran into 😤

  We had challenges creating gestures that can be mapped uniquely identified but we managed to create 3 that would be intuitive to use while teaching. We tweaked the model to run faster to suit our needs in the browser and for our customer teachers.

Being in 3 different time zones (Canada, India, and Germany) and coordinating was definitely a challenges. Sleepless nights and ruthless commitment was our solution for this problem.
  

## Best Domain Name from Domain.com ⭐

We reserved the name visualizing-wizard.tech to suit our idea.

  
## Best Accessibility Hack sponsored by Fidelity ♿

We were delighted to know that this was a category. We are really sympathetic towards disabled persons and our app is a best fit for deaf people. American Sign Language (ASL) can be better taught using EDwiz and be made more interactive and sticky!

## Best Use of MongoDB Atlas

MongoDB Atlas was one of the main cloud services we used in our project to host our database and is one of the reasons why we were able to build such a technically complex project in such a short time. 

We used MongoDB as our database and used the accompanying GUI client Mongo Compass to interact with the DB.

We also used MongoDB as a caching layer, in a scenario where users already selected an image before. This way we save compute and utilize storage to make our app super quick for the users. We tied our user credentials and user history in collections in the DB. The super easy interface with MongoDB made it pleasurable to use.

[![Screenshot-2023-01-08-172620.png](https://i.postimg.cc/bNxbY40K/Screenshot-2023-01-08-172620.png)](https://postimg.cc/F7K1DWBZ)
[![Screenshot-2023-01-08-172638.png](https://i.postimg.cc/vmfwCLwL/Screenshot-2023-01-08-172638.png)](https://postimg.cc/v1YKVnBc)




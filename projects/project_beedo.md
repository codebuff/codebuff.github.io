---
layout: project_details
title: Project Beedo
subtitle: A robot capable of avoiding obstacles and detecting fire simultaneously using only IR sensors
test_cases: None
code_quality: Horrible
commit_activity: None
breadcrumbs: ["limitations", "picture", "video"]
permalink: /project-beedo/

---

<div class="content" markdown="1">
    
    


A fire fighting robot capable of avoiding obstacles and detecting fire simultaneously using only IR sensors without any human intervention or additional hardware.

This was an academic project for our Digital Logic and Circuits course.

As a part of team of four, my job was to come up with the design of bot and the algorithm which can perform the task in controlled environment.

We settled on Atmega32 and took upon us the challenge of using only IR to detect obstacle, avoid them and detect the fire at the same time, if the fire was detected then it was not to be perceived as an obstacle and must be extinguished.

The toughest part in the project was to figure out the threshold where robot can differentiate between the fire and obstacle.

[Demo video](#video) shows the robot in action.

---

## Limitations

In order to make use of as much less hardware as possible some compromises were made which resulted in limitations in functionality, some of the prominent among them are :
- Since only IR sensors were used, the bot was incapable of detecting anything in direct sunlight or outdoors on a very bright day.
- It also behaved erratically if it came across the glass in direct sight.
- The bot was very fragile, i.e. single collision can mess up the whole alignment of IR LEDs and recalibration is needed.

---

## Picture

<figure class="image is-4by3 is-marginless">
    <img src="/img/project-beedo/landscape/0.png">
</figure>

---

## Video
    
</div>

<iframe width="100%" height="520p"  src="https://www.youtube.com/embed/QrHOruRoTBo"></iframe>
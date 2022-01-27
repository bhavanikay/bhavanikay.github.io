---
layout: project
type: project
image: images/zombie.png
title: Zombie Apocalypse Maze
permalink: projects/ZombieApocalypseMaze
# All dates must be YYYY-MM-DD format!
date: 2019-09-27
labels:
  - Java
  - EZGraphics
summary: A maze game that I created for ICS 111.
---

<img class="ui image" src="{{ site.baseurl }}/images/zombie.png">

In the case of a zombie apocalypse, it is essential to have your priorities straight. You must know what to avoid (abandoned buildings, fires, and zombies) and what to find. In this game, players get a chance to use their quick thinking and reflexes to drive their car through a zombie apocalypse. They must pick up others who need help while collecting medical kits and other resources and avoiding any hazards at all costs. Here is a link to a [video of the gameplay](https://www.youtube.com/watch?v=sMU1ypQf9JI).

 I used EZGraphics in order to create this game, and I learned a lot about Object Oriented Programming. It was interesting to me how you could essentially create a virtual object and assign any properties to it. I had fun thinking about a theme for the game that would allow me to incorporate my love for horror movies (specifically zombie movies) with the requirements presented to us. While doing this project, I learned how to create and utilize a “random generator” in order to generate the object and obstacles in the game at random locations during every play. I also learned how to utilize keyboard keys in order to control the direction that images travel on the screen. I used this for my “Car” class, which essentially makes sure that the player is able to control the car with the “w”, ”s”, ”a”, and “d” keys. Here is a snippet:
 
 ``` 
 Car(){
		x = 100;
		y = 50;
		picture = EZ.addImage("truck.png", x, y);
	}
	void move() {
		if (EZInteraction.isKeyDown("w")) {
			y = y - 6;
		}
		if (EZInteraction.isKeyDown("s")) {
			y = y + 6;
		}
		if (EZInteraction.isKeyDown("a")) {
			x = x - 6;
		}
		if (EZInteraction.isKeyDown("d")) {
			x = x + 6;
		}
		picture.translateTo(x, y);
	}
 
 ```


Source: <a href="https://github.com/bhavanikay/ZombieApocalypseMaze"><i class="large github icon "></i>bhavanikay/ZombieApocalypseMaze</a>


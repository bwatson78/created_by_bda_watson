---
layout: single
title: About B.D.A
permalink: /about/
---

I'm a Full-Stack Web Developer with over <span id="career_length"></span> years of Ruby on Rails production experience.

But enough about work--I travel with my wife anywhere I can to try all the news: food, beer, art, culture, architecture, attitudes--whatever they got, I'm up for. My earliest memory is watching Halloween on network TV by myself on Halloween night. That made me a horror film fanatic for life. Well, it made me a cinephile, but horror's still my fave. 

I originally hail from South Jersey, just forty-five minutes from Philadelphia, and have fond memories catching the odd Flyers and Phillies games. I still root for all things Philly, including cheesesteaks, soft pretzels, and weird, insane sports mascots. Even though my ties to my birthplace are strong, my home's in Enterprise, Alabama.

Finally, I'm a big fan of most things live. Sporting events, concerts, theater productions, and comedy. In most cases, I'm dragging my wife to something she has no interest in, like A Perfect Circle or Primus concert. Or a Flyers/Lightning game. But sometimes I get lucky and she likes Book of Mormon and Hamilton. The set Patton Oswalt performed worked for her, too.


<script>
	var careerStart = new Date("06/01/2018");
	var careerDiff = Date.now() - careerStart.getTime();
	var careerDT = new Date(careerDiff);
	var year = careerDT.getUTCFullYear();
	var career_age = Math.abs(year - 1970);

	var spanToChance = document.getElementById("career_length");
	spanToChance.innerHTML = career_age;
</script>

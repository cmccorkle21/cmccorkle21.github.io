---
title: Carpooler
subtitle: Graph Theory | Traffic | Excitement
layout: page
show_sidebar: false
menubar: example_menu
hero_image: /img/traffic.jpg
---

![java](https://img.shields.io/badge/java-green)

Carpooler is one of the first computer science "research" projects I ever completed. I put research in quotations for several reasons which we'll get to. This project was conducted in the spring of 2018, the year I graduated high school. Don't expect the highest caliber peak efficiency programming in this project, but look to appreciate the opportunity I was given to do such a project as a senior in highschool. [Here](https://github.com/cmccorkle21/carpool-graph-theory) is a link to the GitHub project.

##### The Problem
Simple: Traffic. I went to Pace Academy at the time, a high school in Atlanta, Georgia. Whenever people visit me in Atlanta, I often remark "when you drive our roads, you can tell we lost the civil war." The roads near my Alma Mater high school were no different. As you might imagine, when my post AP Data Structures and Algorithms teacher told us to "solve a real world problem," I was ready to go.

##### The Solution
Simple graph theory! Not unlike the travelling salesman problem, my algorithm uses only 3 data points for each student. Their home address, when they leave for school in the morning, and when they leave for home each afternoon. With this information, students are assigned compatibility scores with one another. The algorithm creates groups of 5 to carpool together that minimizes total wasted time and gas.
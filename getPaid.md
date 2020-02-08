---
title: GetPaid
subtitle: Dolla bills y'all
layout: page
show_sidebar: false
menubar: example_menu
hero_image: /img/dollar.jpg
---

![python](https://img.shields.io/badge/python-3.7-green)
![googleCal](https://img.shields.io/badge/Google Calendar-blue)



getPaid is a little python project I created in an evening recently when it came to my attention that I had no idea whether I was getting paid in the correct amount I was supposed to. Being the bright eyed and bushy tailed second year colleg student that I am, I began sifting through Google Calendar APIs til I had a working proof of concept: getPaid. The program is simple. After authenticating the program to view and edit your Google Calendar, the program looks for all calendar events with a user supplied name ("work shift" in my case). The program asks for the start and end date of your pay period (mm/dd/yyyy; let freedom ring); it then totals worked hours and multiplies that by a user supplied pay rate. Simple, fun, and useful tools like this are just my favorite type of development. Check out getPaid on Github [here!](https://github.com/cmccorkle21/getPaid)
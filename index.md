---
title       : Futbol Fun with Shiny
subtitle    : (and Slidify)
author      : Michael O'Dell
job         : Making Stuff Happen
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
ext_widgets: {rCharts: [libraries/polychart]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &radio

## Slide 2
The FIFA World Cup Finals in Brazil just ended, the top European leagues have yet to start, so to fill that world class soccer (as we say in the States) craving, you:

1. Tell yourself that MLS and Liga MX are just as good (don't get me wrong, I catch Earthquakes games when I can) and just suffer

2. Put on your Messi strip and dribble like crazy through the local under 4 youth team

3. _Check out the 2014 FIFA World Cup Goal Inspector_

*** .hint 
No. 2 will not win you lots of friends

*** .explanation 
This slidify presentation is promoting my ShinyApp.

---

## Slide 3
What is the [Goal Inspector](http://mpodell.shinyapps.io/goal_inspector/)?

![Goal Inspector](./assets/img/ginspector2.jpg)

The Goal Inspector is an interactive histogram of every goal (excluding penalty kicks shootouts in the knockout rounds) in 2014 World Cup Finals.

The Goal Inspector is a [Shiny App](http://shiny.rstudio.com), and uses [rCharts](http://rcharts.io) by [Ramnath Vaidyanathan](https://github.com/ramnathv).

---

## Slide 4
So that you don't go into a soccer-withdrawal coma, here is a chart of goal scoring frequency (calculated right here in the Slidify slide!):

<iframe src=' assets/fig/unnamed-chunk-1.html ' scrolling='no' frameBorder='0' seamless class='rChart polycharts ' id=iframe- chart62102f03f64e ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## Slide 5
You're still here? Go explore the World Cup goals with the [Goal Inspctor](http://mpodell.shinyapps.io/goal_inspector/)!

This presentation built in [Slidify](http://ramnathv.github.io/slidify/).

Data for the Goal Inspector extracted from the [openfootball](http://openfootball.github.io) project.




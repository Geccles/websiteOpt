## Website Performance Optimization portfolio project

This project is all about optimizing this online portfolio for speed.

I first started out by optimizing the critical rendering path and made index.html render as quickly as possible. The next challange was to remove jank from the little pizzas when scrolling in pizza.html which automatically gave me a consistent 60 fps frame rate. The last task was to improve the time of resize of pizza when a different size is being selected using the slider. This I was able to improve time from 118ms to 2ms.

To get started, check out the repository, inspect the code,

### Use and Test project
In order to see the outcome of what the page speed is I used googles PageSpeed Insights where I received a score of 98 or better.


#### Part 1: Optimize PageSpeed Insights score for index.html

Optimize the html and css to achieve a PageSpeed Insights score of 90+ for Mobile and Desktop.

*Just a side note, I created two images one is a small pizzeria.jpg for index.html and a larger one for pizza.html which allowed for better optimization.

Below you can see my test in PageSpeed Insights.

![image](desktopPageSpeed.png)

![image](mobilePageSpeed.png)

#### Part 2: Optimize Frame per Second in pizza.html

Identify and perform optimizations ensuring a consistent frame rate of 60fps when scrolling in pizza.html.

The target timeline should look something like this (or better):

![image](framePerSec.png)

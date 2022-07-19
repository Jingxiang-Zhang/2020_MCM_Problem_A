### Introduction

This competition is Mathematical Contest in Modeling (MCM) in 2020, problem A, predict how the fish will move toward by the influential of ocean temperature growth. As a part of a team, my job was to complete all of relative program of this problem. I use Python as a programming language.

### Background Information

Because of the global warming, the ocean temperature will keep growthing. In the same time, the fish living in the ocean around England will go north to find the optimum temperature. As a result, fisher will need to spend more on catching the fish. And our job was to figure out the whole process. 


### Data Crawling and Analysis

First, I crawled the global ocean temperature data from [oceanwatch](data from: https://oceanwatch.pifsc.noaa.gov/erddap/griddap). Those data include the temperature measure result of all the oceans in the earth, from 1985 to 2014.

<div align="center">
  <img src="https://github.com/Jingxiang-Zhang/2020_MCM_Problem_A/blob/main/img/data.png">
</div>

Then, I extract the ocean temperature information in North Atlantic, and color it.

<div align="center">
  <img src="https://github.com/Jingxiang-Zhang/2020_MCM_Problem_A/blob/main/img/data_show.png">
</div>

From this group of image, I conclude that the ocean temperature is indeed increase. To get a better understanding of it, I computed the average temperature in North Atlantic, and got this:

![average 	ocean temperature in the past in Atlantic](:UN_3_MCM/average.png){:data-align="center"}

### Prediction and Conclusion

My work here was to make a regression of the data, and predict the future trend. Therefore, I make a bold prediction, that the ocean temperature in the future will keep growing in a relative short period, with a little bit fluctuating up and down. The algorithm detail can be reached in my project code.

<div align="center">
  <img src="https://github.com/Jingxiang-Zhang/2020_MCM_Problem_A/blob/main/img/Ocean_temperature_prediction.png">
</div>

And I make this animation to demonstrate how the temperature will become in the future.

<div align="center">
  <img src="https://github.com/Jingxiang-Zhang/2020_MCM_Problem_A/blob/main/img/ocean.gif">
</div>

Finally, I draw the isotherms of fish's favorite temperatures, which can be used for my teammate to calculate fisher's spending in the future.

<div align="center">
  <img src="https://github.com/Jingxiang-Zhang/2020_MCM_Problem_A/blob/main/img/future.png">
</div>

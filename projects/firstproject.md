---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Introduction"
date: 2023-08-31
published: true
labels:
  - More about me
summary: "Hey there! My name is Emma and I'm an MIS major at the Shidler College of Business at UHM. I'm really excited to be taking my first course in the MIS major this semester. Feel free to reach out or connect on any of my social media links."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

This is my first project on my porfolio, and I just wrote a short introduction blurb about myself.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).

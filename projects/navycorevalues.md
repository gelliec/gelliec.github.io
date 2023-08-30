---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "NavyCoreValues"
date: 2023-08-29
labels:
  - Honor
  - Courage
  - Commitment
summary: "The Navy's core values of honor, courage, and commitment represent the bedrock principles that guide sailors in upholding integrity, facing challenges with bravery, and demonstrating unwavering dedication."
---

Honor serves as the moral compass that guides every action and decision. Sailors hold themselves to the highest standards of integrity, demonstrating unwavering honesty and accountability in all endeavors. They recognize that their actions not only reflect their personal character but also the reputation of the Navy as a whole. Upholding honor means fostering an environment of trust and respect among fellow sailors and the global community, regardless of the challenges faced.

Courage stands as an indomitable trait that defines Navy sailors. They face adversity head-on, whether it's the demands of their duties or confronting daunting situations at sea. Courage means acting without hesitation to protect their shipmates, defend their country's interests, and uphold the principles they hold dear. Sailors venture into uncharted waters, both literally and metaphorically, demonstrating the bravery to push boundaries and adapt to ever-changing circumstances. This courage is the foundation for leadership, inspiring others through actions that exemplify fortitude and resilience. Commitment is the unwavering dedication that Navy sailors bring to their roles, day in and day out. It's a pledge to serve their nation with unwavering loyalty and to contribute their skills and efforts to the greater mission. Sailors commit not only to their responsibilities but also to their fellow sailors, fostering a sense of camaraderie and unity that transcends individual pursuits. This commitment extends beyond the duration of service, as sailors remain steadfast in upholding their duty to the Navy, their country, and the values they hold dear. The synergy of honor, courage, and commitment transforms Navy sailors into a force that stands resolute, exemplifying the very best qualities of service and sacrifice.


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

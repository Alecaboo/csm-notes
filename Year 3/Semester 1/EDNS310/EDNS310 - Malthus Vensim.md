 #edns310  #design 

## Part A

![[Screenshot 2025-12-16 at 6.25.48 PM.png]]

| Variable             | Type     | Equation                                        | Units               |
| -------------------- | -------- | ----------------------------------------------- | ------------------- |
| Pop growth           | Flow     | Growth rate\* World population                  | People/year         |
| World Population     | Stock    | Integ(Pop growth, Initial = 2.5\*10^9           | People              |
| Growth rate          | Constant | 0.02                                            | Unitless percentage |
| Grain Harvest Growth | Flow     | Grain/year                                      | Tonnes/year         |
| Grain/year           | Constant | 31.06\*10^6                                     | Tonnes              |
| World Grain Harvest  | Stock    | Integ(Grain Harvest Growth), Initial = 631*10^6 | Tonnes              |
## Part B
![[Screenshot 2025-12-16 at 6.40.21 PM.png]]
New Table


| Variable                      | Type      | Equation                             |
| ----------------------------- | --------- | ------------------------------------ |
| Food Per Person               | Auxillary | World Population/World Grain Harvest |
| Minimum Food Level Per Person | Constant  | 0.165                                |
![[Screenshot 2025-12-16 at 6.44.36 PM.png]]
Blue is grain harvest and red is population.
Stocks changing as expected - grain harvest is growing linearly while population is increasing exponentially.

![[Screenshot 2025-12-16 at 6.45.14 PM.png]]
Blue is food per person and red is minimum food - food per person drops below minimum food in 2067 (the intersection of the two lines on the graph), and continues to drop as the graph continues. The behavior of these lines is also as expected - minimum shouldn't be changing, and the curve of the food per person is in line with what's being demonstrated on the population/harvest graph.

## Part C
| Variable         | Type     | Equation                                      | Units               |
| ---------------- | -------- | --------------------------------------------- | ------------------- |
| Pop growth       | Flow     | Growth rate\* World population                | People/year         |
| World Population | Stock    | Integ(Pop growth, Initial = 2.5\*10^9         | People              |
| Growth rate      | Constant | 0.02-STEP ( 0.006 , 1998 ) - STEP(0.005,2023) | Unitless percentage |
Graphs

![[Screenshot 2025-12-16 at 6.48.35 PM.png]]
Noticeably less steep curve for population growth, with visible changes in the slope just before 2000 and just after 2020.
![[Screenshot 2025-12-16 at 6.49.32 PM.png]]
Food per person now never drops below the minimum due to the significantly reduced population.

## Part D
Grain/year growth equation
```
31.06*10^6-(31.06*10^6)*STEP(1,1970)

+(34.5*10^6)*STEP(1,1970)- (34.5*10^6)*STEP(1,1990)

+(9.6*10^6*STEP(1,1990)) -(9.6*10^6)*STEP(1,2010)
```
I made the assumption that grain production stays at the reduced level of 9.6 million tonnes between 1998 and 2010, since it seemed less correct to assume that production increased back to the original 34.5 million tonne value.

Graphs

![[Screenshot 2025-12-16 at 7.02.32 PM.png]]
- Steps are quite distinctly represented on the grain graph, leveling out in 2010.

![[Screenshot 2025-12-16 at 7.03.22 PM.png]]
- Food per person now passes below minimum food in 2061, which is honestly astonishingly close to the original value of 2067 before we began updating the model. While both grain and population were reduced from what the original equations predicted, population was reduced by a factor of nearly 4.6 while grain was "only" reduced by a factor of about 3.5 - so grain was reduced by a comparatively smaller multiplier in terms of final total, almost certainly due to the exponential nature of population making it very sensitive to changes.

## Part E
- I do believe that it is appropriate to model grain with a linear model - with a simple linear model, like we used in the initial case, this assumes that the variety of factors that go into production remain constant, but a simple step model like we used in the later parts that accommodate for significant changes (like the expansion of mechanical agriculture in the mid 20th century) can fairly accurately represent the data. ![[yields-of-important-staple-crops.png]]
	Figure 1 - Staple Crop Yields \[1]
- The graph in Figure 1 shows yields of a variety of staple crops between 1961 and 2023, and most of the crops follow a fairly linear trend - the least linear are millet and sorghum, but they appear more dramatic than they really are due to the relatively small scale of their production and growth compared to the rest of the crops.
### Citations
\[1] “Wheat yields,” Our World in Data, https://ourworldindata.org/grapher/wheat-yields?time=1961..2023&mapSelect=~USA (accessed Dec. 16, 2025).
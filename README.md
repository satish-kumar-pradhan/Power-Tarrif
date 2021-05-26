# Power-Tarrif
Energy Sector related Optimisation problem 
from 12.15 of Model Building in Mathematical programming 5th Edition Problem 12.15

A number of power stations are committed to meeting the following electricity load demands over a day:
| Time of day     | Demand  |
|:----------------|:--------|
|12 p.m. to 6 a.m.| 15000MW |
|6 a.m. to 9 a.m. | 30000MW |
|9 a.m. to 3 p.m. | 25000MW |
|3 p.m. to 6 p.m. | 40000MW |
|6 p.m. to 12 p.m.| 27000MW |

There are three types of generating unit available: 12 of type 1, 10 of type 2 and five of type 3. Each generator has to work between a minimum and a maximum level. There is an hourly cost of running each generator at minimum level. In addition, there is an extra hourly cost for each megawatt at which a unit is operated above the minimum level. Starting up a generator also involves a cost. All this information is given in Table 12.6 (with costs in £). In addition to meeting the estimated load demands there must be sufficient
generators working at any time to make it possible to meet an increase in load of up to 15%. This increase would have to be accomplished by adjusting the output of generators already operating within their permitted limits.


|Type      | No of Units | Minimum level| Maximum Level| Cost per hour at minimum |Cost per hr above minimum | Cost of startup |
|:---------|:------------|:-------------|:-------------|:-------------------------|:-------------------------|:----------------|
| Type 1   |     12      | 850MW        | 2000MW       | 1000                     | 2.00                     | 2000            |
| Type 2   |     10      | 1250MW       | 1750MW       | 2600                     | 1.30                     | 1000            |
| Type 3   |     5       | 1500MW       | 4000MW       | 3000                     | 3.00                     | 500             |


Question asked?
1. Which generators should be working in which periods of the day to minimise total cost?
2. What is the marginal cost of production of electricity in each period of the day; that is, what tariffs should be charged?
3. What would be the saving of lowering the 15% reserve output guarantee; that is, what does this security of supply guarantee cost?

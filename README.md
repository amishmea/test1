## Advanced Algorithms Assignment - 1

### Randomized Operations

#### 1 Million operations with 3:2 ratio of insertions to deletions:

###### Maximum time for an *insertion*:
|Factors|1.25|1.5|1.75|2|3|
|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|**1.25**|<span style="background-color:pink">0.450187</span> | 0.199093 | 0.109981 | 0.114049 | 0.118177 | 
|**1.5**|0.113018 | 0.151655 | 0.252908 | 0.397351 | 0.089325 | 
|**1.75**|0.244078 | 0.286371 | 0.382483 | 0.347339 | 0.259199 | 
|**2**|0.069672 | 0.072986 | 0.079813 | 0.085788 | 0.065528 | 
|**3**|0.040793 |<span style="background-color:lightgreen">0.035938</span> | 0.041115 | 0.037632 | 0.381514 |

###### Maximum time for a *deletion*:
|Factors|1.25|1.5|1.75|2|3|
|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|**1.25**|0.015549 | 0.002710 | 0.003282 | 0.002647 | 0.002662 | 
|**1.5**|0.024377 | <span style="background-color:pink">0.046329 | 0.009343 | 0.003345 | 0.003357 | 
|**1.75**|0.025382 | 0.011744 | 0.010629 | 0.007369 | 0.008594 | 
|**2**|0.015461 | 0.012298 | 0.010149 | 0.009442 | <span style="background-color:lightgreen">0.002288 | 
|**3**|0.008143 | 0.006950 | 0.006339 | 0.007903 | 0.003241 | 

###### Average time for an *operation*:
|Factors|1.25|1.5|1.75|2|3|
|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|**1.25**|0.000062 | 0.000060 | 0.000061 | 0.000063 | 0.000062 | 
|**1.5**|0.000064 | 0.000061 | 0.000061 | 0.000063 | 0.000062 | 
|**1.75**|0.000066 | 0.000064 | 0.000061 | 0.000062 | 0.000062 | 
|**2**|0.000067 | 0.000065 | 0.000064 | 0.000060 | <span style="background-color:lightgreen">0.000059 | 
|**3**|<span style="background-color:pink">0.000068 | 0.000065 | 0.000065 | 0.000062 | 0.000060 |

###### Average time for an *insertion*:
|Factors|1.25|1.5|1.75|2|3|
|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|**1.25**|0.000064 | <span style="background-color:lightgreen">0.000060 | 0.000061 | 0.000066 | 0.000066 | 
|**1.5**|0.000063 | <span style="background-color:lightgreen">0.000060 | 0.000063 | 0.000066 | 0.000064 | 
|**1.75**|0.000066 | 0.000065 | 0.000064 | 0.000065 | 0.000065 | 
|**2**|0.000069 | 0.000068 | 0.000066 | 0.000061 | <span style="background-color:lightgreen">0.000060 | 
|**3**|<span style="background-color:pink">0.000070 | 0.000067 | 0.000067 | 0.000062 | 0.000061 | 

###### Average time for a *deletion*:
|Factors|1.25|1.5|1.75|2|3|
|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|**1.25**|0.000060 | 0.000060 | 0.000060 | <span style="background-color:lightgreen">0.000057 | <span style="background-color:lightgreen">0.000057 | 
|**1.5**|0.000064 | 0.000062 | 0.000058 | 0.000058 | 0.000058 | 
|**1.75**|<span style="background-color:pink">0.000065 | 0.000062 | <span style="background-color:lightgreen">0.000057 | <span style="background-color:lightgreen">0.000057 | 0.000058 | 
|**2**|0.000063 | 0.000061 | 0.000060 | 0.000059 | <span style="background-color:lightgreen">0.000057 | 
|**3**|0.000064 | 0.000062 | 0.000061 | 0.000061 | 0.000058 | 


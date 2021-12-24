## School Districtic Analysis
### Overview of the Project: 
The city school district requested analysis of the standardized tests scores and school spending budgets to provide insights to the district office on any performance trends. These analyses will help inform the district on key decisions at the district and school levels. 

Additionally, the school board received evidence of academic dishonesty from Thomas High School. We ran the analysis twice. In the second trial, we replaced all ninth-grade reading and math scores from Thomas High School with NaNs.

### Results: 
#### **School District Summary**
* The overall reading and math scores in the district summary decreased by 0.3% after removing the ninth-grade scores from Thomas High School.

District Summary(Trial 1):
![](https://i.imgur.com/mQ8Xex6.png)

District Summary(Trial 2):
![](https://i.imgur.com/ER9YFYZ.png)

#### **School Summary**
* Thomas High School's math and reading score percentage increased by roughly 26%.
* Thomas High School was not considered when looking at 9th-grade scores. Schools shifted up one place in the original order of performance. 
* There was no effect on school spending at this time as it doesn't account for math and reading scores. 
* Medium-sized schools saw a decrease of 0.01 in math and reading scores.
* Charter schools saw a decrease of 0.01 in math and reading scores.

School Summary (Trial 1):
![](https://i.imgur.com/8XmRKSi.png)

School Summary (Trial 2): 
![](https://i.imgur.com/ajPU9E2.png)

Top Performing Schools (Trial 1):
![](https://i.imgur.com/movOGDu.png)

Top Performing Schools (Trial 2):
![](https://i.imgur.com/7dl5pEJ.png)

**Math Scores by Grade:**
| Trial 1 | Trial 2 |
| -------- | -------- |
| ![](https://i.imgur.com/15kzxt7.png)   | ![](https://i.imgur.com/36T3d6g.png)    |

**Reading Scores by Grade:**
| Trial 1 | Trial 2 |
| -------- | -------- |
| ![](https://i.imgur.com/qpReB8M.png)   |  ![](https://i.imgur.com/ZiQeAcJ.png)   |

**School Spending (Per Student):**
| Trial 1 | Trial 2 |
| -------- | -------- |
| ![](https://i.imgur.com/YcqEmPR.png)   |  ![](https://i.imgur.com/JCTmlzs.png)    |

**School Size:**
| Trial 1 | Trial 2 |
| -------- | -------- |
| ![](https://i.imgur.com/T2M77xi.png)   |  ![](https://i.imgur.com/2F3Igbb.png)    |

**School Type:**
| Trial 1 | Trial 2 |
| -------- | -------- |
| ![](https://i.imgur.com/AHQWZ0o.png)   |  ![](https://i.imgur.com/UfSnwrM.png)    |

### Summary: 
It is difficult to confirm whether academic dishonesty affected the analysis. The difference between the reading and math scores in trials 1 and 2 was less than 1%.  The overall passing percentage for medium-size schools decreased by 0.07%. The overall passing percentage for charter schools decreased by 0.03%. Thomas High School was still considered a top 5 performing school in the district with an overall passing percentage of 90.1%. 

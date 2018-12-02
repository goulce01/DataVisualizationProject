<html>
  <img src ="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Olympic_rings_without_rims.svg/1200px-Olympic_rings_without_rims.svg.png">
</html>
<br/>
<p align="center">
<font size="20" color="White" face="Trebuchet MS" style="border:2px solid DodgerBlue">120 Years of Olympic History</font>
</p>
<br/>
## This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
### The file contains 271,116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event.
<p align="left">
<font size="4">The dataset included:</font> 
</p>
```markdown
- ID: Unique number for each athlete
- Name: Athlete's name
- Sex: M or F
- Age: Integer
- Height: In centimeters
- Weight: In kilograms
- Team: Team name
- NOC: National Olympic Committee 3-letter code
- Games: Year and season
- Year: Integer
- Season: Summer or Winter
- City: Host city
- Sport
- Event
- Medal: Gold, Silver, Bronze, or NA
```
_Note that the Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on._
<br/>
<br/>
## We also pulled data from a Wikipedia page detailing the [2016 Summer Olympics Women's Marathon results.](https://en.wikipedia.org/wiki/Athletics_at_the_2016_Summer_Olympics_–_Women%27s_marathon)
<p align="left">
<font size="4">The dataset included:</font> 
</p>
```markdown
- Rank
- Athlete's Name
- Nationality
- Time
```
_Time was the information that this dataset provided that was not included in the original dataset._
<br/><br/><br/>
<p align="left">
<font size="5" color="White" style="border:2px solid Green">Our Questions:</font><br/>
<font size="4">1. What factors contribute to the performance of an athlete?</font><br/>
<font size="4">2. How are athletes changing, per sport, over time?</font><br/>
</p>
### As a result of the size of our dataset we aimed to narrow our scope by focusing on Women's Marathon specifically. This was the sport in which we analyzed the most extensively. 
<br/><br/>
<p align="center">
<font size="15" color="Tomato">Context Information</font>
</p>
<br/>
<p align="center">
  <font size="5">Medal Counts by Country for Men and Women's Marathon</font><br/>
  <img src="Women's Marathon Medal Count.png" width="90%"> 
  <img src="Men's Marathon Medal Count.png" width="90%"/>
</p>
_The Unified Team was the name used for the sports team of the former Soviet Union at the 1992 Winter Olympics in Albertville and the 1992 Summer Olympics in Barcelona._
### These graphs show use the countries that are most represented in our future graphs that are broken down by medal type.
<br/><br/>
<p align="center">
<font size="15" color="Tomato">Answering our Questions</font>
</p>
<br/>
<p align="center">
  <font size="5">Change in Average BMI Over Time for Men and Women's Marathon</font><br/>
  <img src="Marathon BMI.png" width="90%"/>
</p>
<br/>
<p align="center">
  <font size="4">Height Distributions of Men and Women's Marathon Medalists vs. Non-Medalists</font><br/>
  <img src="Height Dist of Non Medalists.png" width="50%"/> 
  <img src="Height Dist by Medal Type.png" width="50%"/>
</p>
<br/>
## Weight Distributions of Men and Women's Marathon Medalists vs. Non-Medalists
<p align="center">
  <img src="Weight Dist of Non Medalists.png" width="280" hspace="20"/> 
  <img src="Weight Dist by Medal Type.png" width="280" hspace="20"/>
</p>
### 
<br/>
## Age Distributions of Men and Women's Marathon Medalists vs. Non-Medalists
<p align="center">
  <img src="Age Dist of Non Medalists.png" width="280" hspace="20"/> 
  <img src="Age Dist by Medal Type.png" width="280" hspace="20"/>
</p>
### 
<br/>
## BMI Distributions of Men and Women's Marathon Medalists vs. Non-Medalists
<p align="center">
  <img src="BMI Dist of Non Medalists.png" width="280" hspace="20"/> 
  <img src="BMI Dist by Medal Type.png" width="280" hspace="20"/>
</p>
### 
<br/><br/>
<p align="center">
<font size="15" color="Tomato">Summary</font>
</p>
<br/>
### Our 

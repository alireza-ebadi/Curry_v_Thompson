# curry_v_thompson
 
## This project compares the shooting performances of Stephen Curry and Klay Thompson in 2018-19 season. It is based on the master code developed in [this repository](https://github.com/alireza-ebadi/nba_player_shooting_comparison). It is intended to detect areas in which a good player such as Klay Thompson can work on to reach to an elite level of a player such as Stephen Curry. 

Here are the observations: 
Both players have similar overal shooting performance. 
![Sample](Curry_v_Thompson_all.png?raw=true)

But breaking down the shot type, teh following conclusions can be made:

-Thompson is slightly more efficient than Curry in shots attempted in the paint
![Sample](Curry_v_Thompson_P2.png?raw=true)

-Thompson is noticeably more efficient than Curry in 2-point jumper shots attempted outside the paint. He take more than double CUrry's number while maintaining a better percentage
![Sample](Curry_v_Thompson_O2.png?raw=true)

-Curry is slightly more efficient than Thompson in 3-point shots attempeted beyond the arc
![Sample](Curry_v_Thompson_A3.png?raw=true)

-Curry is significantly more efficient than Thompson in corner 3-point shots
![Sample](Curry_v_Thompson_C3.png?raw=true)

The above observations are summarized in the table below:
![Sample](Curry_v_Thompson.png?raw=true)

**Verdict:** The main difference makers are the 2-point shots outside the paint and beyond the arc 3 shots. While Thompson is superior in the former, Curry is dominant in the latter. Thompson can reach to Curry's numbers if he changes some of his the 2-point shots outside the paint into three point shots. Based on my calculations if Thompson changes 20% of his 2-point jumpers into corner three shots, he will reach to Curry's numbers. This is reasonable because the distance to basket and his performance are very similar in both categories. 


**Available Files:**
1. [curry_v_thompson.ipynb](curry_v_thompson.ipynb): 
  -The notebook is segregated into 3 chapters:
    1. import modules and libraries and set parameters
    2. define functions to draw a 2D NBA courts
    3. find player ID and team ID of the players requested by the user
    4. get shot chart details of the basketball players (all shot attempts during regular season)
    5. compare the 3 point shots beyond the arc
    6. compare the corner 3 point shots
    7. compare the 2 point shots inside the paint
    8. compare the 2 point shos outside the paint 
      
  
8. [environment.yml](environment.yml) and [requirements.txt](requirements.txt):
  -The environment files necessary to recreate the python environment (python 3.6)
    
**DISCLAIMER**
1. The shots are limited to those attempted in the half court

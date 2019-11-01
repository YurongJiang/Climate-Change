# Climate-Change
This is an un-scoped, and open-ended question that relies on public data. This is to understand which regions of the US have experienced the largest shifts in weather patterns in recent times.


__Data source__: NOAA  
__Data date range__: monthly, from 1895 to 2018  
__Region partition__: 9 climate regions   
__Parameters__: 10 parameters  
__ETL details__:see attached notebook  


#### Objective:   
Create Index to measure weather pattern changes for each regions  

#### Methodology:  
1. Quantify current weather pattern by month through __MA__  
2. Determine baseline and calculate __deviation__ by month  
3. Aggregate __monthly deviation into yearly__ deviation  
4. __Unify__ deviation across parameters   
5. Create final __ensemble index__  


#### Finding: 

__region 109 and region 107 have experienced the most changes in recent times.__  

__West Climate Region (109)__: Dramatic change in temperature and drought.  

__Southwest Climate Region (107)__: Significant changes across all parameters.   

This makes a lot more sense as 109 and 107 are next to each other.   

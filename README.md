# Numbers Don't Lie

Analysis on cities of India, and what they do have to say about our nation.
**Kaggle submission.**

Data set : [here](https://www.kaggle.com/zed9941/top-500-indian-cities/downloads/cities_r2.csv) or use the one from repo.

### Dependencies required

  * [pandas](https://pandas.pydata.org/pandas-docs/stable/) - For data analysing and manipulation.
  * [matplotlib](https://matplotlib.org/) - For data visualisation.
  
### Actual data set used : December 2016 version, which only had 493 cities.

### Analysis made on the data set as of June 2017

  * Number of cities : **493**
  * Number of states : **29**
  * Most number of cities are in the state:  **UTTAR PRADESH**
  * Number of cities in **UTTAR PRADESH** :  **63**
  * Least number of cities belong to these states and their counts
  
        HIMACHAL PRADESH             1
        CHANDIGARH                   1
        TRIPURA                      1
        MIZORAM                      1
        NAGALAND                     1
        MANIPUR                      1
        MEGHALAYA                    1
        ANDAMAN & NICOBAR ISLANDS    1

  * There are two **Aurangabad**(s) in the nation, 
        * one belonging to **BIHAR**
        * second one belonging to **MAHARASHTRA**
    
  * Top 5 States with the maximum number of Cities
      
          UTTAR PRADESH     63
          WEST BENGAL       61
          MAHARASHTRA       43
          ANDHRA PRADESH    42
          TAMIL NADU        32
    
  * States vs City counts
      
      ![States&citycounts](/../images/figure_1.png?raw=true "States and city counts")

  * States vs District counts

      ![States&districtcounts](/../images/figure_1-1.png?raw=true "States and district counts")

  * Each city and it's district number plot
    
      ![City&districtnumber](/../images/figure_1-2.png?raw=true "City and district number")
      
    This graph made me analyse and conclude that
      
     * The most common district numbers are `11`, `9` and `12` not the conventional `1`, `2` and `3`.
     
     * District Number, and their occurences and percentage they contribute to the total district count.
        Example : District Number `11`, there are `37` districts in our India numbered `11`, which contributes to `7.51%` of                   total number of districts in India.
        
                                        District Counts  Percentage Index
            District Number                                   
            11                            37              7.51
            9                             26              5.27
            12                            24              4.87
            1                             22              4.46
            3                             22              4.46
            21                            21              4.26
            
    * `95.94%` of districts have their district number value which is less than `50`
    
  * District numbers and their frequency
    
      ![districtcounts](/../images/figure_1-3.png?raw=true "District frequency")
      
     * The above graphs tells us that there are no district numbers from 72 to 98 and few numbers here and there in the 40s & 50s
            Actual missing district numbers : 
            
            `40, 42, 43, 45, 51, 53, 55, 56, 58, 67, 69, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88,              89, 90, 91, 92, 93, 94, 95, 96, 97, 98`
            
   * Missing State Codes
     
          `11, 12, 25, 26, 30, 31`
      
    
      
      

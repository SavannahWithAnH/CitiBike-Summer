# CitiBike-Summer

Please see my completed presentation [here.](https://public.tableau.com/views/CitiBikeSummerEdition/CitiBikeSummerEdition?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Getting Started  
This dataset was very large, with over 1 million rows of data. For the purposes of publishing to Github, and calculating speed of Tableau, I used Python (Pandas) to read in the CSV file and take a sample of the data for visualization purposes. After selecting 30% of the data at random, I wrote the smaller dataset to a new CSV titled CitiBikeoutput. See the process below:

    import pandas as pd
    import numpy as np

    #read in csv
    df = pd.read_csv("./2013-07+08 - Citi Bike trip data.csv")

    #create sample, random 30%
    df_sample = df.sample(frac=0.30, random_state=42)

    #write to new csv
    df_sample.to_csv("CitiBikeoutput.csv", index=False)


## Visualizing the data  
The questions I wanted to answer with this data are as follows:

-Who is cycling?  <br>
-What are the busiest rental hours during summer months (July & August)  <br>
-What are the most popular locations to end cycling trips? <br>
-What bikes are utilized the most? (This could help with maintenance and upkeep)   <br>   
Additionally I wanted to visualize all of the stations with details, and over a period of time. <br>
Finally, I created dashboards and a story to summarize my findings. <br>


<img width="955" alt="image" src="https://github.com/SavannahWithAnH/CitiBike-Summer/assets/126124356/0c12e13d-1247-4829-9601-9effd15d9901">

<img width="957" alt="image" src="https://github.com/SavannahWithAnH/CitiBike-Summer/assets/126124356/69edebb3-f361-47b6-9335-2afe3472a104">

<img width="967" alt="image" src="https://github.com/SavannahWithAnH/CitiBike-Summer/assets/126124356/bcbe7163-986a-40fa-aa42-755a564b893e">

<img width="714" alt="image" src="https://github.com/SavannahWithAnH/CitiBike-Summer/assets/126124356/c55b8b45-3cfd-41ea-9cbf-39036c4cecce">

<img width="952" alt="image" src="https://github.com/SavannahWithAnH/CitiBike-Summer/assets/126124356/3453dbf6-6c8a-4efc-8db1-638e8f01b07c">

<br>
<br>  
<br>  

### Questions?
Please refer to the following:  
[My LinkedIn Page](https://www.linkedin.com/in/savannah-porter-7a2627267/)  
[My Email Contact](savannahnporter@gmail.com)  







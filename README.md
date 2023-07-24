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
-What bikes are utilized the most? (This could help with maintenance and upkeep)   <br>   
Additionally I wanted to visualize all of the stations with details, and over a period of time. <br>
Finally, I created dashboards and a story to summarize my findings. <br>


IMAGESSSSSSSSSSSS


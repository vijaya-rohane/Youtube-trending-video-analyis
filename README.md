# Youtube-trending-video-analyis

Analysis of youtube trending videos dataset

Dataset link : https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset 

Files used - CA_category_id.json, US_category_id.json, US_youtube_trending_data.csv, CA_youtube_trending_data.csv
            Include these files in dataset folder.


final_code.ipynb - 
  Read the data files from "dataset" folder,
  Perform initial loading and cleaning of data,
  Creating model for streak calculation - saving them in "models" folder
  
  
UI_python.ipynb - 
  User interface for entering the values related to youtube video and displaying the streak and e-score of the same.

tag-separation.R -
  To read the cleaned data and use r packages to unnest the tag data as per the separator for a trending youtube video.

Tableau dashboard link - 
  1. https://public.tableau.com/app/profile/shrikant.shrishailya.narawane/viz/Data_Overview_16497792725830/YoutubeTrendingDashboard?publish=yes
  2. https://public.tableau.com/app/profile/shrikant.shrishailya.narawane/viz/Tags_dashboard/TagsDashboard?publish=yes 
  

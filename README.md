**Pathways to Progress: Supporting Education in Vulnerable Regions**
# GovHack 2024

Project description:
To quantify heterogeneity of post-school education seekers across Australian local government areas, allowing for the development of more efficient and targeted strategies that address multiple regions simultaneously.

Google drive link: https://drive.google.com/drive/folders/1rOeE2AiTSgZRJJPBmUHOzxwWGI7qmakW?usp=sharing

Directories:
Please first download and unzip `GovHack directories.zip` to access all subdirectories listed below. Ignore all other subdirectories in github.
* code: This subdirectory contains all R code used for exploration (1_explore_preprocess.Rmd), preprocessing (2_preprocess_analysis.Rmd), analysis (2_preprocess_analysis.Rmd), modelling (3_modelling_inference.Rmd), and inference (4_category_analysis.Rmd). 
* data: Contains preprocessed and post-processed data. Some files were not included as they were too large. However, links to them can be accessed via: https://hackerspace.govhack.org/projects/tbc_2474
* presentation: Contains powerpoint used for video presentation.
* results: Contains exploratory and plots used for video presentation. Exploratory plots are under subdirectory 'histograms'. Note: Most exploratory plots were not saved but can be remade using files in the subdirectory 'code'.

Note: I could not find a bug which was introduced in later in the pipeline (when I was clustering/subsetting the date) which reversed the trend, thus I took the inverse of the SPI to get the original trend. I will need to find the bug after the competition, which I believe is in the second .Rmd file `2_preprocess_analysis.Rmd`

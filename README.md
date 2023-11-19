<img src="https://github.com/AmmarBagharib/sg-hotels-sentiment-analysis/blob/main/tripadvisor-logo.png" width="400" height="240" />

## Hotel Reviews Sentiment Analysis

### Read the Project Report <[HERE](https://github.com/AmmarBagharib/amazon_graph_analysis/blob/master/analysis/report.pdf)>

Project completed for the module, Mining Web Data for Business Insights

National University of Singapore, Semester 1 AY2023/24
- Ammar Bagharib
- Aravinth Adarsh
- Luong Hien Nga
- Nuzzul Islam Nurhaqim
- Png Chen Wei
- Yuen Pin Xuan Tammy
  
Supervised by: Dr. Wang Qiuhong 

# Overview

Hotels in Singapore face the urgent need to understand their customers’ needs and wants pre and post-pandemic. The COVID-19 pandemic has profoundly transformed guest expectations and experiences during the pandemic - customers are seeking for more personalised and empathetic experiences. Furthermore, the hotel scene here is now facing an influx of investments worth billions of dollars (Burgos & Rosendar, 2023). Hotels must adapt and require insights into how different aspects of their service were perceived across different time periods during the pre and post pandemic periods to tailor their offerings effectively. To achieve the aforementioned, we have decided to work from a hotels’ perspective, trying to understand their customers better through analysing hotels’ customer text reviews on TripAdvisor.

Our primary machine learning goal is to empower hotels with advanced insights into customer sentiment. We aim to incorporate aspect-based sentiment analysis and temporal analysis analysis to comprehensively understand customer feedback. This includes identifying specific aspects of their services that impact satisfaction, tracking sentiment changes over pre and post-COVID periods, and understanding which aspects have become more significant in influencing review sentiments Post COVID. We also stratify the analyses based on 3, 4 and 5 star rated hotels in Singapore.


## How to replicate this analysis:

1. You should either have Mini-forge or Anaconda; a conda working environment installed on your device.
2. If a conda environment doesn't exist, you can install **miniforge** [HERE](https://github.com/conda-forge/miniforge](https://kirenz.github.io/codelabs/codelabs/miniforge-setup/#0)https://kirenz.github.io/codelabs/codelabs/miniforge-setup/#0)

We highly recommend using miniforge instead of anaconda. Miniforge is a small, bootstrap version of the data science platform Anaconda (like Minconda) that includes only Python.

Using your IDE, pull this repository using:
```
git clone https://github.com/AmmarBagharib/sg-hotels-sentiment-analysis
```

Navigate to the project repository, and create the virtual conda environment using:
```
conda env create -f environment.yml
```
Now to activate the virtual environment with the packages installed, run:
```
conda activate bt4222_hotels
```

## License

The software provided in this project is offered under the MIT open
source license. Refer to the
[license](https://github.com/AmmarBagharib/sentiment_analysis_bt4222/blob/main/LICENSE.md)
file for more information.


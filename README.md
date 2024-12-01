# Spotify Data Engineering Project with Azure Databricks
### Introduction
The project aims to build a data pipeline using Spotify API on Azure. The pipeline extract data from the Spotify API, load and transform track and artist data into an Azure Data Lake Storage. Lastly, create visualizations on top of the transformed data. 

### Architecture
![Diagram](https://github.com/putthisonwannapong/spotifyproject-azure-databricks/blob/main/image/Architecture-Diagram.png)

### Visualization
![Spotify Dashboard](https://github.com/putthisonwannapong/spotifyproject-azure-databricks/blob/main/image/SpotifyDashboard.PNG)

### Libraries installed in a Databricks  cluster
```
async_timeout
spotipy
```

### Languages
Python, PySpark

### Services
**1. Azure Databricks** : Make use of notebooks to write code for extracting artist and song data from the Spotify API, load the data into Azure containers, transform it into the desired format, and create a Delta table from the transformed data for further analysis.

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
**1. Azure Databricks** : Make use of notebooks to write code for extracting artist and song data from the Spotify API, load the data into Azure containers, transform it into the desired format, create a Delta table from the transformed data, and register it to a catalog for further analysis.
**2. Azure Data Lake Storage Gen2** : Store Spotify raw data and transformed data (Delta Table).                                                                                                                 
**3. Azure Data Factory** : Orchestrate the execution of Databricks notebooks in sequence using a schedule trigger for automated workflows.      
**4. Microsoft Power BI** : Visualize the Spotify data by creating interactive charts and build a dashboard to display key insights.                                                     
**5. Microsoft Entra ID** : Manage identity and access amoung services.                                                                       
**6. Azure Key Valut** : Securely store the Spotify API client ID and secret, along with the Azure Data Lake Storage Gen2 client ID, secret, and tenant ID.


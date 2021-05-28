"Star Trek: The Next Generation" script analysis with NLP and clustering
John Michitsch

Abstract
What kind of insights can be obtained from applying NLP and clustering to the scripts from the series. 

Design
Scripts and show descriptions were acquired and the data was processed in an NLP pipeline. 

Data
Data Source
Script data was obtained from st-minutiae.com
Episode reviews were obtained from startrekguide.com

~175 scripts or ~70K of dialogue chunks for analysis. 

Algorithms
Various script and dialog data analyzed using TruncatedSVD -> KMeans and NMF for topic analysis. Additional tools listed below for additional algorithms.

Tools
- Jupyter Notebook to write / execute Python code
- Pandas / Numpy libraries for data manipulation
- Mathplotlib and Seaborn for visualizations
- Sklearn for vectorization and models (Kmeans, TruncatedSVD, NMF)
- Beautifulsoup for HTML conversion
- Textastic for reading scores
- TextBlob for Sentiment scoring

Communication
Findings are consolidated in a Keynote presentation and the supporting Jupyter notebooks can be found here. (Prep_ notebooks contain EDA and export versions of the feature (X) dataframe Model_ notebooks load the saved dataframes and execute the various models)

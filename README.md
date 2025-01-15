# Historical Network Analysis of 20th Century Country Relations

## Project Overview  
This project explores the geopolitical relationships between countries during the 20th century. Using web scraping and natural language processing (NLP) techniques, the analysis visualizes interrelations and major events to provide insights into how historical ties shaped the current global political landscape.

## Objective  
The goal is to scrape historical data from Wikipedia, analyze it using NLP to identify relationships between countries, and present the findings through a dynamic network visualization.

## Key Insights  
- Mapped key geopolitical interactions throughout the 20th century.  
- Identified central countries in the global network using degree, closeness, and betweenness centrality measures.  
- Highlighted major historical milestones and their impact on international relations.

## Tools and Technologies  
- **Data Collection:** Web scraping (BeautifulSoup, requests)  
- **Text Analysis:** Natural Language Processing (NLTK, SpaCy)  
- **Visualization:** NetworkX, Matplotlib, Plotly  
- **Environment:** Python, Jupyter Notebook  

## Data  
Data was scraped from Wikipedia pages on 20th-century history and politics. Relationships were extracted using NLP algorithms to create a network graph of country interactions.

## Features  
1. **Web Scraping:**  
   Extracted relevant historical information from Wikipedia pages.  
2. **NLP Analysis:**  
   Processed textual data to identify countries involved in major global events.  
3. **Network Visualization:**  
   Developed an interactive network graph that visualizes country relationships and distinguishes between different communities and interactions.

## How I Created 
1. Clone the repository.  
2. Ensure Python and the required libraries are installed (see `requirements.txt`).  
3. Run the Jupyter Notebook to execute the scraping, analysis, and visualization steps.

## Deliverables  
- **Dynamic Network Graph:** A clear, interactive visualization of 20th-century country relations.  
- **Analysis Report:** A summary of key relationships and insights derived from the data.

## Limitations  
- The analysis is based solely on data from Wikipedia, which may have inherent biases or missing details.  
- The NLP approach relies on keyword extraction and may miss nuanced interactions.

## Future Enhancements  
- Expand the dataset by including additional historical sources.  
- Apply more advanced NLP techniques, such as named entity recognition (NER) and sentiment analysis, for deeper insights.

# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 

Link to the dataset: https://open.toronto.ca/dataset/toronto-beaches-water-quality/

I utilized Python within a Jupyter Notebook environment, employing libraries such as pandas for data manipulation and both matplotlib and Plotly for visualization. This combination was chosen for its ability to create interactive, reproducible visualizations that are accessible to a broad audience. The intended audience includes Toronto residents, public health officials, environmental scientists, policymakers, and beach managers who require insights into seasonal water safety trends.

The visualization illustrates temporal trends in E. coli levels at Toronto beaches, highlighting monthly patterns in water quality failures—specifically instances where E. coli concentrations exceed 100 CFU/100mL. This information aids in predicting periods with higher health risks for swimmers. Design considerations focused on clarity and accessibility: a line plot was used to depict trends over time, with labeled axes and a grid to enhance readability. Markers and line styles were selected to make data points distinguishable, and color choices—red for failures and green for passes—were made with colorblind-safe alternatives in mind. Interactivity was incorporated through hover tooltips displaying exact failure counts.

To ensure reproducibility, the script includes dataset URL from the City of Toronto's Open Data Portal and comprehensive data cleaning steps, such as E. coli thresholding. Accessibility was addressed by adding alt-text descriptions, utilizing high-contrast colors, and ensuring compatibility with screen readers through HTML output.

This visualization impacts various communities: families planning beach visits can make informed decisions; nearby restaurants and tourism businesses can anticipate fluctuations in beach attendance; and environmental advocacy groups can use the data to support conservation efforts. Feature selection focused on including E. coli counts, dates, and beach names, while excluding less relevant data like rare weather events to maintain focus on core safety metrics. The 'underwater labour' involved debugging date formats in the raw CSV, researching Health Canada's E. coli thresholds, and testing multiple chart types to achieve clarity in data presentation.

The visualization reveals that July-August have the highest failure rates, likely due to warmer temperatures and increased beach attendance. This could inform public health advisories during peak summer months.
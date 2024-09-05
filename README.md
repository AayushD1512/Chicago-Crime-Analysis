# Chicago-Crime-Analysis
# Chicago Crime Analysis using Big Data Analytics

## Project Overview
This project leverages Big Data Analytics to analyze crime data from the city of Chicago. The goal is to identify crime hotspots, detect trends over time, analyze arrest patterns, and predict future crime occurrences using various machine learning models. The project utilizes data from the Chicago Data Portal, covering the years 2001–2023.

## Motivation
Chicago faces significant challenges related to crime that affect public safety and community welfare. This project aims to provide actionable insights by analyzing crime patterns, arrest effectiveness, and crime density across neighborhoods. The findings are intended to assist law enforcement, policymakers, urban planners, and community organizations in developing data-driven strategies to improve public safety.

## Methodology
### Data Collection
- **Source**: Chicago Data Portal (2001–2023)
- **Attributes**: Crime type, location, time of occurrence, arrest status, etc.

### Data Preprocessing
- Handling missing values
- Feature selection and reduction
- Balancing the dataset using over-sampling/under-sampling techniques
- Reducing crime types from 32 to 20 categories

### Analysis Techniques
- Exploratory Data Analysis (EDA) for understanding data trends and distributions
- Visualizations (bar charts, pie charts, heat maps) to highlight crime hotspots and trends
- Geospatial analysis to map crime densities

### Machine Learning Models
The following models were used to predict future crimes based on historical data:
- **AdaBoost**: Fine-tuned, achieving an accuracy of 76%
- **XGBoost**: Fine-tuned, achieving an accuracy of 79%
- **Random Forest**: Baseline model, achieving an accuracy of 78%
- **Logistic Regression**: Baseline model, achieving an accuracy of 23%

### Tools and Libraries
- **Python**: Programming language for data analysis and modeling
- **Pandas**: Data manipulation library
- **Matplotlib & Seaborn**: Visualization libraries
- **Scikit-learn**: Machine learning library
- **Google Colab**: Cloud-based Jupyter notebook environment
- **Power BI**: Used for advanced visualizations and dashboards

## Results
- **Crime Types**: Theft, battery, and criminal damage were the most prevalent crimes.
- **Monthly Trends**: Crime rates show a cyclical pattern, with a gradual decline after 2010.
- **Crime Hotspots**: Geospatial mapping revealed crime hotspots in specific neighborhoods.
- **Predictive Models**: XGBoost outperformed other models with an accuracy of 79% in predicting future crimes.

## Visualizations
The project includes several key visualizations:
- Crime trends over the years
- Crime distribution across neighborhoods
- Comparison of crime and arrest patterns
- Interactive Power BI dashboard for real-time insights

## Conclusion
The project provides a comprehensive understanding of crime in Chicago, helping stakeholders make data-driven decisions. By analyzing trends, identifying hotspots, and using predictive models, this project offers valuable insights to law enforcement, policymakers, and community organizers.

## Future Work
- Incorporating real-time data for dynamic crime prediction
- Expanding the model to cover more complex crime patterns
- Integrating additional data sources such as social media or 911 call records

## Authors
- **Aayush Dubey**
- **Aksh Gupta**

## Acknowledgements
We would like to thank Dr. Yogesh Gupta for his guidance and support throughout this project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

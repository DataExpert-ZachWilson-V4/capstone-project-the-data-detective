[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/1lXY_Wlg)

# BayAreaInsider Proposal

## The Struggle is Real
BayAreaInsider knows how frustrating it can be to search for a rental property in the Bay Area. It takes days, even weeks, to scour through multiple platforms, compare prices, and find the best fit. And it's not just hard for you - it's also tough to recommend neighborhoods and rentals to friends and family who are moving to the area. BayAreaInsider wants to help you find a great place to live, but it's hard to know where to start.

## The Solution
BayAreaInsider proposes building a platform that collects and analyzes data from various APIs and presents it in a single, easy-to-use interface. With BayAreaInsider, you'll be able to:
- Search for rentals across multiple platforms
- Compare prices and amenities
- Get personalized recommendations based on your preferences
- Explore neighborhoods and their safety scores, public transportation options, and local amenities
- Stay up-to-date with market trends and insights

## Technical Details

### Data Sources
- Zillow API ([link unavailable])
- Redfin API ([link unavailable])
- (link unavailable) API ([link unavailable])
- Walk Score API ([link unavailable])
- CrimeReports API ([link unavailable])
- Yelp API ([link unavailable])
- City-Data API ([link unavailable])

### Phases

#### Data Ingestion and Storage
- API integration and data ingestion
- Data storage in Trino warehouse
- Data quality checks and validation

#### Data Pipelines
- ETL processes for data transformation and loading
- Apache Airflow for workflow orchestration
- dbt for data transformations

#### Data Modeling
- Dimensional modeling for optimized analytical queries
- Data modeling tools: Apache Spark, Trino

#### CLI Tool
- Build a command-line interface tool
- Allow users to query the data models and pipelines
- Provide output in a human-readable format

#### Application Development (Future Phase)
- Build a web application with a user-friendly interface
- Connect to data pipelines and models
- Implement filtering and search functionality

Thanks for considering BayAreaInsider!  
BayAreaInsider is excited to bring this project to life and make rental searching easier for everyone in the Bay Area.

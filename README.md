## Netflix Data Visualization Dashboard
## 1. Project Title / Headline: Netflix Data Visualization Dashboard

An interactive analytics dashboard designed to explore Netflix’s global content library—focusing on content distribution, genre trends, ratings, and country-wise insights.

## 2. Short Description / Purpose

The Netflix Data Visualization Dashboard is a Power BI report that provides a comprehensive overview of Netflix content across different countries, genres, and ratings. It helps users understand content growth trends, distribution patterns, and audience targeting strategies.

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

    • Power BI Desktop – Main platform used for building the dashboard and visualizations.
    • Power Query – Used for data cleaning and transformation.
    • DAX (Data Analysis Expressions) – Used for calculated metrics like total movies, TV shows, and content ratios.
    • Data Modeling – Relationships established between datasets such as content, genre, and country.
    • File Formats – .pbix / .png for development and presentation.

## 4. Data Source: Kaggle

The dataset is based on Netflix content listings, which includes:

    => Title details (movies & TV shows)
    => Country of origin
    => Release year
    => Genre/category
    => Content ratings (TV-MA, PG-13, etc.)
    
    Typical dataset structure includes:
    
    => Content Table – Title, type (Movie/TV Show), release year
    => Country Table – Country-wise mapping
    => Genre Table – Categories like Drama, Comedy, etc.
    => Ratings Table – Viewer classification ratings


## 5. Features / Highlights
   
• Business Problem

    Streaming platforms like Netflix host massive amounts of content, making it difficult to:

      => Analyze content growth over time
      => Identify top-performing genres
      => Understand regional content distribution
      => Evaluate audience suitability based on ratings

      Without proper visualization, extracting insights from such data is complex.


• Goal of the Dashboard

    To develop an interactive dashboard that:

      => Tracks content growth over time
      => Analyzes country-wise and genre-wise distribution
      => Compares movies vs TV shows
      => Evaluates content ratings and audience segmentation
      => Enables data-driven content strategy insights
      
• Walkthrough of Key Visuals

    i) Key KPIs (Top Section)
  
        Total Content: 8807
        Total Countries: 124
        Total Movies: 6.13K
        Total TV Shows: 2.67K
        Total Genres: 43

        These KPIs give a quick overview of Netflix’s content library.


     ii) Filter Panel (Right Side)

        Allows users to dynamically explore the data.
        => Year filter
        => Country filter
      

     iii) Content Growth Trend (Line Chart)

        - Shows how content has grown over the years
        - Highlights rapid increase in recent years
    
     iv) Top 10 Countries by Content (Bar Chart)

        - Displays countries contributing the most content
        - Example: United States, India, UK
    
      v) Most Watched Content (Rating-wise Pie Chart)

        Distribution of content based on ratings:
        => TV-MA
        => TV-14
        => TV-PG
        => R
        => PG-13
          Helps understand audience targeting
    
      vi) Content Distribution (Country-wise Stacked Bar Chart)

        - Compares Movies vs TV Shows by country
        -  Shows content production preference across regions
    
      vii) TV Shows vs Movies (Donut Chart)

        - Visual comparison of total movies vs TV shows
        - Helps identify platform content strategy

      viii) Top 10 Genres (Table)

        Lists most popular genres like:
        - International Movies
        - Dramas
        - Comedies
        - Action & Adventure
          Helps understand viewer preferences
      
• Business Impact & Insights

      Content Strategy:
        - Netflix can identify which genres are most popular and invest accordingly.

      Regional Insights:
        - Understand which countries contribute the most content and expand production in high-performing regions.

      Audience Targeting:
        - Analyze ratings to tailor content for different age groups and preferences.

      Growth Analysis:
        - Track how content has scaled over time to evaluate platform expansion.

      Platform Optimization:
        - Balance between movies and TV shows based on user demand and trends.

# Dashboard Preview: 

link: https://github.com/rishirajpatidar5/Netflix_data_visualization_dashboard/blob/main/Netflix_data_visualisation_dashboard.png

# Conclusion

This dashboard provides a powerful and interactive way to explore Netflix’s content ecosystem. It transforms raw data into meaningful insights that can support strategic decisions in content production, regional expansion, and audience engagement.

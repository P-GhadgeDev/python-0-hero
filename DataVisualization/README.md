## Data Visualization

1. Data visualization is the graphical representation of data.
2. Data is just numbers until you turn it into a picture.

## Why Data Visualization?

1. Helps understand patterns quickly.
2. Makes data easier to explain.
3. Useful for business decisions.
4. Detects trends, outliers, and relationships.
5. Converts complex datasets into meaningful insights.

# Visualization Approaches

1. `With Code`:
   1. `Libraries`:
      1. Matplotlib
      2. Seaborn
      3. Plotly
      4. Cufflinks
   2. `Advantages`:
      1. Very high flexibility.
      2. Can customize every element.
      3. `Easy integration with`:
         1. Machine Learning pipelines
         2. Web applications
         3. Automation systems
      4. Better for developers and data scientists.
   3. `Disadvantages`:
      1. Requires coding knowledge.
      2. Slight learning curve.

2. `With Tools`:
   1. `Tools`:
      1. Power BI
      2. Tableau
      3. Google Data Studio.
   2. `Advantages`:
      1. Easy drag-and-drop interface.
      2. Quick dashboard creation.
      3. Business-user friendly.
   3. `Disadvantages`:
      1. Limited customization.
      2. Tough to integrate with ML pipelines.
      3. Licensing cost in some tools.
      4. Less coding flexibility.

## Origin Story of Visualization Libraries

1. `Matplotlib`:
   1. `Created by`:
      1. John Hunter (2003)
   2. `Inspired by`:
      1. MATLAB plotting style.
   3. `What is MATLAB?`:
      1. MATLAB is a high-level programming language and a numerical computing environment.
      2. `Used by`:
         1. Engineers
         2. Scientists
         3. Researchers
      3. `Mainly used for`:
         1. Mathematical computations
         2. Simulations
         3. Data analysis
         4. Visualization
      4. `Famous for`:
         1. Matrix operations
         2. Scientific computing

2. `Seaborn`:
   1. `Created by`:
      1. Michael Waskom
   2. `Background`:
      1. Neuroscientist
   3. `Purpose`:
      1. Simplify statistical visualization.
      2. Provide beautiful default themes.
   4. `Advantages`:
      1. Built on top of Matplotlib.
      2. Better default themes.
      3. Easier statistical visualization.
      4. Direct integration with Pandas DataFrames.

3. `Plotly`:
   1. Interactive visualization library.
   2. `Supports`:
      1. Zooming
      2. Hover effects
      3. Dynamic charts

4. `Cufflinks`:
   1. `Created by`:
      1. Santiago Pallandino
   2. `Purpose`:
      1. Connect Pandas directly with Plotly.
      2. Create interactive plots easily.

## Index

1. Matplotlib
2. Categorical Plots
3. Regression Plots
4. Distribution Plots
5. Matrix Plots
6. Cufflinks + Plotly
7. Great Capstone Project

## Matplotlib Basics

1. Importing Library
2. Basic Plot

## Subplots

1. Used to create multiple plots in a single figure.
2. Helpful for comparing charts.

## Object Oriented Approach

1. More professional and scalable approach.
2. Gives better control over plots.

## Figure Size and DPI

1. `Matplotlib allows`:
   1. Figure size
   2. Aspect ratio
   3. DPI (Dots Per Inch)
2. `figsize`:
   1. Width and height in inches.
3. `dpi`:
   1. Pixel density of image.

## Types of Plots

1. `Line Plot`:
   1. Used for trends over time.
2. `Scatter Plot`:
   1. Used to show relationships between variables.
3. `Bar Plot`:
   1. Used for categorical comparison.
4. `Histogram`:
   1. Used for frequency distribution.
5. `Box Plot`:
   1. Used to detect outliers and spread.
6. `Heat Map`:
   1. Used for correlation matrices.
7. `Area Plot`:
   1. Used to visualize cumulative trends over time.
   2. Similar to a line chart but the area beneath the line is filled.

## Categorical Plots

1. Count Plot
   1. Shows the count of observations in each category.

2. Bar Plot
   1. Compares numerical values across categories.
   2. Uses an estimator (mean by default).

3. Box Plot
   1. Displays the distribution of quantitative data.
   2. Helps compare distributions across categories.
      1. `Components`:
         1. Q1 (First Quartile)
         2. Median (Q2)
         3. Q3 (Third Quartile)
         4. Whiskers
         5. Outliers
      2. `Outliers`: 
         1. Determined using the Interquartile Range (IQR).
      
4. Violin Plot
   1. Similar to a box plot.
   2. Shows probability density.
   3. Displays distribution shape.
   4. Combines box plot and KDE.

5. Strip Plot
   1. Scatter plot where one variable is categorical.
   2. Shows all observations.
   3. Useful with box plots and violin plots.

6. Swarm Plot
   1. Similar to strip plot.
   2. Prevents overlapping points.
   3. Better visualization of distributions.
   4. Not suitable for very large datasets.

## Regression Plots

1. Shows relationship between variables.
2. Displays regression line.
3. `lmplot()`:
   1. `lmplot()` is a Seaborn function used to visualize linear relationships between variables.
   2. `Features`:
      1. Draws scatter plots with regression lines.
      2. Helps understand correlations between variables.
      3. Frequently used in exploratory data analysis and machine learning.
      4. Supports grouping using the hue parameter.

## Distribution Plots

1. Histogram
   1. Uses bins.
   2. Shows frequency distribution.

2. KDE Plot
   1. Smooth representation of distribution.
   2. Helps understand data density.

3. Jointplot
   1. Combines scatter plot with univariate distributions.
   2. Analyzes relationships between two variables.
   3. `Supports`:
      1. Scatter
      2. KDE
      3. Hex
      4. Regression

4. Pairplot
   1. Shows pairwise relationships among numerical variables.
   2. Creates scatterplots and histograms automatically.
   3. Useful for exploratory data analysis (EDA).

5. Matrix Plots
   1. Matrix plots are used to visualize relationships within a matrix-like dataset.
      1. `Types`:
         1. `Heat Map`:
            1. Represents data values using colors.
            2. Commonly used for correlation matrices.
         2. `Cluster Map`:
            1. Groups similar rows and columns together using hierarchical clustering.
            2. Useful for pattern identification.
         3. `Pivot Table Heat Map`:
            1. A heat map created from pivot table data.
            2. Helps identify trends and relationships quickly.

6. Rug Plot

## Plotly

1. Interactive visualization library.
2. `Supports`:
   1. Zooming
   2. Hover effects
   3. Dynamic charts

## Cufflinks + Plotly

1. Makes Plotly easier with Pandas.

## Saving Plots

1. `Common Formats`:
   1. PNG
   2. JPG
   3. PDF
   4. SVG

## Working with Images

1. Read Image

## Optional Designing

1. Choose proper chart type.
2. Avoid too many colors.
3. Keep labels readable.
4. Use titles properly.
5. Maintain proper spacing.
6. Highlight important insights.
7. Do not overload charts.
8. Simplicity improves understanding.

## Estimator Functions

1. You can change the estimator object to your own function that converts a vector to a scalar.
2. `Common estimators`:
   1. Mean (default) `np.mean`
   2. Median `np.median`
   3. Sum `np.sum`
   4. Count `len`
   5. Standard Deviation `np.std`
   6. Minimum `np.min`
   7. Maximum `np.max`

## Real-World Usage

1. Business dashboards
2. Sales analysis
3. Machine Learning visualization
4. Financial analytics
5. Healthcare analytics
6. Scientific research
7. Marketing insights
8. Stock market analysis

## Capstone Project Ideas

1. `IPL 2022 Capstone Project`:
   1. `Project Overview`:
      1. The Indian Premier League (IPL) is a professional Twenty20 cricket league in India featuring franchise teams representing different cities.
      2. `This project analyzes IPL 2022 match-level data to derive insights about`:
         1. Match outcomes
         2. Team performance
         3. Player performance
         4. Toss impact
         5. Venue influence
         6. Winning patterns

2. `Important Columns`:
   1. date `String/Date`
   2. venue `String`
   3. stage `String`
   4. team1 `String`
   5. team2 `String`
   6. toss_winner `String`
   7. toss_decision `String`
   8. first_ings_score `Integer`
   9. second_ings_score `Integer`
   10. match_winner `String`
   11. won_by `String`
   12. margin `Integer`
   13. player_of_the_match `String`
   14. top_scorer `String`
   15. highscore `Integer`
   16. best_bowling `String`
   17. best_bowling_figure `String`

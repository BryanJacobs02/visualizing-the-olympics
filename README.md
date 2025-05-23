# Visualizing the Olympics
*Final project for [INFO 526: Data Analysis and Visualization](https://infosci.arizona.edu/course/info-526-data-analysis-and-visualization) — University of Arizona*
  
  
## Project Intro/Objective
This project consisted of two parts: using logistic regression to gain insights on the effect player height has on team performance in Men's Olympic Basketball, and using time series analysis to study the performance of top countries over time.

Through studying player height, it was discovered that the median Men's Olympic Basketball player height was well above average, and has increased significantly over time. A mild correlation was found between player height and Olympic gold medal win porbability through logistic regression analysis. Important next steps in this section of the project would be to look into potential reasons for the increase in player height over time, as well as to create a more sophisticated logistic regression model. There are obviously many factors beyond height that are involved in winning basketball games, and a sophisticated multivariate logistic regression model could help quantify the impact of a multitude of traits. A model of this sort could help Team USA more effectively recruit players for their Olympic Basketball squad.

Time series analysis of medal count by country revealed the dominance of a few nations over the past two centuries. The most dominant nations consisting of the United States, Russia (and former Soviet Union), Germany, and Great Britain. Further research also yielded information on major spikes or drops in certain nation's medal counts. The boycott of the 1980 Moscow Games led by the United States led to a massive medal count increase for the Soviet Union, while the Soviet led boycott of the following 1984 Los Angeles games yielded a smilar medal count boom for the United States. Important next steps in this section of the project would be to study seemingly less related historical events and their impacts on nations' performances in the Olympic Games. This analysis could help us understand the greater reaching implications of political events, natural disasters, and more.
  
  
## Dataset
The TidyTuesday dataset used for this project can be accessed using the following link:
- [Dataset Link](https://github.com/rfordatascience/tidytuesday/blob/main/data/2024/2024-08-06/readme.md)
  
  
## Authors
**Bryan Jacobs**  
**Raja Sekhar Malireddy**  
**Arjun Kumar**  
**Sri Ram Theerdh Manikyala**  
**Vaishnav Mandlik**  
**Rafi Leviton**  
**Deepak Lingala**  
  
  
## Languages/Packages:
* R
  * tidyverse (ggplot2, dplyr)
  * ggridges
  * here
  * RColorBrewer
  * DescTools
  * grid
  * caTools
  * pROC
  * ggthemes
  * ggthemes
  * patchwork
  * gganimate
  * gifski
  * lubridate
  
  
## Software & Platforms
* RStudio / Quarto Markdown
* Quarto Dashboards
* GitHub


## Models & Methods
* Logistic Regression
* Time Series Analysis
* Density Plots
  
  
## Repository Structure
- **`data/`**: Contains supplementary world event data. TidyTuesday dataset too large for GitHub.
- **`code/`**: Contains `.qmd` files of code documentation with generated visuals. Files include:
  - `about.qmd`: introduces team members
  - `contract.qmd`: project management plan
  - `proposal.qmd`: project proposal
  - `EDA.qmd`: exploratory data analysis
  - `Q1_code.qmd`: code and visualizations associated with basketball analysis
  - `Q2_code.qmd`: code and visualizations associated with performance analysis by country
  - `dashboard.qmd`: Quarto dashboard for neat viewing of visuals
  - `index.qmd`: report for website rendering
- **`deliverables/`**: Contains `.pdf` files of final report and final presentation.
- **`README.md`**
  
  
## How To Run
#### To View Report or Presentation
1. Download and open desired `.pdf` files.

#### To Render Quarto-Generated Website
1. Make sure you have Quarto installed on your system.
2. Clone the repository.
3. Open any `.qmd` file (excluding `Q1_code.qmd`, `Q2_code.qmd`, and `EDA.qmd`) in RStudio.
4. Download `world_important_dates.csv` from `data/` folder and TidyTuesday dataset, place in correct directory.
5. Press `Render`. You should be automatically redirected to a website where you can view the dashboard, report, and more.

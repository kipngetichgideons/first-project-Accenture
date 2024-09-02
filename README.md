# My first Data analysis project simulation on Accenture
Data analysis of content categories and user reactions for Social Buzz to optimize content strategy and enhance user engagement.
```markdown
# Content Category Analysis for Social Buzz

## Project Overview

**Objective:**  
The goal of this project is to analyze the content categories and user reactions on the Social Buzz platform to help optimize content strategy, improve user engagement and align content with user preferences.

**Client:**  
Social Buzz - A rapidly growing social media platform focusing on content creation and user interaction.

**Date:**  
August 24, 2024

**Analyst:**  
Gideon

## Problem Statement

Social Buzz has experienced massive rapid growth, leading to an overwhelming amount of user generated content and reactions. The company needs to understand which content categories drive the most engagement and how user sentiment varies across content types. *The goal is to use this understanding to optimize content strategy and enhance user engagement.*

## Project Process

### 1. Data Understanding

- **Data Sources:**  
  - **Content Data:** Information on the types of content posted or uploaded on Social Buzz.
  - **Reactions Data:** User reactions to the content, including likes, dislikes and comments.
  - **Reaction Types Data:** Different types of user reactions available on the platform.

- **Key Attributes Identified:**  
  - `category` - The category to which the content belongs.
  - `reaction` - The type of reaction the user gave.
  - `datetime` - The date and time when the reaction was recorded.

### 2. Data Modeling

- **Data Cleaning:**
  - Removed inconsistencies and standardized categorical columns (e.g., converting text to lowercase and removing apostrophe on some variables).
  - Converted the `datetime` column to a proper date format.
  
- **Data Merging:**
  - Merged the cleaned datasets (`content`, `reactions`, `reaction_types`) to create a comprehensive dataset for analysis. *Name of the dataset 'accenture_dataset'.*

### 3. Data Analysis

- **Top 5 Content Categories:**
  - Identified the content categories with the highest number of user reactions.

- **Sentiment Analysis:**
  - Analyzed how user sentiment varies across different content types, focusing on positive and negative reactions.

- **Temporal Analysis:**
  - Examined user engagement over time to identify peak periods for posting.

### 4. Uncover Insights

- **Key Insights:**
  - **Top 5 Content Categories:** 'Animals' leads in user reactions, while 'Public speaking' is the least engaged.
  - **Sentiment Analysis:** 'Photo' content receives the most positive reactions, while 'Audio' content is less engaging.
  - **User Engagement Over Time:** Engagement peaks in specific months, with positive sentiment increasing over time.

## Key Findings

- **Unique Categories:**  
  The platform has 22,534 unique content categories.

- **Reactions to Most Popular Category:**  
  The 'Animals' category has the highest number of reactions, with a total of  1,738 reactions.

- **Month with Most Posts:**  
  The month of Jan and May 2921 recorded the highest number of posts.

## Recommendations

- **Focus on High-Engagement Categories:**  
  Promote and create more content in top-performing categories like 'Animals' to drive engagement.

- **Optimize Low-Engagement Areas:**  
  Reassess and improve content strategies for less engaged categories, such as 'Public speaking'.

- **Leverage Sentiment Analysis:**  
  Use sentiment insights to tailor content that resonates more positively with users, particularly in the 'Photo' category.

## How to Run the Analysis

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kipngetichgideons/first-project-Accenture/accenture_analysis.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd accenture_analysis
   ```

3. **Install Required Packages:**
   Ensure you have the required R packages installed. You can do this by running:
   ```r
   install.packages(c("tidyverse", "janitor", "plotly", "visdat", "esquisse", "inspectdf", "gtsummary", "labelled", "ggthemes"))
   ```

4. **Load and Run the R Script:**
   Open the R script file `accenture_analysis.R` in RStudio and run the code to replicate the analysis and generate the visualizations.

## Project Files

- **`accenture_analysis.R`** - The R script containing the data cleaning, modeling, and analysis code.
- **`Content.csv`** - The dataset containing content information.
- **`Reactions.csv`** - The dataset containing user reactions.
- **`Reaction_types.csv`** - The dataset containing different types of user reactions.
- **`README.md`** - This file, providing an overview of the project.

## Contact Information

For any questions or further information, please contact:
- **Name:** Gideon Kipngetich
- **Email:**kipngeticgideons@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```


# Chain_Reaction_Repository

#Supply Chain Technology Final Project - Team Chain Reaction

## Project Overview
#Our data is about export trade from multiple countries, but focused on trade from country A to country B in said year. The data set also included how much money in USD was being traded between country A and country B in said year. We want to know, which trade partners or commodities are most critical to global supply chains?

## Austin Fiber, Cylie Leidy, Lindsay Gaul, Logan Kalman, Sydney Dews

##Repo Structure
- '/data/' - raw and cleaned datasets
- '/notebooks/' - Python Jupyter Notebooks
- '/simulation/' - AnyLogic models (.alp files)
- '/docs/' - Reports, slides, and instructions

  ##How to Run
  1. Clone repo
  2. Install dependencies: 'pip install -r requirements.txt'
  3. Run notebooks in '/notebooks/'
  4. Open AnyLogic models in '/simulation/'
 
     ## Deliverables
     # Deliverable 1
# To choose the kind of prediction model, first, we had to look at our dataset. Our dataset covers export trade from multiple countries, while focusing on trade from Country A to Country B. Our goal is to identify which trade partners or commodities are most critical to global supply chains.
The link below gives an overview of every prediction model. After reviewing the pros and cons of every model and comparing it to the dataset, we decided that a time series model would be the best fit for us and our project. 
A time series model is the best fit for our trade data because it looks at how things change over time. Our data shows how much money was traded between country A and country B each year, so it’s already set up in a way that works well with this kind of model. Time series models help you see patterns, like if trade is going up, going down, or changing with the seasons. They can also spot big changes caused by world events, like new laws or supply chain problems.
Unlike simple averages, which just give you one number, time series models can show how trade is growing or shrinking. They can also make better guesses about the future. Since our data includes many countries and products, this model can help us look at all of them at once and find out which ones are most important. That way, you can figure out which trade partners or goods matter most to the global supply chain and where problems might show up.

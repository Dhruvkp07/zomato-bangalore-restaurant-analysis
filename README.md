# Zomato Restaurant Data Analysis - Bangalore


## What Got Me Started on This

Ever wondered what makes some restaurants more popular than others in Bangalore? With so many dining options available, I was curious to dig into the data and see what patterns emerge from actual customer behavior on Zomato.

Working with over **51,000 restaurant records** from Bangalore, this project became a fascinating exploration of the city's dining landscape.

## The Dataset That Told a Story

This wasn't just any dataset - it was real business data from Zomato with:
• **51,717 restaurant records** across Bangalore
• Everything from street food joints to fine dining
• Customer ratings, pricing, locations, and service options
• Real messy data that needed serious cleaning (just like real-world projects!)

## What I Discovered Along the Way

**The Cleaning Challenge:**
The data was pretty messy when I started - ratings were in formats like "4.1/5", costs had commas everywhere, and there were inconsistent location names. Spent quite a bit of time standardizing everything, but that's half the fun of real data work!

**Interesting Patterns I Found:**
• **Online vs Offline**: Way more restaurants offer online delivery than table booking - makes sense given Bangalore's traffic!
• **Location Hotspots**: Koramangala and BTM are restaurant goldmines (no surprise to anyone who's lived in Bangalore)
• **The Popularity Paradox**: Just because a restaurant has many outlets doesn't mean it has the highest ratings or costs
• **Cost Distribution**: Found some fascinating patterns in how pricing varies across different areas

## My Approach to the Analysis

**Data Wrangling:**
• Cleaned up rating formats (converted "4.1/5" to proper numbers)
• Standardized cost data (removed commas, converted to float)
• Grouped less frequent restaurant types into 'Others' for cleaner analysis
• Consolidated similar locations (like all the Koramangala sub-areas)

**Exploration & Insights:**
• Analyzed online ordering vs table booking trends
• Mapped restaurant distribution across Bangalore
• Compared costs and ratings for popular restaurant chains
• Looked at what drives customer satisfaction

## Tools I Used

• **Python** for the heavy lifting
• **Pandas** for data manipulation (lots of it!)
• **NumPy** for calculations
• **Matplotlib & Seaborn** for visualizations
• **Google Colab** as my analysis playground

## Key Findings That Surprised Me

**Service Preferences:**
• Most restaurants focus on delivery over dine-in experiences
• Table booking is still not widely adopted

**Geographic Patterns:**
• Clear clustering of restaurants in tech hubs
• Different areas have distinct pricing patterns

**Business Insights:**
• Popular restaurant chains don't always have the highest ratings
• There's no direct correlation between outlet count and customer satisfaction

## What's in This Repository

• `notebooks/zomato_bangalore_analysis.ipynb` - Complete analysis journey
• `README.md` - This overview

## Dive Into the Analysis

[Open in Google Colab](https://colab.research.google.com/drive/1JyINv0Bq6xDjb7mVq9bnm_E2PpAsv1YE?usp=sharing)

## What This Project Taught Me

Working with real business data is messy but rewarding. This analysis could actually help:
- **Restaurant owners** understand market positioning
- **Customers** make better dining choices
- **Zomato** optimize their platform features

The scale of this dataset (51K+ records) taught me a lot about handling large datasets and extracting meaningful business insights from real-world data.

## Future Ideas

I'm thinking of extending this with:
• Sentiment analysis on customer reviews
• Predictive modeling for restaurant success
• Geographic clustering analysis
• Time-series analysis of rating trends.

## Contact

Dhruvkp07 - [LinkedIn](https://www.linkedin.com/in/dhruv-kumar-463b27290/) | [Email](kdk751666@gmail.com)

---
*Exploring Bangalore's food scene, one data point at a time! 🍽️📊* .

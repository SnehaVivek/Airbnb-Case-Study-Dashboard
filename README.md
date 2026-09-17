Airbnb Market Insights Dashboard

An interactive Power BI dashboard designed to analyze Airbnb listing performance, pricing patterns, neighbourhood demand, room-type distribution, and proximity to the city centre.

This project demonstrates an end-to-end data analytics and business intelligence workflow, from raw Excel data preparation and Power Query transformation to data modelling, DAX analysis, and interactive dashboard development.
<img width="1390" height="788" alt="image" src="https://github.com/user-attachments/assets/80cf7e60-6851-430c-ba85-d5cddb35543e" />


Project Overview

The Airbnb Market Insights Dashboard provides a consolidated view of Airbnb listing data across neighbourhoods and city zones.

The dashboard explores key business questions including:

Which city zones generate the highest review activity?

How does price vary across neighbourhoods and room types?

Which neighbourhoods show stronger guest activity?

How are listings and reviews distributed across room types?

Does distance from the city centre relate to price or review activity?

How do superhost listings vary across neighbourhoods?



Project Objectives

Clean and standardize raw Airbnb listing data.

Combine listing-level data with neighbourhood information.

Create meaningful KPIs for pricing, reviews, and location.

Analyze differences across city zones and neighbourhoods.

Build an interactive and visually intuitive Power BI dashboard.

Translate raw data into actionable business insights.



Dataset

The project uses an Excel workbook containing two primary datasets.

1. Listings

Column

Description

Listing ID

Unique identifier for each Airbnb listing

Neighbourhood

Area where the listing is located

Room Type

Type of accommodation offered

Price

Listing price

Number of Reviews

Total reviews received by the listing

Reviews Per Month

Average monthly review activity

Superhost

Indicates whether the host is a superhost

2. Neighbourhood_Info

Column

Description

Neighbourhood

Name of the neighbourhood

City Zone

Central, North, South, East, or West zone

Distance to Center (km)

Distance from the city centre



Tools & Technologies

Tool

Purpose

Microsoft Excel

Raw data source

Power Query

Data cleaning and transformation

Power BI

Data modelling, visualization, and dashboard development

DAX

KPI and analytical calculations

GitHub

Version control and project documentation

Data Preparation & Transformation

The raw Airbnb data was prepared and transformed before analysis.

Key transformation steps:

Imported both Excel datasets into Power BI.

Removed blank and incomplete records.

Trimmed unnecessary spaces from text fields.

Standardized neighbourhood and room-type values.

Converted price fields into appropriate numeric data types.

Checked missing values and corrected data types.

Combined listing data with neighbourhood-level information.

Created analytical fields for city-zone and room-type analysis.

Validated aggregations and totals before developing visuals.

Created DAX measures for dashboard KPIs and analysis.

Dashboard Features

KPI Cards

The dashboard includes key metrics such as:

Total Reviews

Average Listing Price

Average Distance from City Centre

High-Demand Neighbourhood

Visual Analysis

Dashboard Visual

Purpose

Reviews by City Zone

Compares review activity across different zones

Price by City Zone

Highlights pricing differences between zones

Total Price by Room Type

Compares price contribution across room types

Reviews by Room Type

Examines review activity across accommodation categories

Average Price by Neighbourhood & Room Type

Analyzes the relationship between location, room type, and pricing

Neighbourhood Summary

Provides neighbourhood-level review and superhost information

Average Distance by Neighbourhood

Compares neighbourhood proximity to the city centre



Key Insights

1. Review activity differs across city zones

The city-zone analysis highlights differences in review activity across Central, South, East, North, and West zones, helping identify areas with comparatively higher guest engagement.

2. Entire homes/apartments represent a significant share of pricing

The room-type analysis shows that entire homes/apartments contribute substantially to the total price value represented in the dataset.

3. Room type and location influence pricing

Average prices vary across neighbourhoods and accommodation types, indicating that both location and room type are important dimensions when examining Airbnb pricing patterns.

4. Guest activity is uneven across neighbourhoods

Some neighbourhoods receive substantially more reviews than others. Review volume can serve as an indicator of guest activity, although it should not be treated as a direct measure of bookings.

5. Distance provides additional market context

Comparing neighbourhood distance with price and review activity provides additional context for understanding how proximity to the city centre relates to Airbnb market characteristics.

Note: This analysis is based on the supplied case-study dataset. Review counts are used as an activity indicator and should not be interpreted as exact booking, occupancy, or revenue figures.

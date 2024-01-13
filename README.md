```    
Business Insights 360 
```

## Project Introduction

Welcome to the Business Insights 360 project, where data meets innovation! In this PowerBI implementation, I've tailored my analytics journey based on the Codebasics PowerBi Course, providing a unique perspective to our data-driven decision-making process.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYjgwZWQ3MDktYzU5MS00YjMxLThhY2YtZmMyNGE2OTAzMTdiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&embedImagePlaceholder=true)

## Table of Contents

- [Company’s Background](#companys-background)
- [Tech Stacks](#tech-stacks)
- [PowerBI Techniques Implemented](#powerbi-techniques-implemented)
- [Business-Related Terms](#business-related-terms)
- [Project Kick-off Session](#project-kick-off-session)
- [Dataset Understanding](#dataset-understanding)
- [Data Modeling](#data-modeling)
- [Dashboard Designing](#dashboard-designing)
- [Outcome of the Project](#outcome-of-the-project)

## Company’s Background

Atliq Hardware, a rapidly expanding company in the computer and accessories market, has established a global presence. Specializing in the sale of computers and related products, the company operates through three primary channels: Retailers, Direct sales, and Distributors.

Despite its recent growth, Atliq Hardware encountered unexpected losses with the opening of a store in America. The decision was influenced by surveys, intuition, and some Excel analysis. Additionally, the competitive landscape revealed that rival companies benefit from robust analytics teams, enabling them to make informed, data-driven decisions.

In response to these challenges, Atliq Hardware recognizes the need to bolster its analytical capabilities. The company has initiated a project to establish an analytics team dedicated to deriving insights from data. This strategic move aims to enhance decision-making processes, ensuring a more resilient and competitive position in the industry.

## Tech stacks

- SQL
- Excel
- PowerBi 
- DAX
- DAX studio (for optimizing the report)
- Project charter file

## PowerBI Techniques Implemented

The approach delves into a customized visualization strategy, exploring:

- Questions to be asked before starting with dashboarding.
- ETL methodology (Extract, Transform, Load)in Power Query.
- Tailored calculated columns.
- Uniquely crafted measures using DAX language.
- Innovative data modeling.
- Creative use of Buttons, Parameters, Bookmarks for seamless visual transitions.
- Intuitive page navigation with custom buttons.
- Advanced divide function applications.
- Dynamic titles based on applied filters for a personalized experience.
- Distinct KPI indicators for a nuanced understanding.
- Creative conditional formatting techniques using icons or background colors.
- Data validation strategies that align with our unique business needs.
- Comprehensive PowerBi services integration.


## Business-Related Terms

Navigate the customized analytics landscape with an understanding of terms such as:

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGS - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Project Kick-off Session

The project kick-off session serves as a pivotal starting point, addressing fundamental questions to clarify the project's purpose and objectives:

- **1.  Project Scope and Objectives**: Define the extent and goals of the analytics project.
- **2.  Performance Metrics**: Establish criteria for measuring the success of the project.
- **3.  Timeline**: Determine the project's time frame and deadline for completion.
- **4.  Stakeholder Involvement**: Assess whether stakeholders expect a preview before the official release.
- **5.  Stakeholder Expectations and Concerns**: Understand the hopes and fears of stakeholders regarding the project.
- **6.  User Base**: Identify who will be using the analytics dashboard and for what purposes.
- **7.  Expected Outcomes**: Define the expectations stakeholders have upon the project's completion.
- **8.  Risk Assessment**: Anticipate potential challenges and issues that may arise during the project.
- **9.  Resource Requirements**: Identify the data and resources needed to build a robust analytics dashboard.
- **10. Stakeholder Input on Design**: Seek feedback and preferences from stakeholders regarding the dashboard's design and visual elements.

This comprehensive kick-off session sets the stage for a strategic and well-informed approach to building an analytics team and leveraging data-driven insights for future decision-making.
	
## Dataset Understanding

Understanding the available dataset is a crucial step before delving into analysis. It provides a solid foundation for informed decision-making. The dataset comprises two key components:

```python    
Dimension Table:
```
This table contains static data detailing customers and products. 

### ``dim_customer:``

- Encompasses 27 distinct markets.
- Represents 75 distinct customers across the markets.
- Classifies platforms into Brick & Mortars (physical/offline stores) and E-commerce (online stores like Amazon and Flipkart).
Three primary channels: Retailer, Direct, and Distributors.

### ``dim_market:``
 - Involves 27 distinct markets, with sub-zones and regions (APAC, EU, nan, LATAM).
dim_product:
 - Organized into divisions (P & A, PC, N & S) and further categorized into 14 types, such as Peripherals, Accessories, Notebook, Desktop, Networking, and Storage.


```python 
Fact Table:
```
Dedicated to transactional data, this table holds information about various transactions.

### ``fact_forecast_monthly:``
- Utilized for forecasting customer needs in advance, aiding in enhancing customer satisfaction and optimizing warehouse costs.
Denormalized by the data engineering team for analytical work.
Dates in the month are replaced with the start date, and the table concludes with forecast quantities needed by customers.


``fact_sales_monthly:``
- Similar to fact_forecast_monthly, with the last column containing the actual sold quantities instead of forecast values.
gdb056:

``freight_cost:``
- Details travel costs and other expenses for each market, organized by fiscal year.

``gross_price:``
- Contains details of gross prices with associated product codes.

``manufacturing_cost:``
- Provides information on manufacturing costs associated with product codes and years.

``Pre_invoice_dedutions:``
- Outlines pre-invoice deduction percentages for each customer, categorized by year.

``Post_invoice_deductions:``
- Encompasses post-invoice deductions and additional details.
This comprehensive dataset serves as the bedrock for our analytical work, facilitating insights into customer behaviour, market dynamics, and cost considerations. 
	
## [Data Modeling](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Data%20Model.png)	
	
1. Fundamental Role of Data Modeling:
   - Data modeling is the essential foundation for our reporting, shaping all visual elements.
2. Impact of Poor Data Modeling:
   - Subpar data modeling significantly hampers overall report performance.
3. Importance of Best Practices:
   - Adherence to data modeling best practices is crucial for effective analytics.
4. Adoption of Snowfall Data Modeling Method:
   - The project follows the Snowfall data modeling method.This method ensures a structured foundation, facilitating seamless data integration into visuals.
5. Objective:
   - Prioritizing sound data modeling practices enhances overall reporting quality and performance.
   
   
## Dashboard Designing

Our visuals are not just reports; they are a journey. Based on unique mock-ups, I've designed visuals and measures that align with distinctive business landscape.

### Dashboard

[Click here to run interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjgwZWQ3MDktYzU5MS00YjMxLThhY2YtZmMyNGE2OTAzMTdiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&embedImagePlaceholder=true)

### [Home View](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Home%20View.png)

Navigate through our Home view, where every button leads to a tailored experience:

- ### Finance View
  ![Finance View](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Finance%20View.png)
- ### Sales View
  ![Sales View](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Sales%20View.PNG)
- ### Marketing View
  ![Marketing View](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Marketing%20View.PNG)
- ### Supply Chain View
  ![Supply Chain View](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Supply%20Chain%20View.PNG)
- ### Executive View
  ![Executive View](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Executive%20View.PNG)
- ### [Info
  ![Info](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Info.PNG)
- ### Support
  ![Support](https://github.com/HIMANyadav/PowerBI--Atliq_Business_Insight_360/blob/main/Visuals/Support.PNG)


## Outcome of the Project:
The report not only facilitates data-driven decision-making but also serves as a key resource for addressing a multitude of "why" questions arising in different situations. The insights derived from the report contribute significantly to informed decision-making processes, offering a holistic understanding of the underlying data.

=============================================


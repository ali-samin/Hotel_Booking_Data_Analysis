# Hotel Booking Data Analysis

## Project Overview
This project involves analyzing hotel booking data to understand and address high cancellation rates for City Hotels and Resort Hotels. The analysis aims to provide actionable insights to improve booking management, optimize pricing strategies, and enhance customer experience, ultimately helping hotels increase revenue and efficiency.

## Business Problem
City Hotels and Resort Hotels have been experiencing high cancellation rates, leading to reduced revenues and suboptimal room usage. The primary goal is to lower cancellation rates to enhance revenue generation and efficiency. This report focuses on analyzing the factors affecting cancellations and providing business recommendations to address these issues.

## Dataset
The dataset used includes detailed information about hotel bookings with the following key features:
- **Hotel Type**: City Hotel or Resort Hotel
- **Lead Time**: Number of days between the booking date and the arrival date
- **Arrival Date Year, Month, and Day**
- **Number of Adults**
- **Number of Children**
- **Number of Babies**
- **Meal Plan**: BB (Bed & Breakfast), HB (Half Board), FB (Full Board)
- **Country**: Country of origin of the guest
- **Market Segment**: Market segment through which the booking was made
- **Distribution Channel**: Channel through which the booking was made (e.g., Direct, Corporate)
- **Is Canceled**: Whether the booking was canceled (1 for yes, 0 for no)
- **Booking Changes**: Number of changes made to the booking
- **Deposit Type**: Type of deposit made (e.g., No Deposit, Non Refund)
- **Customer Type**: Type of customer (e.g., Transient, Contract)
- **ADR**: Average Daily Rate (price per night)
- **Required Car Parking Spaces**
- **Total of Special Requests**

## Business Problem & Assumptions
### Business Problem
- High cancellation rates impacting revenue and room usage for City and Resort Hotels.
- Objective: Reduce cancellation rates to increase efficiency and revenue.

### Assumptions
1. No significant unusual occurrences between 2015 and 2017 will impact the data.
2. Data remains relevant and applicable for current analysis and decision-making.
3. There are no unforeseen negative effects from implementing recommended strategies.
4. Hotels are not currently using the suggested solutions.
5. Booking cancellations are a major factor affecting revenue.
6. Cancellations are made within the same year as the bookings.

## Research Questions
1. What variables affect hotel reservation cancellations?
2. How can we improve the hotel reservation cancellation rates?
3. How can hotels be assisted in making pricing and promotional decisions?

## Hypotheses
1. Higher prices lead to more cancellations.
2. Longer lead times are associated with higher cancellation rates.
3. A majority of reservations come from offline travel agents.

## Analysis and Findings
- **Cancellation Rates**: Significant proportion of reservations are canceled, impacting hotel revenue.
- **City vs. Resort Hotels**: Resort Hotels have higher booking rates but also higher cancellation rates.
- **Pricing Trends**: Higher prices correlate with higher cancellation rates.
- **Booking Patterns**: August shows the highest number of reservations, while January has the most cancellations.
- **Reservation Sources**: Online travel agencies account for a large proportion of reservations, with direct bookings being less common.
- **Country Analysis**: Identifying countries with the highest cancellation rates.

## Suggestions
1. **Pricing Strategy**: Adjust pricing strategies to lower rates for specific hotels based on location and provide discounts to reduce cancellations.
2. **Discounts on Peak Days**: Offer reasonable discounts on weekends and holidays, especially for Resort Hotels where cancellations are more frequent.
3. **Marketing Campaigns**: Implement marketing campaigns in January to boost reservations and reduce cancellations during this peak cancellation month.
4. **Service Quality**: Enhance the quality of services and accommodations, particularly in high-cancellation regions like Portugal, to reduce cancellation rates.

## Technology Stack
- **Python**: For data analysis and visualization.
- **Pandas & NumPy**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For exploratory data analysis and reporting.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ali-samin/Hotel_Booking_Data_Analysis.git

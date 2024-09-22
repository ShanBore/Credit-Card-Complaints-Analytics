# Credit Card Complaint Dashboard
## Background and Overview
The Credit Card Complaint Dashboard is a Tableau-based visualization project aimed at analyzing and summarizing consumer complaints received by major financial institutions regarding credit card services. This project utilizes data on complaints recorded during 2019 - 2021, their resolution statuses, and trends over time to provide insights into key problem areas, company performance, and consumer sentiment.

Insights and recommendations are provided on the following key areas:  

* Total complaints received and timely resolution  
* Most common types of complaints  
* Consumer preferences in communication channels  
* Company responsiveness and performance trends  
* Geographic distribution of complaints  
  
The dashboard helps companies better understand customer pain points, assess their handling of complaints, and identify opportunities for enhancing customer satisfaction. You can view it [here](https://public.tableau.com/app/profile/shan.bore/viz/CreditCardComplaintDashboard_17014032352930/Dashboard1).

## Data Structure Overview
The dataset used in this dashboard contains multiple fields, including:

* ***Company:*** The financial institution receiving the complaint.
* ***Complaint Category:*** The type of complaint, such as "Billing disputes" or "Identity theft."
* ***Company response:*** How the company responded, including "Closed with explanation" and "Closed with monetary relief."
* ***Date received:*** When the complaint was submitted.
* ***Submitted via:*** The method used to submit the complaint, including "Web" or "Phone."
* ***Timely response:*** Indicates whether the company responded within a reasonable timeframe.
* ***Receiving channels:*** The channels through which complaints were filed (web, phone, referral, etc.).
## Executive Summary
Overview of Findings:  
Over the course of 2019 to 2021, the dashboard captures 86,893 total complaints, with the following notable metrics:

![Screenshot 2024-09-22 at 4 12 10 PM](https://github.com/user-attachments/assets/90336e5e-6d14-40d5-a657-ace259e3ba67)
* 2020 marked the peak in complaints, with 20,875 complaints, largely due to the impact of the COVID-19 pandemic.
  
 ![Screenshot 2024-09-22 at 3 31 36 PM](https://github.com/user-attachments/assets/e61d3262-63c4-4b46-84a6-1956358c2db3)
* Billing disputes accounted for the highest volume of complaints across all three years, consistently making up around 19% of total complaints.
* 69% of all complaints were submitted via web channels, highlighting the importance of digital platforms.
* Companies maintained a strong timely response rate, exceeding 97% each year.
### Trends:

![Screenshot 2024-09-22 at 4 18 32 PM](https://github.com/user-attachments/assets/a2bebebb-40a9-48b6-9580-c5e9ec2297fd)
* ***Complaint Volume Trends:*** 2020 saw the highest number of complaints, with a sharp decrease in 2021 (down to 5,604 complaints). This trend might indicate improvements in complaint handling or external factors such as pandemic recovery.
  
* ***Response Patterns:*** The most common resolution was "Closed with explanation" (~59.7% of cases), followed by "Closed with monetary relief" (~20%), which decreased slightly in 2021.  
### Performance:
* ***Company Responsiveness:*** Companies consistently closed over 97% of complaints in a timely manner, reflecting an effective resolution system.
* ***Top Complaint Categories:*** "Billing disputes" consistently ranked as the most frequent complaint, followed by issues related to "Identity Theft/Fraud" and "Closing/Cancelling Account."
## Insights Deep Dive
### Peak in Complaints in 2020
In 2020, complaints reached their peak with 20,875 total complaints, a significant rise from 17,149 in 2019. However, this trend dramatically reversed in 2021, with the number of complaints dropping to 5,604. The surge in 2020 can likely be attributed to the financial disruptions caused by the COVID-19 pandemic, which saw more consumers facing billing, fraud, and account-related issues.

### Billing Disputes Are the Most Common Complaint
Across all three years, Billing Disputes consistently accounted for the largest portion of complaints. In 2021 alone, 1,083 billing disputes made up 19.33% of all complaints. This persistent issue suggests that many customers are struggling with billing clarity or errors, highlighting an area where companies can focus on improving their billing systems and customer communication.

### Web Is the Preferred Complaint Submission Channel
Consumers clearly prefer using web platforms to submit their complaints, with 76.55% of complaints in 2021 submitted through the web, a trend that remained steady in both 2020 and 2019. The predominance of digital submissions underscores the importance of companies optimizing their online support systems to handle a large volume of inquiries and issues effectively.

### Declining Trend in Monetary Relief
Monetary relief provided for complaints has been decreasing. In 2020, 21.01% of complaints were resolved with monetary compensation, whereas in 2021, this dropped to 18.50%. This indicates a shift in companies' resolution strategies, with more emphasis on providing explanations or other non-monetary solutions. While this may help reduce costs, companies must ensure that these alternatives still meet customer expectations.

### Strong Timely Response Rate
Companies have consistently maintained a timely response rate of over 97% in closing complaints across all three years. This reflects strong operational efficiency in managing and resolving customer issues, but certain complaint categories like Identity Theft/Fraud—which frequently appeared as a top issue—suggest that more targeted measures, such as enhanced fraud detection and customer education, are needed to further reduce these types of complaints.


## Recommendations
***1. Focus on Addressing Billing Disputes:***  
Billing disputes have consistently accounted for the highest volume of complaints, indicating the need for a targeted strategy. This could involve proactive error detection in billing systems, clearer communication of billing policies, and enhanced customer support for disputed transactions.

***2. Enhance Digital Support for Web Submissions:***  
Since the majority of complaints (over 75%) are submitted via the web, investing in more sophisticated digital support tools, including AI-powered chatbots or expanded self-service options, could reduce the need for formal complaints by resolving common issues upfront.

***3. Improve Transparency in Complaint Resolutions:***  
With 63-67% of complaints being closed with explanations, companies should ensure that these explanations are comprehensive and satisfactory to customers. Further, automating follow-up feedback after explanations are provided could identify unresolved issues sooner. 

***4. Strengthen Fraud Detection for Identity Theft Complaints:***  
Identity Theft/Fraud consistently ranks high in complaint types. Investment in fraud detection and prevention, as well as customer education around security practices, could mitigate future complaints in this category.

***5. Address Regional Complaint Disparities:***  
The geographic density maps suggest certain regions have disproportionately high complaints. Focusing resources and tailored solutions to these regions could help lower complaint volumes.

# E-mail-Marketing-Campaign-Project
This project analyzes email marketing campaign performance using SQL and Python. The dataset consists of tables tracking campaign sends, user engagement through opens, clicks, and unsubscribes.

# Background
The goal is to answer a series of analytical questions (based on a LinkedIn SQL practice challenge) and extract insights that may show why there are certain behaviors.

The questions were:

Which campaigns had the highest and lowest unsubscribe rate?

Do certain campaign categories(promotion,newsletter,re-arrangement,announcement) have higher unsubscribe rates?

What is the Overall_unsubscribe_rate?

Which region(s) or device types(s) have the highest unsubscribe rate?

What are the common unsubscribe reasons, and do they vary by campaign category?

What's your final story?

# Tools I used
SQL: Query and explore the dataset.

SQLite: Database Management System.

Python: For further analysis.

Power BI: For visualization of the data.

# Key Findings


Campaign 2 has the highest unsubscribe rate at 5.87% in comparison to Campaign 13 which has the lowest rate at 3.4%. Another interesting observation is that Campaign 13 is a newsletter while Campaign 2 is a re-engagement. Based on the other results, it might not be a big factor in reducing the unsubscribe rate but it is worth mentioning that in the next section, the category with the lowest rate is the newsletter.


Promotions have the highest unsubscribe rate at 5.36% and newsletters are the lowest with 4.82%. This indicates that while the previous observation of re-engagements as a category do not correlate with higher rates of unsubscribing, it does give us a better picture of the possibility of what is written in each category that might affect a user’s choice of unsubscribing or not. 

The overall unsubscribe rate is at 5.05%. The average rate across all industries is under 2%. Indicating that the campaign for this company is over the average rate.


For newsletters, the reason why a lot of users unsubscribe is due to privacy concerns at 116 users while the re-engagement category is at 43 users. The top 3 categories are also in the newsletter section but for differing reasons such as finding better brands or too many emails. This gives us more information on what the company may be struggling in terms of what users want from the company.

 
Mobile and tablets are at the top when it comes to the number of total unsubscribes. Regions in Asia and Europe, 8860 and 8840 users respectively, are most likely to unsubscribe compared to their other regional counterparts. From this observation, there could be an implication that since users tend to spend more time on their tablets and mobile phones, they might be more likely to unsubscribe compared to using a desktop.


# Recommendations

Overall, these findings suggest that the email campaign has a higher rate compared to the average when it comes to user unsubscription rates. Here are some recommendations to combat these obstacles: 

### Improve Content Relevance and Quality

Tailor content based on user behavior and preferences. Use segmentation to target users with specific interests. Reduce the frequency of emails, especially for re-engagements and promotions. Too many emails can lead users to unsubscribe. Continue monitoring surveys and see if the reasons end up changing or not.

### Address Privacy Concerns

Ensure that privacy policies are transparent and easy to understand. Highlight how user data is protected and used, alleviating user concerns. Offer options for users to manage their preferences regarding data sharing and marketing communications.

### Improve Mobile Experience

Ensure that emails are optimized for mobile devices, given the high unsubscribe rates from mobile users. A clean, responsive design can help user experience. Regularly test different designs and layouts to determine which formats yield better engagement rates on mobile and tablets.

### Engagement Strategies

Consider implementing loyalty rewards or incentives for continued engagement. Recognizing loyal subscribers can reduce churn. Develop targeted campaigns specifically aimed at users who have shown signs of disengagement. Personalized re-engagement emails can rekindle interest.

Regional Tailoring

Be mindful of regional preferences. Customize content to align with cultural norms and expectations. Schedule email sends based on recipients' time zones to optimize open rates and reduce the likelihood of emails being ignored.


# Customer-Engagement-Analysis

## Case Description
During the year 2022, heightened anticipations surrounded the growth trajectory of the 365 company and the augmented student engagement attributed to the debut of novel features on the website platform. Among these features was an XP system empowering students to monitor their advancement, level up, and garner rewards through the completion of diverse learning objectives. Furthermore, the platform offered in-app coins exchangeable for special accolades, a leaderboard fostering competitive spirits across various divisions, weekly rewards, and ladder ascensions, along with streaks designed to incentivize consistent learning habits. Additionally, the company broadened its course library, encompassing a wider spectrum of topics to furnish students with a more comprehensive skill set and entice a larger audience. These enhancements were poised to bolster the student experience, devise an efficacious customer engagement strategy, and propel the company's prosperity in the forthcoming period. Through this Customer Engagement Analysis in Excel project, the objective is to assess whether the newly incorporated features have indeed elevated student engagement levels.


## Project Files
Throughout this Customer Engagement Analysis in Excel project, analysis of a dataset from the 365 company will be conducted. It is essential to acknowledge that personal user information has been obscured to ensure confidentiality, and the dataset's size has been reduced for practicality. Nonetheless, this dataset can be regarded as an accurate representation of the company's operations, offering a realistic and pertinent context for the analysis.

1. Descriptive Statistics.xlsx : The file conducts a descriptive statistical analysis on a dataset, exploring the engagement patterns of paid and free-plan students over time. It examines metrics such as mean, median, standard deviation, skewness, and kurtosis to gain insights into the distribution and trends in student engagement levels.
2. Confidence Intervals.xlsx : The file serves to conduct an analysis of confidence intervals to compare the engagement levels of paid and free-plan students over two quarters. It aims to determine whether there are significant differences in the average minutes watched between the two groups and to understand how engagement changes over time for each group.
3. Hypothesis Testing 1.xlsx : The file serves to conduct hypothesis testing to compare engagement levels between paid and free-plan students. It aims to determine whether there is a significant difference in engagement between the two groups across two quarters. Additionally, it examines the implications of Type I and Type II errors in the context of hypothesis testing.
The file is intended for conducting hypothesis testing to compare engagement levels between US and Indian students. It aims to determine whether there is a significant difference in the amount of content watched by these two student groups. Additionally, the analysis explores potential implications of the findings, such as market differences, growth opportunities, and resource allocation considerations based on the observed disparities in engagement levels.

All the data required for conductive analysis outlined above is available in the "Engagement Project.xlsx" file. This file contains the necessary information, including engagement metrics and student demographics.Additionally, pertinent details about the column values should be taken into consideration while interacting with the data:

- student_id: Acts as a distinctive identifier for each student within the dataset. This field encompasses IDs for students who utilized the 365 Data Science platform with either free or paid accounts during Q4 2021 (October 1, 2021 – December 31, 2021, inclusive) and Q4 2022 (October 1, 2022 – December 31, 2022, inclusive).
- student_country: Identifies the country of origin for each student, offering insights into their geographical location and facilitating analyses regarding regional disparities or country-specific patterns.
- Paid: Indicates whether a student possessed a paid account during the specified period. It's represented as a binary variable, where '1' signifies a paid account and '0' indicates a free or unpaid account. This helps distinguish between students with access to enhanced features or content through a paid subscription.
- minutes_watched_21: Reflects the level of student engagement, quantified by the number of minutes watched by a student during Q4 2021.
- minutes_watched_22: Represents the level of student engagement, measured by the number of minutes watched by a student during Q4 2022.

## Project Requirements
To conduct the Customer Engagement Analysis using Excel, ensure you have Microsoft Excel 2007 or a later version installed. Additionally, you'll require the Data Analysis ToolPak for the analysis. Follow the steps below to verify if the Data Analysis ToolPak is already installed:

1. Open Microsoft Excel.
2. Navigate to the Data tab located in the top menu.
3. Look for the Data Analysis button within the Analysis group. If visible, it indicates that the ToolPak is installed, enabling you to proceed with the analysis.

For installing the Data Analysis ToolPak on Windows:

1. Click on the File tab positioned in the top left corner of Excel.
2. Choose Options located at the bottom of the left-hand navigation pane.
3. Within the Excel Options window, select Add-Ins on the left.
4. From the Manage drop-down menu at the window's bottom, opt for Excel Add-ins, and click the Go button.

In the Add-Ins window, check the box adjacent to Analysis ToolPak, then click OK to initiate the installation process.

## Methods Used
- Descriptive Statistics
- Inferntial Statistics
- Data Visualization
- etc

## Tools Used
- MS Excel

## Results Overview
1. **Descriptive Statistics**:
 - **Task 1**:  The analysis indicates that, on average, low-engagement-paid students showed a more significant increase in their watching time compared to free-plan students from Q4 2021 to Q4 2022. This suggests that paid-plan students may perceive more value in the platform, potentially due to access to premium features or content. Conversely, the median watch time decreased for free-plan students, implying that typical students in this group did not enhance their engagement. These findings suggest that engagement strategies may be more effective for paid-plan students, possibly driven by their monetary investment. However, increased variability among paid-plan students suggests diverse responses to platform offerings, highlighting the need for personalized approaches to boost engagement. Further analysis is warranted to understand the factors influencing engagement among paid and free-plan students.
 
 - **Task 2**: The rising skewness and kurtosis observed in both groups from Q4 2021 to Q4 2022 indicate a growing proportion of students watching substantially more content compared to the majority. Particularly noteworthy is the trend among free-plan students, exhibiting higher skewness and kurtosis in Q4 2022 than their paid-plan counterparts. This suggests a pronounced increase in engagement among free-plan students during this period, emphasizing a notable shift in viewing patterns.

2. **Confidence Intervals**: The comparison between paid and free-plan students in Q4 2022 reveals a substantial difference in engagement levels. Paid-plan students watched significantly more minutes, with a confidence interval of 351.99 to 384.72 minutes, compared to free-plan students, with a confidence interval of 61.71 to 70.59 minutes. This aligns with the expectation that paid-plan subscribers are more engaged due to their investment in the platform. However, higher engagement among paid-plan students may not solely stem from the subscription; additional features or content availability could contribute. Conversely, factors such as platform changes or competition may explain the decrease in engagement observed among free-plan students.

3. **Hypothesis Teasting** : <br>
- **Task 4**: The t-statistic value of -3.05 is below the critical value of -1.645, leading to the rejection of the null hypothesis. This indicates that the mean minutes watched by students in Q4 2021 is significantly smaller than the mean minutes watched in Q4 2022. However, it's important to note that rejecting the null hypothesis does not confirm the alternative hypothesis; it simply suggests that the data provide enough evidence against the null hypothesis.
The t-statistic of 29.78 for free-plan students surpasses the critical value of -1.645, resulting in the failure to reject the null hypothesis. This indicates insufficient evidence to conclude that the mean engagement of free-plan students in Q4 2022 is smaller than that of paid-plan students. These findings align with previous results from confidence intervals, emphasizing the distinction in engagement patterns between the two groups. In terms of error types, a Type I error could lead to incorrect assertions of increased engagement, while a Type II error might overlook actual increases, affecting decision-making and resource allocation within the company. The significance level, determined by the researcher, influences the probability of these errors, underscoring the importance of careful consideration in hypothesis testing.

- **Task 5**: The conclusions indicate a failure to reject the null hypothesis, as both the calculated t-statistic surpasses the critical value and the p-value exceeds the specified significance level. If the hypothesis that US students watch more or an equal amount of content as Indian students is rejected, it implies that, on average, US students consume less content than their Indian counterparts. <br>
**_Market Differences_**: The disparity in engagement between Indian and US students may imply that the platform is more appealing or relevant to the Indian audience, highlighting the need for further exploration into the specific features or content that drive this discrepancy. However, such inquiries extend beyond the current analysis's scope. <br>
**_Growth Oppurtunities_**: The lower engagement among US students presents a potential growth opportunity for the 365 company. Strategies to enhance engagement may involve targeted marketing initiatives, augmenting content tailored to US students' preferences, or implementing other strategic approaches.<br>
**_Resource Allocation_**: For instance, if Indian students exhibit higher engagement, it may justify directing resources towards developing content and features specifically tailored to this demographic.












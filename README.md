# **MY ELECTRICITY BILL: NIGERIA'S POWER PROBLEM IN CHARTS AND RECEIPTS**

![Screenshot (583)](https://github.com/user-attachments/assets/dccdd80c-5959-4feb-83db-76a4c7980f08)

## **INTRODUCTION**

In 2024, a ₦5000 electricity purchase gave me close to 70 units of electricity. In 2025, that same ₦5000 barely gives me 22. That’s not just a 68% drop, it’s a silent disaster. While everyone talks about inflation and fuel prices, electricity quietly became a luxury. This project isn’t just about numbers, it’s about frustration, it’s about tracking every unit, comparing old receipts, and realizing it’s not just me but the system.

I tracked every electricity purchase from January 2024 to 2025, visualized the trends, and added real stories from everyday Nigerians. I wanted to understand how Nigeria’s electricity pricing had increased so badly and how ordinary people like me were being affected.

## **INDUSTRY TYPE OF DATA**

This project falls under the Energy Sector and Socioeconomic Impact, focusing on how fluctuating electricity tariffs affect household budgets and daily life.

## **TARGET AUDIENCE OF THIS PROJECT**

Nigerian Residents
 - Policy Makers and Regulatory Bodies
 - Civil Society and Advocacy Groups
 - Economists and Energy Analysts
 - Data Storytellers

## **DATA LIMITATION**

While this project began with personal electricity data, it was later supported by survey responses from users across different DISCOs in Nigeria, many of whom reported similar billing issues. However, the survey sample was limited in size and may not fully capture the diversity of electricity usage patterns or billing experiences across all regions and customer categories in Nigeria. A larger, more representative dataset would further strengthen the findings.

## **DATA CLEANING STEPS TAKEN**

I used Excel to clean and prepare the dataset for analysis. Here's what I did:

1. Performed Data Entry: Collected all the data I needed for this anaysis from my electricity receipts or records, and entered the data into the Excel sheet for further cleaning.
2. Rounded Numeric Values: I used the ROUND function to limit decimals to two places in unit-related columns.
3. Removed Redundant Columns: I deleted the “Duration in Days” column to avoid duplication and focused on the more detailed “Duration in Hours”.
4. Grouped Data: Using IF formulas, I created custom categories for both Amount Paid and Duration to spot patterns more easily.
Foe example: =IF(C2<1000,"Very Low", IF(C2<3000, "Low", IF C2<7000, "Medium", IF(C2<15000, "High", "Bulk"))))
5. Standardizing Data Formats: The Amount column was formatted in the correct currency, Naira(₦), to maintain consistency across the dataset.

## **METHODOLOGIES**

To analyze and visualize the rising electricity cost, I used the following techniques:
1. Pivot Tables to summarize data by month, cost per unit, and usage duration.
2. Line and Column Charts to show trends in cost per unit over time and show when the crash started.
3. Pie Charts to show the yearly spending comparison between 2024 and 2025.
4. Combo Charts showing the correlation between the amount spent and the units obtained.
5. Survey Tags to display short quotes from users to capture real-world frustration.

## **PROBLEMS BEING ADDRESSED**

Here are some of the core questions this analysis tried to answer:

1. When exactly did the crash in unit value begin?
2. How has the cost per unit changed month by month?
3. How long does a typical electricity purchase last in Nigerian homes?
4. Are people buying less electricity now, or are the units simply getting fewer?
5. What are people saying about this crisis, and how are they adapting?

## **ELECTRICITY SPENDING KEY METRICS**

 - From January 2024 to April 2025, I spent a total of ₦490,995 on electricity.
 - Over the same period, I consumed a total of 6,094 units (kWh).
 - On average, I paid ₦96.83 per unit.
 - Each purchase lasted an average duration of 118 hours.
 - The crash in unit value started in April 2025.
 - Between January 2024 and April 2025, my average cost per unit rose from ₦96.83/unit to over ₦227/unit.
 - ₦5000, which gave around 69.99 units in early 2024, now gives just 22 units in 2025, a 68% drop.
 - All survey respondents said they now pay higher amounts on electricity for smaller units.
 - From January 2024 to March 2025, the units corresponded with the amount paid, but in April 2025, the units dropped drastically.

## **RECOMMENDATION**

From what I’ve seen in the data and, honestly, what I’ve lived through myself, things need to change.

1. First, billing needs to make sense. You can’t be paying ₦50k for light and not know how many units you’re supposed to get or why it finishes so fast. People just want to understand what they’re paying for.
2. Next, the power supply has to improve. If we’re now paying over ₦220 per unit, the least we deserve is steady light. Even something like 20 hours a day would change people’s lives. Right now, we’re just paying more for the same or even worse service.
3. Also, the tariff increase is too much, too fast. There needs to be a serious conversation about reducing these prices or at least slowing them down. Because the way things are going, light will soon be a luxury only the rich can afford.
4. People talk about solar and inverters, and yes, they help. But let’s be real: most Nigerians can’t afford that kind of setup. There should be options that help average people switch, not just those who already have money.
5. Finally, the whole system needs to care more about people, not just profit. If we keep ignoring how hard this is hitting everyday Nigerians, we’re going to push even more people into darkness.

## **CONCLUSION**

This whole project wasn’t just about tracking units and money. It was about trying to make sense of why light, something so basic, feels like a battle every month.
The data says it clearly: I’m spending more, but getting less, and I’m not alone. From what others shared with me, this is a nationwide issue. No matter the DISCO, the story is the same.

Until something changes, whether it’s the pricing, the supply, or the policies, Nigerians will keep struggling with a system that’s broken. We deserve better.

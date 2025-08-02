 
<img width="214" height="214" alt="Image" src="https://github.com/user-attachments/assets/9d66a372-7d40-40d0-bb92-006a3f6d4c86" />


# NIGERIA’S ECONOMY IN FOCUS

Sector Performance, Inflation Impact & Investment Outlook

<img width="1981" height="1125" alt="Image" src="https://github.com/user-attachments/assets/6260dc89-98f4-4c1b-b5e5-72fb48985436" />


<img width="1981" height="1125" alt="Image" src="https://github.com/user-attachments/assets/d9fac44d-7dce-4b5e-91d7-cf44dba7200c" />


<img width="1981" height="1125" alt="Image" src="https://github.com/user-attachments/assets/7870393b-5b1b-4ce6-98f2-e6ecdded7e3f" />


# EXECUTIVE SUMMARY

•	The Services sector dominates Nigeria’s economy, contributing 53.98% of GDP in 2024 and recording the highest sectoral growth rate at 0.31%. This post-2020 surge, likely accelerated by digital transformation and pandemic-induced shifts, also positions Finance and Insurance as the fastest-growing subsector, with a 0.30% growth rate, signaling strong investor confidence and digital infrastructure resilience.

•	Agriculture remains the largest GDP-contributing subsector (₦19.5 trillion in 2024, 25.05% of total GDP) and demonstrates a steady upward trend in absolute GDP since 2016. However, its growth rate has consistently declined, with an overall rate of just 0.125%, suggesting that although output is high, productivity and innovation may be stagnating.

•	Manufacturing has experienced persistent decline, with weak GDP contributions and no clear recovery trend over the past decade. In contrast, the Services sector, once volatile (2015–2020), rebounded strongly from 2020–2024, likely benefiting from post-COVID recovery policies and digital service expansion.

•	Nigeria faces a severe inflation-growth disconnect. While food inflation leads at 0.31%, even surpassing imported food inflation (0.29%), communication remains the most stable component, with consistently low inflation growth. An alarming price-to-growth ratio of 2.0 suggests inflation is outpacing GDP growth, creating long-term risks for economic stability and consumer purchasing power.

•	Corporate profitability mirrors sector dynamics. Dangote Cement achieved the highest PAT (₦3.07 trillion over 10 years), while agriculture-linked companies collectively earned ₦180 trillion, the highest by any subsector. The year 2022 recorded peak corporate profits (₦1.14 trillion), aligning with post-COVID demand rebounds. Most companies showed positive correlation between PAT and sector GDP, indicating inflationary impacts and sector health directly influence profitability.

# INTRODUCTION

**Analysis & Approach**

The analysis began with downloading the provided datasets from Google Sheets, followed by an initial data cleaning phase in Microsoft Excel. This stage involved removing irrelevant columns, assigning descriptive headers, resolving missing values, and introducing unique identifiers to ensure traceability and consistency across the datasets. Due to the manageable size of the datasets, there was no need for normalization or concerns about model overloading.

To gain a thorough understanding of the datasets and their interrelationships, I conducted a detailed review of each table. This process was enhanced through domain-specific research supported by ChatGPT, which helped clarify the economic context and the implications of various indicators across sectors.
Following the preliminary cleaning, the structured data was imported into Microsoft SQL Server, which served as the central data warehouse. 

Although no SQL queries were executed, this environment provided a well-organized storage system and facilitated seamless integration with subsequent analytical tools.
The next phase involved connecting SQL Server to Power BI, where more advanced data transformation and modeling were conducted using Power Query. Key processes included:

•	Unpivoting columns for time-series analysis

•	Mapping companies to their respective GDP sectors

•	Creating relationships between tables

•	Modeling time-based metrics.

All necessary calculations, including Year-on-Year (YoY) GDP growth rates, inflation trends, and Profit After Tax (PAT) growth were performed using DAX (Data Analysis Expressions) within Power BI.

To enhance visual storytelling, Figma was used to design dashboard templates and simulate visual layouts. In Power BI, tooltips were strategically applied to provide contextual explanations and improve user interaction, an interactive, insight-driven dashboard was developed to narrate the economic story of Nigeria across GDP sectors, inflation components, and corporate performance.

Finally, the Visual report was exported to Microsoft Power Point where the reports were extracted as pure Images. This end-to-end workflow from Excel-based preparation to SQL Server storage and Power BI transformation ensured high data quality, analytical depth, and an engaging visual experience for stakeholders.





# MAIN SECTION
**2.1.1. Analytical Sections Overview**

This report is divided into three key analytical areas, each focused on uncovering critical insights from different facets of Nigeria’s economy: GDP performance, inflationary trends, and corporate profitability across sectors. Each section is backed by data-driven visuals and interactive dashboards, designed to help stakeholders explore trends, patterns, and relationships that inform strategic decision-making. 

A link to the full visual report is provided below for further exploration.

📎 Access the full interactive report here: [ https://tinyurl.com/sbf8yhu8  ]

**2.1. GDP Analysis**

<img width="624" height="354" alt="Image" src="https://github.com/user-attachments/assets/9377870f-94ec-431e-a74b-89fdda13ac85" />


This section examines sector-by-sector GDP contributions and growth trends from 2015 to 2024. It identifies top-performing sectors, fastest-growing subsectors, and highlights structural changes in the economy over time.
 



**2.1.1. Year-on-year GDP growth rate (YoY%) for each sector and subsector for the last 10 years.**

  <img width="306" height="214" alt="Image" src="https://github.com/user-attachments/assets/75b0770b-faca-44e2-b837-e1f8888fd7cd" />

<img width="306" height="213" alt="Image" src="https://github.com/user-attachments/assets/aba1caed-055e-4abb-8e08-76d7ee18cc95" />


Over the last decade, the services sector has recorded the highest average year-on-year (YoY) GDP growth rate, with a value of 0.13%, followed closely by agriculture at 0.12%, and manufacturing at 0.11%.

From 2016 to 2020, agriculture consistently led in annual growth, followed by manufacturing, while the services sector lagged behind. However, in 2020, services surpassed manufacturing in growth rate, and by 2021, fully overtook agriculture, becoming the leading sector and maintaining upward momentum since then.

By 2023, a noticeable decline began in agriculture’s growth, continuing into 2024, which resulted in manufacturing overtaking it as the second-best performing sector. Despite this recent dip, agriculture has performed strongly overall during the 10-year period, though it was ultimately outpaced by the rapid and sustained growth in services.

Among subsectors, oil and gas recorded the lowest average growth at 0.09%, while financial and insurance services led with a robust 0.22%. Despite agriculture’s large share of GDP — contributing over 25%, its growth rate has steadily declined from 0.04% in 2015 to 0.01% in 2024.

The financial and insurance subsector rose significantly from negative growth in 2016 to 0.01% by 2020, then accelerating to 0.04% by 2024. Similarly, water supply and waste management ranks as the second-best performing subsector in terms of average growth. However, its performance remained volatile, as its 2024 growth rate of 0.01% merely matched that of 2016.

The oil and gas sector, consistently trailing behind, fluctuated mostly in the negative growth region throughout the decade. Although it finally returned to positive growth in 2024, the recovery remained modest and insufficient to make a significant impact.

The accommodation and food services subsector showed irregular trends, recording an average growth of 0.11%. It experienced a steady increase from 2018 to 2019, suffered a sharp drop in 2020 (likely due to the COVID-19 pandemic), then rebounded to 0.05%, where it stabilized until 2024.


**2.1.2. Top 5 Subsectors by growth rate in 2024.**

<img width="308" height="210" alt="Image" src="https://github.com/user-attachments/assets/300c4830-c20e-4b99-9115-0bc3d2e66080" />

It’s no surprise to see the Financial and Insurance subsector leading with the highest growth rate in 2024, posting a remarkable 0.30%, a wide margin above others. This continued growth reflects the sustained expansion of fintech, digital banking, and broader financial services innovation.
Following behind are:

•	Water Supply, Waste Management & Remediation – 0.08%

•	Transportation and Storage – 0.07%

•	Information and Communication – 0.05%

•	Oil and Gas – 0.05%

These results reinforce the growing dominance of the services sector, with four out of the top five subsectors falling within it.
It’s particularly noteworthy that Oil and Gas, despite being the worst-performing subsector over the last decade, has made a positive recovery in 2024, returning to the top five in terms of annual growth. 

This suggests a potential rebound, possibly driven by improved production stability or favorable market conditions.
Overall, the 2024 data reflects a continued shift towards service-driven growth, with traditional sectors like oil and gas showing signs of gradual recovery but still trailing behind in long-term performance.


**2.1.3. Top 5 sectors by contribution to GDP in 2024.**

 <img width="308" height="209" alt="Image" src="https://github.com/user-attachments/assets/077e01a5-a9b5-462a-af7f-775c783a5947" />


In 2024, Agriculture remained the highest contributor to Nigeria’s GDP, with a total value of ₦19.5 trillion. This reinforces the sector’s foundational role in the economy, despite recent declines in growth rate.

It was followed by the:

•	Information and Communication sector – ₦14.0 trillion

•	Trade sector – ₦12.3 trillion

•	Manufacturing sector – ₦6.8 trillion

•	Financial and Insurance sector – ₦4.9 trillion

The gap between the top three contributors and the remaining sectors is significant, indicating a concentration of economic activity within agriculture, ICT, and trade.

While manufacturing and finance are performing well in terms of growth, their overall GDP contribution is still considerably lower compared to the leading subsectors, reflecting either smaller base values or slower historical expansion.
This ranking highlights the need to balance sectoral growth with structural transformation, especially in industries with high potential but relatively lower current output.


**2.1.4.1. Which sector performed best and least over the 10 years by growth**

<img width="304" height="160" alt="Image" src="https://github.com/user-attachments/assets/92b55f51-5d65-4234-aa53-5d514ae54b6c" />

<img width="306" height="158" alt="Image" src="https://github.com/user-attachments/assets/65293434-9d09-4c85-beb6-76260277919c" />

Over the past decade, the Services sector emerged as the best-performing sector in terms of average year-on-year GDP growth, recording a rate of 0.13%. This sustained growth reflects Nigeria’s gradual transition towards a service-based economy, largely driven by sectors such as financial services, ICT, and transportation.

In contrast, the Manufacturing sector recorded the lowest average sectoral growth at 0.107%, indicating slower expansion over the 10-year period despite its importance to industrialization and job creation.

At the subsector level, the Financial and Insurance subsector was the top performer, with an impressive growth rate of 0.22%, largely due to rapid digital transformation and financial inclusion. While the Oil and Gas subsector was the least performing, reflecting challenges such as price volatility, underinvestment, and frequent production disruptions.

It remained mostly in the negative growth region throughout the period.
This trend highlights a shift in Nigeria’s economic structure from heavy reliance on oil to emerging growth in technology-driven and service-based industries.


**2.1.4.2. Which sector performed best and least over the 10 years by contribution?**

<img width="306" height="158" alt="Image" src="https://github.com/user-attachments/assets/408e4ee7-124e-432d-8b2a-27f7a6545b77" />

<img width="308" height="214" alt="Image" src="https://github.com/user-attachments/assets/83007b1c-be4f-4e52-b5a4-120fe886a8f4" />

The Agriculture sector has maintained a strong presence, contributing over 25% of Nigeria’s total GDP, despite consisting of only a single subsector (agriculture). Its dominance highlights the sector's central role in the economy, especially in employment and food production.
However, in aggregate terms, the Services sector outperformed all others, contributing nearly double the amount of agriculture to the national GDP. This includes multiple high-performing subsectors such as financial services, ICT, and transportation, reflecting the country’s gradual shift toward a more service-oriented economy.

On the other hand, the Manufacturing sector recorded the lowest total contribution, accounting for just 20.97% of GDP over the 10-year period. Despite its role in industrialization, its relative share remained modest compared to other sectors.

At the subsector level, agriculture remained the highest contributor, with a cumulative GDP value of approximately ₦180 trillion between 2015 and 2024, while the Administration subsector was the least contributor, with a total GDP value of just ₦147.28 billion, indicating its relatively limited economic output despite its administrative importance.

These insights underline the need to diversify growth across sectors, particularly in manufacturing and administrative services, while also sustaining productivity in the agriculture sector.


**2.1.5. If you were a member of the Economic Advisory Team, what recommendations would you make to improve underperforming sectors?**

I.	**Modernize the Oil & Gas Sector:** Over the past decade, the Oil & Gas sector recorded the lowest average GDP growth rate of 0.09%, with prolonged years of negative growth before a modest rebound to 0.05% in 2024. Despite being a vital contributor to Nigeria's foreign exchange earnings, its declining performance signals inefficiencies in value addition and upstream investments. 

To reverse this trend, there should be a focus on incentivizing domestic refining and production, enhancing transparency in operations, and shifting toward gas and clean energy to diversify the sector’s contribution.

II.	**Reignite Manufacturing Growth:** The Manufacturing sector posted the lowest 10-year sectoral growth rate of 0.107%, yet contributed ₦6.8 trillion to GDP in 2024. This stagnant growth suggests deep structural issues including unreliable power, high production costs, and poor access to credit. Revitalization efforts should target industrial clusters with uninterrupted electricity, investment in transport logistics, and low-interest financing for small and medium manufacturers.

III. **Revamp Public Administration Services:** The Public Administration subsector was the lowest contributor to GDP in 2024, with only ₦147.28 billion, highlighting its limited productivity and economic value. Given its central role in governance and service delivery, improving this subsector could have a ripple effect across the economy. Prioritizing digital transformation, automating bureaucratic processes, and instituting a performance-based public service culture could increase its efficiency and potentially grow its GDP contribution by over 50%.

IV.	**Sustain Agricultural Dominance through Innovation:** Agriculture remained the largest single subsector in 2024, contributing ₦19.5 trillion, but experienced a decline in growth rate from 0.04 in 2015 to 0.01 in 2024. This reflects stagnation despite its scale. To maintain dominance and improve resilience, the sector needs targeted investments in mechanization, smart irrigation, and market access for smallholder farmers. A modest increase in growth back to 0.03 could inject an estimated ₦1 trillion into the economy each year.

V.	**Boost Underutilized High-Potential Services:** The Financial & Insurance subsector recorded the highest average growth rate (0.22%) and led all subsectors in 2024 growth at 0.30%, yet its contribution to GDP was only ₦4.9 trillion significantly below sectors like Agriculture and Trade. This mismatch highlights untapped potential. Expanding digital financial services, improving financial literacy, and incentivizing fintech expansion in rural areas could significantly increase its economic footprint, potentially pushing its GDP contribution beyond ₦6 trillion within a few years.

**2.2. CPI & Inflation Analysis**

<img width="624" height="354" alt="Image" src="https://github.com/user-attachments/assets/be6e7be3-7c59-4441-8d40-279cbbe23c5e" />

Here, we assess the Consumer Price Index (CPI) across different components to determine inflation hotspots, long-term price pressures, and their implications on economic growth. Sectoral inflation is compared against GDP performance to identify resilience and vulnerabilities.
 
**2.2.1. Year-on-year inflation rate (%) for each CPI component.**

 <img width="308" height="216" alt="Image" src="https://github.com/user-attachments/assets/fe4da05b-cdc0-49e7-acec-dea4cd8b45da" />

**Agricultural Sector:**
The Food component recorded an overall inflation growth rate of 0.31%, surpassing Imported Food, which stood at 0.29%. Between 2016 and 2020, both the Food and Food & Non-Alcoholic Beverages components maintained inflation rates below 0.2%. However, from 2021 onwards, they experienced a sharp rise, peaking at 0.4%, making Food the component with the highest inflation rate over the past decade. Similarly, Imported Food remained under 0.2% until 2022, after which it saw a sudden spike above 0.4%.

**Manufacturing Sector:**
This sector has been least impacted by inflation, with a slow and steady rise over the years. Components such as Alcoholic Beverages, Clothing, and Furnishing had inflation growth rates of 0.23%, 0.22%, and 0.22%, respectively. Notably, these components maintained relative stability between 2018 and 2019, before gradually rising in subsequent years.

**Services Sector:**
The Services sector recorded the highest average inflation growth, with most of its components showing sharp increases beginning in 2019. However, some exceptions deviated from this trend:
I.	Communication experienced a significant decline in inflation growth, dropping from earlier highs to settle below 0.05% by 2023, with an overall inflation rate of 0.15%.
II.	Recreation and Culture had an overall rate of 0.18%, with a sharp decline in 2022 followed by a gradual uptick in 2023, yet still remained under 0.1%.

**2.2.2. Identify which sectors/components have experienced the highest costs of goods/services in the last 10 years**


 <img width="621" height="214" alt="Image" src="https://github.com/user-attachments/assets/61907e77-1c2b-42de-a8c8-15a371d25f42" />

 

With a Price Pressure Index (PPI) of 2.46, the agriculture sector has experienced the highest cost of goods and services over the past 10 years. It is followed by the manufacturing and services sectors, which recorded PPIs of 2.08 and 1.67, respectively.
At the component level, Food, Food & Non-Alcoholic Beverages, and Imported Food top the list, highlighting a significant surge in costs across these categories over the last decade.




**2.2.3. What insights can you draw by comparing the CPI data with GDP growth & contributions?**

  <img width="306" height="214" alt="Image" src="https://github.com/user-attachments/assets/cac09c7c-8c1a-4a63-8c81-4ded4d83ec4e" />

<img width="306" height="216" alt="Image" src="https://github.com/user-attachments/assets/08b022cf-0ac0-4bc7-9f2b-128686e5d476" />


I.	**Persistent Inflation vs. Modest GDP Growth:** Inflation Rate rose from 16.5% in 2016 to 29.7% in 2024, showing a sharp and consistent increase over time, in contrast, GDP Growth remained modest, peaking at just 3.4% in 2021 and 2024. This indicates stagflation risks, where the economy faces high inflation but slow growth, which can erode purchasing power without boosting productivity.

II.	**Inflation Outpacing Economic Growth:** For every year between 2016–2024, the inflation rate was significantly higher than GDP growth. For instance, in 2024, Inflation Rate was 29.72% while GDP Growth was 3.4%. This suggests that real incomes and economic well-being may be declining, as price increases are not matched by economic expansion.

III.	 **Post-COVID Recovery Divergence:** In 2020 (COVID year), Nigeria’s GDP shrank to -1.92% and Inflation rose by 13.33% however in 2021, while GDP rebounded (3.4% in 2021), inflation continued climbing, signaling supply-side shocks and rising costs rather than demand-driven inflation.

IV.	**Recommendation:** The steady rise in CPI points to increased costs for basic goods/services, this places pressure on household consumption, potentially slowing down domestic demand and impacting sectors reliant on consumer spending. I recommend that Monetary and fiscal policies must target inflation control without stifling growth, there's a need to boost productivity and investment in sectors like manufacturing and agriculture to counter cost-push inflation and enhance GDP performance.



**2.2.4. Are rising prices hurting or helping certain sectors?**
AGRICULTURE

<img width="306" height="214" alt="Image" src="https://github.com/user-attachments/assets/5968bad0-728f-456b-93f7-b1ca27d6dfe9" />

<img width="304" height="214" alt="Image" src="https://github.com/user-attachments/assets/79ef2e2f-7297-4d91-84a5-640a480da10c" />
  
Rising prices is hurting the agriculture sector. From 2016 to 2024, inflation surged from 19.2% to 40.5%, while GDP growth fell from 4.1% to just 1.2%. This inversely proportional relationship shows that price increases are not driven by productive growth, but by cost pressures eroding real value.

Agriculture  Sector is particularly vulnerable and despite being a key driver of CPI, agriculture isn’t benefiting, it’s likely underperforming in real terms due to lagging supply and shrinking profit margins.
Other sectors are also affected, but manufacturing and services may be slightly more resilient due to slower inflation growth and more stable output. Still, across the board, rising prices appear to be hurting rather than helping economic performance.

**2.2.5. Are some subsectors resilient despite inflation?**

**Financial and insurance**


<img width="309" height="214" alt="Image" src="https://github.com/user-attachments/assets/cbaae634-4740-4324-a20c-d53f69fa7364" />

<img width="306" height="214" alt="Image" src="https://github.com/user-attachments/assets/224c9e72-f955-48ce-b086-1d47315397d1" />
  


Yes, the financial and insurance subsector has proven highly resilient from 2016 to 2024.
After a sharp contraction of -4.5% in 2016, the sector rebounded strongly, reaching 29.6% GDP growth in 2024, the highest recorded over the period. Between 2020 and 2024, its growth consistently outpaced inflation (e.g., 2024: 29.6% growth vs. 21.6% inflation), showing real economic expansion.

Despite rising inflation pressures, especially from 2021 onward, the sector sustained upward momentum. This resilience reflects strong market adaptability, driven by factors such as digital innovation, financial inclusion, and increased public trust in banking, insurance, and fintech services.

In summary, the data confirms that the financial and insurance subsector is one of the most adaptive and consistently expanding sectors in Nigeria’s economy.

**2.3. Company–Sector Relationship**

<img width="624" height="354" alt="Image" src="https://github.com/user-attachments/assets/94289013-2415-4991-bf8e-06609be5b0b4" />

This section explores the financial performance of seven key companies, analyzing their Profit After Tax (PAT) trends and mapping them to their respective GDP sectors. It also evaluates the alignment between company growth and sectoral GDP, offering insights into investment potential and inflation resilience.
 
**2.3.1. Determine the annual growth rate of PAT for each of the 7 organizations.**

 <img width="306" height="210" alt="Image" src="https://github.com/user-attachments/assets/61c7b1cf-2fd4-442a-8dda-bdb393b24252" />


I.	**Seplat Energy (1.09 %):** The company’s PAT more than doubled, indicating explosive growth, likely driven by favorable conditions in the upstream oil & gas sector such as rising crude prices, reduced subsidies, or cost efficiency, also looking from an industrial context,  Global energy market recovery post-COVID may have boosted revenue and margins

II.	**Okomu Oil & Zenith Bank:** Okomu (0.48 %) reflects agri-export strength, possibly benefiting from global palm oil demand and local market expansion, Zenith (0.45 %) shows that banking remains resilient, possibly due to smart investment management, increasing digitalization, or FX gains.

III.	**Conoil & Dangote Cement:** Conoil (0.30 %) suggests steady performance in downstream oil, likely boosted by deregulation and petrol price flexibility and Dangote Cement (0.19 %) is growing slowly, hinting at sectoral maturity or pressures like high energy costs, interest rates, or stagnant infrastructure projects.

IV.	 **MTN Nigeria (-0.34 %):** A sharp drop, indicating pressure on telecom profitability, Possible reasons: stiff competition, regulatory fines, infrastructure investment burden, or declining ARPU (average revenue per user).

V.	**Critical Losses:** Nestlé Nigeria (-0.034 %) A massive reversal in performance from profit to deep losses. This scale of decline suggests structural financial distress, such as: Severe inflation impact on imported inputs, FX losses from currency devaluation, weakening consumer purchasing power, and High operating costs.


**2.3.2. Explore the relationship between each company’s PAT and the GDP of its sector:**

<img width="306" height="210" alt="Image" src="https://github.com/user-attachments/assets/c946379e-f837-4743-a188-540901816e00" />

<img width="306" height="209" alt="Image" src="https://github.com/user-attachments/assets/7b2c090d-574e-4055-add9-d1a2dd006755" />

Zenith Bank has the strongest contribution relative to its sector, with PAT making up 11.07% of the Financial & Insurance sector’s GDP indicating a dominant role, followed by Dangote Cement is also a major player, contributing 4.72% to Manufacturing GDP.

MTN and Seplat Energy show moderate influence within their sectors, while Okomu Oil and Conoil have marginal shares. Nestle Nigeria posted a net loss, reducing the overall contribution of its sector. The low PAT-to-GDP ratios in some sectors (e.g., Agriculture, Oil & Gas) may suggest a high number of smaller or unlisted firms in the sector, operational inefficiencies and weak profitability margins in relation to the sector’s total output.

  

**2.3.2.1. Do their trends align? Why or why not?**


Zenith Bank, Dangote cement, MTN Nigeria, Conoil and Nestle Nigeria all have perfect alignment .
Zenith is a leading profit-maker in its sector, and it's also growing fast. This shows strong financial health and strategic market leadership, As the dominant manufacturing firm, Dangote cement contributes significantly to GDP. Although its PAT growth is modest, the consistency supports its mature and stable market position.

MTN Nigeria, despite being a major telecom, its contribution to sector GDP is relatively low and its PAT is shrinking. Reflects sector saturation, rising costs, and regulatory challenges. With a modest PAT growth and modest sector contribution, Conoil operates in a tight-margin retail fuel market which explains moderate profitability. Finally, Nestle Nigeria, a major manufacturer suffering massive losses and this is a major concern for the consumer goods segment of the manufacturing sector.


Seplat Energy and Okomu Oil states otherwise as they are not aligned. Despite Seplat’s explosive PAT growth, its share of sector GDP is small. This suggests that the he oil & gas GDP is driven more by output volume (e.g., crude oil production) than company profit and also the sector may have many unlisted firms or heavy capital expenditure, keeping PAT low relative to GDP. 

Okomu oil had strong profit growth, but its contribution to GDP is tiny. The Agriculture sector GDP is very large and fragmented — Okomu, while successful, is just one small player. High output in agriculture does not always translate into high profits due to low price margins.


**2.3.2.2. How does overall inflation and sector inflation affect their profitability?**

<img width="306" height="166" alt="Image" src="https://github.com/user-attachments/assets/2ca5c326-3526-4400-962a-c7ada0d2fd48" />

<img width="306" height="166" alt="Image" src="https://github.com/user-attachments/assets/4aa17d67-61b9-43fa-92ec-72e0d974a9b3" />

<img width="306" height="210" alt="Image" src="https://github.com/user-attachments/assets/faa45880-b2e3-4483-a13b-77c48f7a549a" />
   

I.	**Zenith Bank:** With a relatively low inflation rate of 0.21%, Zenith Bank achieved very high profit after tax (PAT) and robust growth. This reflects how banks can benefit from inflation through higher interest rates, widened spreads, and forex income, while their service costs remain comparatively low.

II.	**Dangote Cement & Seplat:** Both operate under 0.22% inflation. Dangote Cement recorded high PAT but modest growth, likely limited by FX losses, energy costs, and price controls. In contrast, Seplat’s lower PAT came with strong growth, supported by dollar-based earnings that helped offset naira depreciation.

III.	**MTN, Nestlé & Okomu:** MTN faced a PAT decline of 0.34% despite 0. 21% inflation, due to high operational and FX costs. Nestlé’s PAT plunged by 0.034% as inflation eroded margins in a cost-sensitive manufacturing sector. Okomu Oil, despite very high inflation (0.29%), posted strong PAT growth  likely due to export gains and favorable global prices.

IV.	**Conoil:** Although inflation was moderate, Conoil posted relatively low PAT (₦37.5 billion) despite a 0.30% growth rate, suggesting tight margins and cost pressures in the fuel distribution sector.

Inflation affects sectors differently, banks and exporters often benefit, while manufacturers are more exposed. Export-oriented firms like Seplat and Okomu can thrive under inflation if cost controls and forex earnings are strong. Sector structure and internal operations (e.g., cost base, regulatory environment) may influence PAT more than inflation alone, as seen with Zenith and MTN.

**2.3.3. As an investor, which industry and company would you invest in? Why?, Considering growth, resilience to inflation, and GDP contribution.**

Zenith Bank (Financial Sector) is the top investment pick, showing exceptional financial health with a total PAT of ₦3.00 trillion, 0.45 PAT growth, and 11.07% contribution to its sector’s GDP, the highest among all companies analyzed. It also operates in a sector with low inflation exposure (21.96%), enhancing its resilience and long-term stability. This ultimately shows that the Financial & Insurance sector stands out as the most stable and profitable industry, contributing ₦27.13 trillion to GDP, and maintaining high returns even in inflationary conditions, as banks benefit from interest rate spreads and forex operations. It offers the best balance of growth, resilience, and economic impact.

# RECOMMENDATIONS

**3.1. Recommendations for Policymakers**

i.	**Manage Inflation Strategically**

o	Inflation hit 24.4% in 2024, worsening cost pressures in key sectors.

o	Deploy targeted subsidies and infrastructure investment in sectors like agriculture and manufacturing.

o	Stabilize monetary policy to improve purchasing power and business margins.

ii.	**Enable Export and FX-Earning Sectors**

o	Firms like Seplat and Okomu Oil thrived due to dollar revenues.

o	Incentivize exporters with FX access, tax reliefs, and reduced trade barriers.

o	Strengthen trade policies to encourage value-added exports.

iii.	**Boost Sector-Specific Reforms**

o	Support financial sector digitalization and SME lending to sustain growth seen in Zenith Bank.

o	Improve ease of doing business in manufacturing and telecoms.

o	Introduce performance-based support for sectors with high GDP but low profitability.

**3.2.  Recommendations for Investors**

i.	**Favor Inflation-Resilient Sectors**

o	Invest in financial institutions like Zenith Bank, which benefit from high interest rate spreads.

o	These firms showed strong PAT performance even under inflationary pressure.

o	Less vulnerable to input price volatility.

ii.	**Target Export-Focused & Dollar-Earning Companies**

o	Firms like Seplat (+1.09% PAT) and Okomu Oil outperform due to FX earnings.

o	Provide inflation hedge and higher profit stability.

o	Ideal for growth-oriented portfolios.

iii.	**Avoid Inflation-Sensitive Consumer Manufacturing**

o	Companies like Nestlé posted heavy losses due to high import costs and shrinking consumer demand.

o	Select firms with lean cost structures and pricing power.

o	Monitor FX exposure and input dependency closely.

**3.3. Suggested Sectors for Further Investment & Focus**

i.	**Financial & Insurance Sector**
o	29.6% GDP growth in 2024, with strong PAT from banks.

o	Digital transformation and fintech expansion fuel long-term returns.

o	Low inflation sensitivity makes it stable.

ii.	**Oil, Gas & Renewable Energy**

o	Companies like Seplat show PAT stability and FX advantage.

o	Investment in gas, refining, and renewables will drive energy independence and profitability.

o	Strategic for national revenue and investor returns.

iii.	**Agro-Export and Agribusiness Value Chains**

o	Agriculture contributed ₦19.5 trillion to GDP, but is under-leveraged.

o	Firms like Okomu Oil highlight export potential and CPI insulation.

o	Invest in agro-processing, logistics, and export-oriented farming.




## Used By

This project is used by the following companies:

- Statisense



## Authors

- [@Joshkingzz](https://github.com/Joshkingzz)



# Identifying factors that contribute to worldwide military spending and conflict

## Background
Global military spending increased by [2.6% in 2020](https://www.dw.com/en/global-military-spending-increases-despite-covid-19-pandemic-report/a-57333582#:~:text=Total%20military%20expenditure%20worldwide%20increased,Institute%20(SIPRI)%20on%20Monday.) to $2 trillion, despite the economic and social hardships brought on by the COVID-19 pandemic. A staggaring finding shows that 5 countries (U.S., China, Russia, India, and the U.K.) account for [62%](https://www.dw.com/en/global-military-spending-increases-despite-covid-19-pandemic-report/a-57333582#:~:text=Total%20military%20expenditure%20worldwide%20increased,Institute%20(SIPRI)%20on%20Monday) of global military expenditure. Specific to the United States, [debates](https://www.charleskochinstitute.org/issue-areas/foreign-policy/the-military-spending-debate/#:~:text=The%20Military%20Spending%20Debate%20on%20Capitol%20Hill&text=At%20about%20%241%20trillion%2C%20military,directly%20choose%20how%20to%20spend.) rage on as to what amount of military spending is appropriate. Indeed, some [military expenses](https://www.defenseone.com/ideas/2020/01/why-does-us-spend-so-much-defense/162657/) would be ongoing, even in a perfect world i.e. aid to other countries, response to natural disasters, and general preparedness against the inevitable wrong-doer. However, many [argue](https://www.brookings.edu/blog/order-from-chaos/2020/07/09/how-to-cut-and-not-cut-the-defense-budget/) that U.S. military spending, which makes up [15% of federal spending and nearly half of discretionary spending](https://www.pgpf.org/chart-archive/0053_defense-comparison), has much fat to be trimmed. At its core, military spending is motivated by defense and offense, which raises the question: What influences countries to spend money for military defense and advancement? While aiming for world peace may be [difficult](https://time.com/3935254/is-world-peace-possible/#:~:text=%E2%80%9CGenuine%20%E2%80%9Cworld%20peace%E2%80%9D%E2%80%93,becoming%20increasingly%20diversified%20and%20contentious.), pursuing it should reduce utilization of resources, cut expenditures, and give the world a greater feeling of safety.

This analysis seeks to identify societal and economic characteristics which correlate with military spending and eventual conflict. Using the datasets and manipulations listed below, mitigations will be proposed to build up the developing nations of the world and to promote cohesion between current and future opposing forces.

## Business Question
__What factors should global peacekeepers target to promote, and eventually attain, world peace?__

## Data Question - Open Data
Data for this analysis comes from the [UCDP Database](https://ucdp.uu.se/downloads/index.html#battlerelated) organized by country, the [World Bank](https://data.worldbank.org/) organized by country and country code, and the [Stockholm International Peace Research Institute (SIPRI)](https://www.sipri.org/). Raw datasets are as follows:

- [Arms Exports](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Arms_exports.csv)
- [Arms Imports](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Arms_imports.csv)
- [Energy Use](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Energy_Use.csv)
- [Fuel Exports](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Fuel_exports_percent_merchandise_exports.csv)
- [Income Shared by Lowest 20%](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Income_share_by_lowest_20.csv)
- [Male Agriculture](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Percent_Male_Agriculture.csv)
- [Electricity Access](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Percent_access_to_electricity.csv)
- [Girls/Boys School Enrollment](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Percent_school_enrollment.csv)
- [Military Expenditure (GDP)](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Military_expenditure_GDP.csv)
- [Military Expenditure (per Capita)](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Military_expenditure_capita.csv)
* The SIPRI dataset was too large to upload to GitHub

Processed datasets are as follows:
- [Conflict Deaths](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/conflict_deaths.csv)
- [Conflicts](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/conflicts.csv)
- [Country Name Processing](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/countries_regions.csv)
- [Fuel data](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/fuel_imports_data.csv)
- [Low income processed](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/lowinc_conflicts_plot_data.csv)
- [Bulk data for analysis](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/various_expenditure_capita.csv)

A detailed breakdown of analysis will be provided in the final project submission. 

Figures resulting from this analysis are found here:
- [Agriculture and Expenditure](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Agriculture.png)
- [Education and Expenditure](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Education.png)
- [Electricity and Expenditure](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Electricity.png)
- [Fuel Exports and Expenditure](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Fuel_Expenses.png)
- [Fuel Exports and Arms Imports](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Fuel_Imports.png)
- [Income and Conflicts](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Income_share.png)

This [Google Colab file](https://github.com/mehurlock94/identifying-factors-contributing-to-armed-conflict/blob/main/Identifying_factors_contributing_to_armed_conflict.ipynb) was used to process datasets

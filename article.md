---
title: 'Global and National Perspectives on Obesity Trends: Insights from Gender-Specific Data'
abstract: |
    Obesity has emerged as a significant public health challenge worldwide, with varying prevalence rates across genders, geographic regions, and over time. This study combines global data with national trends in the United States and the United Kingdom to examine obesity prevalence. Gender-specific obesity rates were analyzed from 1990 to 2016, leveraging visualizations including global maps and comparative line graphs. Findings indicate a steady rise in obesity prevalence across both genders, with women consistently showing higher rates. These insights underscore the need for targeted interventions to address obesity at both global and national levels.

availability: |
    The data that support the findings of this study are openly available in `jterm2025article` at (https://github.com/shaunya-upp/jterm2025article).

exports:
  - format: typst
    template: lapreprint-typst
    output: exports/uppalapati-jterm2025.pdf
  - format: pdf 
    template: arxiv_two_column 
    output: exports/uppalapati-jterm2025.pdf
---

## Introduction 
Obesity, defined as a body mass index (BMI) of 30 kg/m² or higher, poses severe health risks, including cardiovascular disease, diabetes, and certain cancers (@10.1002/osp4.474). While the global obesity epidemic continues to grow, its distribution across genders and regions varies significantly. This research examines gender-specific obesity trends globally and in two high-income nations, the United States and the United Kingdom, from 1990 to 2016. By integrating WHO global prevalence maps and national datasets, the study aims to highlight disparities and provide insights for policymakers.

## Methods 
The analysis used data from simulated datasets reflecting BMI trends among U.S. and U.K. adults between 2000 and 2020. These datasets included information on the prevalence of underweight (BMI < 18.5 kg/m²), obesity (BMI ≥ 30 kg/m²), and morbid obesity (BMI ≥ 40 kg/m²). Data were categorized by gender to identify potential disparities. Trends were analyzed using descriptive statistics and visualizations to highlight changes over time. Simulated datasets were designed to mimic patterns observed in large-scale health surveys such as the National Health and Nutrition Examination Survey (NHANES) in the U.S. and the Health Survey for England (HSE) in the U.K. Results were reported as percentages to allow for comparative analysis across populations. Statistical software was used to calculate changes over time and compare gender-based differences within and between the two countries. This study utilized three primary data sources:
1. WHO Global Data: Prevalence maps for overweight individuals (≥25 kg/m² BMI) by gender in 2016.
2. U.S. Dataset: Annual obesity prevalence rates (BMI ≥30 kg/m²) for males and females from 1990 to 2016.
3. U.K. Dataset: Annual obesity prevalence rates (BMI ≥30 kg/m²) for males and females from 1990 to 2016.
Data were processed using Python and pandas for analysis and visualization. Line graphs were generated to compare trends by gender within the U.S. and U.K., and WHO maps provided a global perspective.

## Results 
**Obesity Prevalence:**
- U.S. Women: Increased from 30.5% in 2000 to 39.0% in 2020.
- U.S. Men: Increased from 28.0% in 2000 to 36.2% in 2020.
- U.K. Women: Increased from 27.5% in 2000 to 35.8% in 2020.
- U.K. Men: Increased from 25.0% in 2000 to 34.1% in 2020.

**Global Perspective:**
The WHO maps for 2016 (@Female-Overweight and @Male-Overweight and @Combined-Graph) indicate higher obesity prevalence among females globally, particularly in the Middle East and Pacific regions, where rates exceed 60%. In contrast, male obesity prevalence is more evenly distributed, with fewer regions surpassing the 60% threshold.

**National Trends:**
- **United States:** Obesity rates for both genders increased steadily from 1990 to 2016 (@Combined-Graph). Women exhibited consistently higher rates, with a rise from 21.2% in 1990 to 38.5% in 2016. Men’s rates also climbed, from 19.7% to 35.2% over the same period.
- **United Kingdom:** A similar upward trend was observed (@Combined-Graph). Female obesity rates increased from 13.8% in 1990 to 27.5% in 2016, while male rates rose from 11.7% to 24.7%.

## Discussion 
The findings reveal a consistent gender disparity in obesity prevalence, with women generally exhibiting higher rates globally and nationally. This disparity may be attributed to various sociocultural, biological, and behavioral factors. Hormonal differences, such as those related to estrogen and progesterone, can influence fat distribution and metabolic processes, potentially predisposing women to higher levels of body fat. Additionally, women often face societal pressures that shape eating behaviors, including emotional eating or consumption of calorie-dense comfort foods.

Lifestyle behaviors further compound these trends. In many societies, women may have less access to structured physical activities due to caregiving responsibilities or cultural restrictions. These factors can reduce opportunities for exercise and increase sedentary behaviors, further elevating obesity risks. Moreover, gender-specific marketing strategies for unhealthy foods, such as sugary snacks targeted at women, may contribute to higher caloric intake.

In the U.S. and U.K., the alignment of rising obesity rates with lifestyle changes emphasizes the role of modern dietary patterns and physical activity levels. The proliferation of processed and fast foods, combined with increasingly sedentary work environments, has created a "caloric imbalance," where energy intake surpasses expenditure. Women, particularly in urban areas, may face higher exposure to these unhealthy food environments, which exacerbates obesity prevalence.

The global maps highlight significant geographic disparities. Regions such as the Middle East and Pacific Islands show alarmingly high obesity rates among women, exceeding 60% (@10.3390/nu14204253). These trends reflect unique cultural and economic factors. For instance, traditional dietary patterns in these regions have shifted towards higher consumption of imported processed foods, which are often cheaper and calorie-dense. Additionally, limited access to recreational spaces and cultural norms restricting women’s mobility may contribute to physical inactivity (@10.3390/nu14204253).

Economic transitions also play a role. In developing nations experiencing rapid urbanization, obesity often coexists with undernutrition in a phenomenon known as the "double burden of malnutrition." (@10.1186/s12966-021-01125-8) Women in these settings may face a greater risk of obesity due to urban lifestyles characterized by reduced physical labor and increased reliance on inexpensive, energy-dense foods. This paradox highlights the complexity of addressing obesity within broader socioeconomic contexts (@10.1186/s12966-021-01125-8).

Finally, the interplay between biological predispositions and environmental influences underscores the need for targeted interventions. Addressing obesity among women requires a multifaceted approach, including public health campaigns promoting balanced diets and physical activity, policies regulating unhealthy food marketing, and community initiatives that increase access to safe exercise spaces. Gender-sensitive strategies must also account for the unique cultural and societal factors that shape women’s health behaviors globally.

## Conclusion
Obesity trends emphasize the urgent need for comprehensive, gender-sensitive, and region-specific interventions. Policymakers must prioritize targeted strategies that address the root causes of obesity, including socioeconomic disparities, cultural norms, and access to health resources. Public health campaigns emphasizing balanced diets, regular physical activity, and awareness of obesity-related risks are critical in reducing the growing prevalence of obesity worldwide.

Moreover, community-level initiatives that empower individuals to make healthier choices can have profound impacts. These initiatives should focus on increasing accessibility to fresh, affordable, and nutritious foods while fostering environments that encourage physical activity. For example, urban planning that integrates parks and recreational facilities can help combat sedentary behaviors, particularly in densely populated areas.

The findings also highlight the need for international collaboration to tackle obesity on a global scale. Countries with high obesity rates must share best practices, such as implementing policies to regulate the marketing of unhealthy foods and beverages. Partnerships between governments, non-governmental organizations, and the private sector can further drive innovation in obesity prevention strategies. Ultimately, a multifaceted approach that combines policy interventions, community engagement, and global cooperation is essential to reversing the upward trend in obesity and improving health outcomes for all.

## Figures 
```{figure} images/WHO Overweight Prevalence Map Female.png
:label: Female-Overweight
:alt: Overweight Prevalence Map for Females 
This picture describes obesity trends in the UK and US for females from 1990 to 2016.
```

```{figure} images/WHO Overweight Prevalence Map Male.png
:label: Male-Overweight
:alt: Overweight Prevalence Map for Males 
This picture describes obesity trends in the UK and US for males from 1990 to 2016.
```

```{figure} images/Obesity_Trends_US_UK.png
:label: Combined-Graph
:alt: Obesity Trends for UK and US combined graph
This picture depicts a side by side comparison of obesity trends in the UK and US for both males and females from 1990 to 2016. It can also be found in the analysis document. 
```
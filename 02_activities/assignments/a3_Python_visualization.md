I chose the EarlyON Child and Family Centers dataset: https://open.toronto.ca/dataset/earlyon-child-and-family-centres/
    > What software did you use to create your data visualization?
Python(plotly)
    > Who is your intended audience? 
Community planners, policy makers, and local government stakeholders who want a quick snapshot of the distribution and density of EarlyON Centres across different wards. Could also be used by researchers or nonprofit organizations interested in service coverage or child care resource allocation in Toronto.
    > What information or message are you trying to convey with your visualization? 
A bar chart showing how many EarlyON Child and Family Centres exist in each City Ward. This helps identify which wards might have the highest or lowest number of centres and can serve as a starting point for resource planning.
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
Substantive:
- The chart reflect real counts and is an honest representation of the dataset.
- All wards present in the data are shown.
Perceptual:
- A bar chart is used so that differences in height are easy to compare visually.
- Clear labeling of wards on the x-axis and the count of centers on the y-axis.
Aesthetic:
- Used a clean layout, ensuring that unnecessary chart elements (clutter) are removed.
- Title and axis labels are concise and descriptive: “Number of Centers” or "Ward Name".
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
- Using Python code ensures reproducibility because anyone with the same dataset and the script can run it to generate the exact same chart.
    > How did you ensure that your data visualization is accessible?  
- The bar chart uses sufficiently contrasting colors so that people with color vision deficiencies can distinguish between bars and background.
- Large fonts and descriptive alt-text (e.g., “Bar chart showing the count of EarlyON Centres by ward.”) can be included in any digital publication.
    > Who are the individuals and communities who might be impacted by your visualization?  
- Parents, caregivers, and young children who use EarlyON Centres could be affected by any insights leading to redistribution or expansion of services.
- Agencies that manage the centres could reallocate resources based on this information.
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
- Included: Ward name/number, counts of centres (program_name).
- Excluded: Full address details and geocoordinates. This level of detail wasn’t needed for the high-level distribution count.
    > What ‘underwater labour’ contributed to your final data visualization product?
- Data cleaning (checking for data format inconsistencies, missing wards).
- Data validation (verifying wards are properly named or coded).
- Research to understand the City Ward boundaries and naming conventions.
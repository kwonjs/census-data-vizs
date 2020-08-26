# Visualizing Census Data/Census-Related Data

_**DISCLAIMER**: Much of the data sourced is from the 2017 American Community Survey. At the time I conducted this mini-project, I wasn't aware that the census data I was using was based on 1-year and 5-year **estimates** with associated margins of error, calculated using [custom U.S. Census Bureau projections](https://www.census.gov/content/dam/Census/library/publications/2018/acs/acs_general_handbook_2018_ch08.pdf). I acknowledge that I should have been much more cautious in presenting this data and extrapolating any policy-influencing conclusions from the visualizations._ 

These visualizations were created as an independently-led project I did during the 2019 [Data Discovery Summer Program](https://data.berkeley.edu/research/discovery-program-home). That summer, the research cohort focused on developing ways to raise awareness about the importance of the decennial U.S. Census. I decided to create visualizations using the most recent census and census-related data at the time that showed users how they could look up different statistics related to SNAP - the Supplemental Nutrition Assistance Program - and health insurance coverage as a way to gauge how the counties or states they lived in compared to the rest of the U.S. 

### Statistics on SNAP (Supplemental Nutrition Assistance Program)

<iframe seamless frameborder="0" src="https://public.tableau.com/views/FoodStampsSNAPStatsbyCounty/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '980' height = '700' scrolling='yes' ></iframe>    

_The Center of Budget and Policy Priorities has interactive factsheets on who benefits from SNAP in each state. [Click here](https://www.cbpp.org/research/food-assistance/a-closer-look-at-who-benefits-from-snap-state-by-state-fact-sheets) to view up to date information on your state!_

In California, SNAP is known as [CalFresh](https://www.cdss.ca.gov/inforesources/calfresh), a state-supervised and county-operated program. Before it was named SNAP, the program was colloquially known as "food stamps." Folks who qualify for CalFresh receive an EBT, or an Electronic Benefits Transfer card that works similarly to a debit card, that they can use in EBT-card-accepting grocery stores, farmer's markets, and co-ops to buy groceries each month. Students at UC Berkeley can assess their [eligibility](https://calfresh.berkeley.edu/eligibility/) to receive SNAP and get help with applying for benefits at [Cal's CalFresh website](https://calfresh.berkeley.edu/#apply). Students who aren't married and have no dependents are usually eligible to get up to [$194 per month](https://www.cbpp.org/research/food-assistance/a-quick-guide-to-snap-eligibility-and-benefits) in CalFresh benefits (as of the fiscal year 2020).

With [just under 40 million people](https://www.cbpp.org/research/food-assistance/a-closer-look-at-who-benefits-from-snap-state-by-state-fact-sheets) relying on SNAP in 2019, the Trump administration's attempts to cut SNAP's federal budget (i.e. setting [stricter work requirements](https://www.usda.gov/media/press-releases/2019/12/04/usda-restores-original-intent-snap-second-chance-not-way-life) tied to SNAP eligibility) would cut [hundreds of thousands](https://www.npr.org/2019/12/04/784732180/nearly-700-000-snap-recipients-could-lose-benefits-under-new-trump-rule) of residents from food assistance and disproportionally harm those living in certain counties in certain states (i.e. Glasscock and Loving Counties, TX) or  states/territories like Puerto Rico, where over 80% of households living below 2017 federal poverty level in some municipios/municipalities and over 50% of households in some municipios/municipalities with one or more disabled*** members relied on SNAP. 

This project was done before the COVID-19 pandemic. As of August 2020, the administration has temporarily stopped the implementation of SNAP work-related eligibility restrictions and has issued waivers to all states. The [U.S. Dept. of Agriculture](https://fns-prod.azureedge.net/sites/default/files/resource-files/CA-SNAP-COV-EmergencyAllotmentsExtension5-Acknowledged.pdf) approved the suspension of these restrictions up until September as part of the "Families First Coronavirus Response Act of 2020," stating that "states that have already received Food and Nutrition Service approval for Emergency Allottment (EA) issuance in March and April, or April and May" by having confirmed COVID-19 cases and being impacted economically by pandemic-related mandates "are approved to continue issuing EA benefits each month." 

*** *I usually use identity-first rather than person-first language when discussing disability. [Click here](https://thebodyisnotanapology.com/magazine/i-am-disabled-on-identity-first-versus-people-first-language/) to read one article that explains this standpoint.* 

### Statistics on health insurance coverage (2017)

#### Health insurance coverage by sex & age group

<iframe seamless frameborder="0" src="https://public.tableau.com/views/ofpopulationwhealthinsurancecoveragebyagesexandcountyin2017/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '980' height = '700' scrolling='yes' ></iframe>   

#### Percent insured and uninsured below 100% federal poverty level

<iframe seamless frameborder="0" src="https://public.tableau.com/views/HealthcareInsurance2017-PercentUninsuredInsuredbelow100ofPovertyThresholdbyCounty/uninsinsbelowpov?:embed=yes&:display_count=yes&:showVizHome=no" width = '900' height = '860' scrolling='yes' ></iframe>  

#### Statistics on _public_ health insurance coverage

<iframe seamless frameborder="0" src="https://public.tableau.com/views/PublicHealthInsuranceCoverageStatsbyCounty/healthinsmedicaremedicaid?:embed=yes&:display_count=yes&:showVizHome=no" width = '900' height = '860' scrolling='yes' ></iframe>  


Note on the coloring schemes: In the "Medicaid vs. Medicare coverage, by county (sorted by percent (%) public coverage of total population)" visualization, the **bottom** coloring scheme is based off of U.S. Census Bureau-designated regions. 
* Region 1, the Northeast (colored BLUE), encompasses New England (Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont) and the Mid-Atlantic (New Jersey, New York, and Pennsylvania. 
* Region 2, the Midwest (colored YELLOW), encompasses East North Central (Illinois, Indiana, Michigan, Ohio, and Wisconsin) and West North Central (Iowa, Kansas, Minnesota, Missouri, Nebraska, North Dakota, and South Dakota). 
* Region 3, the South (colored RED), covers the South Atlantic (Delaware, Florida, Georgia, Maryland, North Carolina, South Carolina, Virginia, District of Columbia, and West Virginia), the East South Central (Alabama, Kentucky, Mississippi, and Tennessee), and the West South Central (Arkansas, Louisiana, Oklahoma, and Texas).
* Region 4, the West (colored GREEN), contains the Mountain (Arizona, Colorado, Idaho, Montana, Nevada, New Mexico, Utah, and Wyoming) and the Pacific regions (Alaska, California, Hawaii, Oregon, and Washington).

## Census-related data: Income inequalities across the U.S. in 2015 (Economic Policy Institute)

Data from the decennial census and other surveys like the U.S. Census Bureau's American Community Survey can also highlight **income inequality**, a phenomenon that drives wealth inequality and, on a national scale, perpetuates the widening gaps in coverage related to health insurance or food assistance. 

<iframe seamless frameborder="0" src="https://public.tableau.com/views/Ratiooftop1incometobottom99incomeforallU_S_countiesin2015/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '900' height = '860' scrolling='yes' ></iframe>  
_[Click here](https://www.epi.org/publication/the-new-gilded-age-income-inequality-in-the-u-s-by-state-metropolitan-area-and-county/#epi-toc-14) to see the data source (go to "Appendix Table B2"). The Economic Policy Insitute also created [an interactive factsheet](https://www.epi.org/multimedia/unequal-states-of-america/#/California) where users can search up their state's income inequality levels._

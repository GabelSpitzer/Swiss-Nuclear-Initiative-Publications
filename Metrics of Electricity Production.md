# Metrics of Electricity Production
Modern grids don't typically consist solely of a single electricity production technology. Different technologies serve different roles within the grid, some of them supply a cheap and stable supply, some of them have very low emissions but are difficult to control, some excel at providing electricity quickly on demand. We will try to explain some of the most relevant decision-guiding metrics of electricity producing technologies in this article. 
## Introductory information and some examples
To understand the meaning of many of the parameters below it is important to know that they are usually evaluated over the life cycle of a project and either reported as an impact per unit of electricity or rated output. For example you have probably seen the cost of your electricity given to you in CHF/kWh (cost per unit of electricity) and if you've bought solar panels you may have seen their cost given to you in CHF/kW (cost per rated output). Understanding the difference is vital since values reported relative to the rated output may not give you a fair comparison without this understanding.
### Capacity factor
The capacity factor states how 'active' a given electricity producer is and is calculated by dividing the electricity a power plant or other source of electricity produces throughout its life by the electricity it could have produced if it constantly produced 100% of its rated output (*comment: e.g.: a 1kW solar panel has the capacity to produce 8760 kWh. If it only produced 1314 kWh in a given year then the capacity factor for that year is 1314/8760 = 15%). Different methods of generating electricity have different reasons for not operating 100% of the time. Gas fired power plants usually reduce their output when the price of electricity is low, because the cost of fuel is a major driver for the cost of their electricity. Most nuclear power plants have month-long periods of maintenance and refuelling. Solar and wind power are weather dependent in their output, with solar power typically having no meaningful electricity production during the night.
### Life-cycle assessments and project lifetimes
The life cycle assessment (LCA) of a project usually starts with the mining of the materials necessary for the equipment and ends in the recycling or disposal of all materials used in the project (this is called "cradle to grave"). Knowing whether an LCA is taking the "cradle to grave" approach or not is very important in order to understand the meaning of the results. Comparing the life cycle greenhouse gas (GHG) emissions of a coal-fired power plant with a similarly sized solar PV installation will yield very different results if you include the emissions from the production of the power plant and solar panels or if you are only looking at operating emissions (i.e coal being burned vs a solar panel just existing). In order to produce comparable numbers we usually take the impacts of a project over its lifetime and divide them by the power produced throughout its lifetime.


## GHG intensity
Different greenhouse gasses have different impacts on climate change, some molecules being more severe in their impact on the global climate than others. Methane is approximately 28 times more effective than carbon dioxide as a greenhouse gas per unit of mass, thus 1 kg methane corresponds to 28 kgCO2eq [1][p.47]. The exact behaviour is a bit more complex than this. Not all of these gasses remain in the atmosphere for the same amount of time, thus having different global warming potentials over different time horizons, for instance, the above number for methane refers to the global warming potential it has over the course of 100 years [1][p.47]. Some gasses have additional negative effects, such as depleting ozone (e.g. chlorofluorocarbons [1][p.117] used in old refrigerators), which are not well conveyed with the carbon dioxide equivalence unit.
Leading sentence into the next section: 
## Pollution
## Health aspects
Will require a deeper article, mortality and morbidity need to be explained here and we link to 'which power source is the safest'
## Scalability
- Geographic limitations
    - e.g. only certain places have the geography needed for dams, sun and wind availability differ geographically, thermal PPs need cooling water.
- Fuel limitations
## Land usage
## Pilotability
- Ramp rate
- Daily availability and variance
- Seasonal availability and variance

## Water usage
This section probably won't appear in the final article





## Costs (e.g. LCOE)
The LCOE is the amount of money which a power producer needs to receive per unit of energy for the life of the power plant to break even. It is calculated by dividing the all of the costs accrued throughout the life of a power producer by the power it produced. This takes into account the capital and operating costs, such as the power plant and fuel, as well as the cost of capital which is associated with necessary bank loans or investors expected returns, namely the discount rate. This latter parameter is particularly important for projects with high capital costs (up-front costs), since the rate of return expected by investors can have a large impact on the overall LCOE. Of the widespread electricity generation methods nuclear power is most sensitive to the discount rate [2] There are more nuanced aspects of calculating an LCOE, but those will not be covered here. Suffice it to say that the LCOE calculation assumes some parameters associated with costs and is summarised as a cost per unit of electricity, such as USD per kWh

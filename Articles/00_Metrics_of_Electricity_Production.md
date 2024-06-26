# Metrics of Electricity Production

*Note: all numbered references herein are those taken from the Technology Report. I don't know how to do references easily in Git, we may want to switch over to Overleaf for this aspect unless we find a simple way to do citations (also has version history, etc.)*

Modern grids don't typically consist solely of a single electricity production technology. France doesn’t exclusively power their grid with nuclear power, the Netherlands don’t exclusively produce their electricity with wind turbines. Different technologies serve different roles within the grid, some of them supply a cheap and stable supply, some of them have very low emissions but are difficult to control, some excel at providing electricity quickly on demand, some are cheap and some are expensive. We will try to explain some of the most relevant decision-guiding metrics of electricity producing technologies in this article.

## Introductory information and some examples

To understand the meaning of many of the parameters below it is important to know that they are usually evaluated over the life cycle of a project and either reported as an impact per unit of electricity or rated output. For example you have probably seen the cost of your electricity given to you in CHF/kWh (cost per unit of electricity) and if you've bought solar panels you may have seen their cost given to you in CHF/kW (cost per rated output). Understanding the difference is vital since values reported relative to the rated output may not give you a fair comparison without this understanding.

### What is a capacity factor

When we talk about electricity generators there is a difference in their maximum output and what they actually produce. This difference is captured in the capacity factor and the differences in capacity factors between common Swiss sources of electricity may surprise you.

![image](https://github.com/GabelSpitzer/Swiss-Nuclear-Initiative-Publications/assets/113603228/e6de9734-c262-4390-a943-614c2ce1bdda)

The capacity factor states how 'active' a given electricity producer is. It is calculated by dividing the electricity a power plant or other source of electricity produced during some amount of time (usually a year) by the electricity it could have produced (*comment: e.g.: a 1kW solar panel has the capacity to produce 8760 kWh in a year. If it only produced 1314 kWh in a given year then the capacity factor for that year would be 1314/8760 = 15%). Different electricity generators have different reasons for not always operating or not operating at full capacity: 

- Gas fired power plants usually reduce their output when the price of electricity is low, because the cost of fuel is a major driver for the cost of their electricity.
- Most nuclear power plants take weeks to refuel, though this usually only happens one every 12-18 months.
- Solar and wind-based electricity producers are weather dependent in their output, with solar PV typically having no meaningful electricity production during the night.

Capacity factors are not static, they may change with time as maintenance is required or if external factors (such as the weather) are at play. The figure below illustrates how the average annual Swiss nuclear power plant capacity factor has changed over the course of the last few decades.

![image](https://github.com/GabelSpitzer/Swiss-Nuclear-Initiative-Publications/assets/113603228/405cd304-5ab7-4fc0-a41b-b723160c21fd)

The line shows the maximum capacity (sum of installed nuclear power plant capacities in GWh), the bars show the power produced by NPPs in any given year (also in GWh) and the dots show the average capacity factor for that year based on the prior two data (in % on the right). 1984 and 2019 are peculiar outliers since the former marked NPP Leibstadt coming online and the latter NPP Mühleberg being decommissioned. We saw the capacity factor steadily increasing until the start of the last decade. Large maintenance projects and upgrades such as the 2015 upgrades to the [Beznau 1&2 emergency power systems](https://www.axpo.com/ch/en/energy/generation-and-distribution/nuclear-power/beznau.html), as well as environmental factors such as hot river temperatures in some years have resulted in a lower average capacity factor in the last decade. Like nuclear power, the capacity factors for other types of electricity generators also vary.

### Life-cycle assessments and project lifetimes

Life cycle assessments (LCAs) are a type of report in which we look at the impacts a project has had over the course of its lifetime. Every project has costs, economic, environmental and social and life cycle assessments can show all of these at the same time. A given electricity producer may have the lowest impact on the global climate, but may result in the most wildlife being impacted or the highest degree of social injustice. It is important that we are able to view our potential sources of electricity in the full context of their impacts so that we can make fair and informed decisions. LCAs are highly variable in what they focus on. Some LCAs are purely economic, some purely environmental, some are combinations of both. The list of different metrics within LCAs is quite long too. We explain the ones we think are most relevant later in this section.

### How is an LCA made?

The LCA of a project usually starts at the mining of the materials necessary for the equipment and ends at the recycling or disposal of all materials used in the project (this is called "cradle to grave"). Knowing whether an LCA is taking the "cradle to grave" approach or not is very important in order to understand the meaning of the results. Comparing the life cycle greenhouse gas (GHG) emissions of a coal-fired power plant with a similarly sized solar PV installation will yield very different results if you include the emissions from the production of the power plant and solar panels or if you are only looking at operating emissions (i.e. coal being burned vs a solar panel just existing).

In order to produce comparable numbers we usually take the impacts of a project over its lifetime and divide them by the power produced throughout its lifetime. Consequently, predictions about the impacts of electricity generators are highly dependent on the assumptions around capacity factors and lifetimes of the equipment. Assuming that a hydroelectric dam will last for 100 years and comparing that to either a 10 or 20 year solar panel will result in a factor 2 difference in the results.+

### Some common metrics you may come across - INCOMPLETE, NEEDS EXPLANATIONS FOR THE DIFFERENT METRICS OR JUST AN EXTERNAL REFERENCE

- Eco points - often used, are an amalgamation of different factors, the balance is highly scenario dependent and thus LCAs based on the same data won’t necessarily have the same results.
- Ecological scarcity: pointes (species-year).
- Freshwater eutrophication: g P eq. per MWh, MEANING
- Water scarcity (?): u.ex. dissipated water in l per kWh       |        UNIT, water scarcity is a particularly subjective parameter in its weighting. Fresh water is not available to us in equal measure around the globe.
- Climate change: GHG emissions (g CO2 eq. per kWh) , GWP or similar
- Ionizing radiation: u.ex. = Sievert per GW-annum
- Human toxicity: u.ex. = CTUh per TWh (carcinogenic and non-carcinogenic)
    - Land use/occupation: u.ex. = points per kWh
- Resource use
    - fossil energy carriers: u.ex. = MJ/kWh
    - minerals and metals:
        - Straight: u.ex. kg/MW or g/MWh, e.g. one MW of solar PV rooftop installation requires about 3070 kg of copper, or 3 kg per kW. Consequently, each MWh of Swiss solar PV rooftop electricity uses about 130 g of copper.
        - Scarcity based: u.ex =  g Sb eq. per MWh - this uses the scarcity of antimony as a measure to compare other material scarcities to. Depletion is calculated based on the global available extractable reserves (material in the ground for which the extraction is economically feasible)

![image](https://github.com/GabelSpitzer/Swiss-Nuclear-Initiative-Publications/assets/113603228/f93ac03a-0845-4892-b5d6-1135283259a2)

The figure above illustrates the issue we are trying to address with our explanations. Critical minerals (such as copper, lithium, rare earths, silicon, ect.) are required for the construction of power plants and other infrastructure. The amount required changes depending on the type of power producer and the figure on the left is how this data was reported in the IEA's report (CONFIRM SOURCE). We care about the amount of minerals needed because each kg of minerals represents the undertaking of a certain amount of mining, refining and permanent waste disposal, usually on foreign soil and often performed in an unsafe manner (e.g. Myanmar, Chinese silicon, etc.). The left figure shows the mineral requirements in kg/MW, with solar PV being less than twice as mineral intense as hydroelectricity on a per-MW basis. But what does this mean? Solar PV and hydroelectricity are active for very different amounts of times and have substantially different expected life times, so whilst it seems as if these values are comparable, the figure on the right shows that the mineral intensity of solar PV per unit of electricity (g/MWh) is more than 21 times higher than that of hydroelectricity (* comment = these numbers reflect solar PV rooftop installations and hydroelectric dams in the Swiss context. Note that the units have changed from kg to g between the two metrics. Data was obtained from the IEA "The Role of Critical Minerals in the Clean Energy Transition" report, assumptions for the right side of the figure can be found in HERE{link to appendices or something, list lifetimes, capacity factors, etc.}).

## Greenhouse gas (GHG) intensity and climate change

GHGs, like carbon dioxide, reduce our planets ability to cool itself, meaning that a higher concentration of GHGs in our atmosphere results in a higher average global surface temperature. Many GHGs are produced naturally and global warming and cooling events have regularly occurred, for instance through the [volcanic emission of sulphur dioxide (SO2)](https://scied.ucar.edu/learning-zone/how-climate-works/how-volcanoes-influence-climate). Whilst GHGs occur naturally, they are also produced by human activity and we are much faster at pumping GHGs into the atmosphere than nature seems to be, resulting in the rapid climate change we are seeing today. 

### What is a GHG?

Any gas which has the potential to change the planet's cooling ability is a GHG. We separate GHGs into two broad classes, direct and indirect GHGs. Direct GHGs interact with light and convert some of it to infrared radiation. They have a "direct radiative forcing effect", examples of these are carbon dioxide (CO2), methane (CH4) and chlorofluourocarbons. Indirect GHGs are gases which don't exhibit a direct radiative forcing effect but do affect the overall radiation balance on a global scale. SO2 is an example of an indirect GHG which results in the planet becoming cooler through cloud seeding and other effects. Methane is another example of an indirect GHG, though with a warming effect, because the decomposition of methane in the atmosphere results in the production of CO2.
Please click [here](https://ghginstitute.org/2010/06/15/what-are-greenhouse-gases/) to find out more about what a GHG is.

### What do Global Warming Potential (GWP) and the kgCO2eq unit mean?

The most common metric to compare different emissions with respect to their climate change impact is GWP, the measure of the cumulative radiative forcing a single large emission would have caused relative to CO2 after a certain number of years had passed. 

Different GHGs have different impacts on climate change, some molecules being more severe in their impact on the global climate than others. On a 100 year time horizon (more on that later), methane is approximately 28 times more effective than carbon dioxide as a greenhouse gas per unit of mass, thus 1 kg methane is equivalent to 28 kilograms of CO2 (kgCO2eq) [1][p.47]. The exact impact depends on several factors which we will not get into here, but suffice it to say that reality is a bit more complicated than a single carbon dioxide equivalency value. When countries or companies report on their GHG emissions they usually have a specific selection of GHGs they are reporting on, usually [those covered by the Paris agreement](https://www.europarl.europa.eu/topics/en/article/20230316STO77629/climate-change-the-greenhouse-gases-causing-global-warming), not the entire spectrum of all GHGs. A good example of an indirect GHG which is usually not reported on is hydrogen, which is about [11.6 times more effective as a GHG than CO2](https://www.nature.com/articles/s43247-023-00857-8).

### Time horizons

Not all of these gasses remain in the atmosphere for the same amount of time, thus having different global warming potentials over different time horizons. Methane, for instance, is approximately [120 times more effective than CO2 as a GHG](https://pubs.rsc.org/en/content/articlehtml/2018/em/c8em00414e#:~:text=GWP%20is%20used%20widely%20across,indirect%20climate%20effects%20are%20included).) (in terms of radiative forcing) directly after it is emitted; however, it is degraded in the atmosphere over time into CO2 and thus the GWP it has over the course of 100 years is 28 years[1][p.47] instead of 120. 100 years is the current standard reporting time horizon though there is a push by some to adopt shorter time horizons since policy changes are looking at 2050 target. Changing the time horizon changes the results considerably, since methane on a 20 year time horizon is [86 times effective as CO2](https://www.gti.energy/wp-content/uploads/2019/02/CMR-Implications-Using-Different-GWP-Time-Horizons-White-Paper-2019.pdf) in terms of radiative forcing, three times worse than the 100 year time horizon.

![image](https://github.com/GabelSpitzer/Swiss-Nuclear-Initiative-Publications/assets/113603228/20e0b0d8-f177-4018-b33c-af67b4591f82)
https://pubs.rsc.org/image/article/2018/EM/c8em00414e/c8em00414e-f5_hi-res.gif
### Criticisms of GWP and alternatives to it

The GWP metric has received a lot of criticism from the scientific community. GWP, [they argue](https://pubs.rsc.org/en/content/articlehtml/2018/em/c8em00414e#:~:text=GWP%20is%20used%20widely%20across,indirect%20climate%20effects%20are%20included).), does not represent the climate change effects of GHGs accurately since 

- the GWP measures radiative forcing instead of the resulting temperature change (between which the relationship is not linear),
- time horizons are chosen seemingly arbitrarily
- GWP looks only at pulse emissions (*A pulse emission is emitted in an instant), which do not reflect the real-world emissions which occur over the span of years or decades.

The most popular alternative to GWP is Global Temperature change Potential (GTP), a metric which estimates the global mean surface temperature change due to a pulse emission at a certain point in time after the emission has occurred (so only the current effects of the emission, not the cumulative effects). This metric has received enough popularity to be included in the International Panel on Climate Change reports. Since the GTP investigates only the current effects of a prior emission it is not a good replacement for GWP. For that purpose the Integrated Global Temperature change Potential (IGTP) has been created. Several other metrics exist which measure the impact of GHGs on the global climate, such as the [Sustaine-flux global warming potential](https://essd.copernicus.org/articles/8/605/2016/) or the [temperature proxy index](https://link.springer.com/article/10.1007/s10584-009-9566-6), though they are not as widely used as GWP or GTP.

GHGs are only one of the many ways in which the electricity sector impacts our environment. We often focus on GHGs because their influence on the climate is posing a global threat, but the electricity we receive in our homes has a wider pollution history than just GHGs.

## Pollution and its ecological impacts - may just be renamed to be “ecological impacts” to become a broader section, with pollution becoming a partial section within it

Note: I am fighting myself (Mark) in this section. The actual metrics are extremely boring to most people because almost no one is going to care about the differences in regional ecotoxicity and their weighting, or the degree to which a mineral is toxic in a specific application in several different ways. What matter is that there are metrics for these things and that they are considered; however, if we never actually mention the specific metrics used to do that then I probably should not dive deeply into how this is done in an LCA or LCIA but rather link to an explanation on how and this is done and only give a “why” this is done. The purpose of this section thus becomes to give some background knowledge to the “externalised impacts” article and the “waste” article. Any other points?

Almost all construction or mining project will inevitably impact the environment, some of these happen near us and some of them very far away. In the case of wind turbines this would be the local population of birds near the wind turbine and abroad some of the impacts are the habitat destruction of the fish, gibbons and red pandas of Myanmar where materials for the wind turbine are sourced from ([GLOBAL WITNESS ARTICLE](https://www.globalwitness.org/en/campaigns/natural-resource-governance/myanmars-poisoned-mountains/)) - not to mention the impacts on the people of Myanmar, social injustice in the green energy transition is a topic to itself.

Pollution occurs in many forms, but is broadly defined as the release of harmful materials into the environment. Pollution may enter the environment in a gaseous or aerosol form or by being dissolved or carried by water streams. The most relevant measures for pollution are the ecotoxicity (unit), 

Some types of emission are produced at the electricity production site. The Combustion fumes from coal, natural or biogas fired power plants are examples of this. Much of the pollution is produced during mining, refining, transportation or equipment production. Fine particles (harmful to human and animal welfare) and noxious gases are part of the air pollution issue. Mining and refining may result in heavy metals being released into the ecosphere, such as EXAMPLE or arsenic from steel smelting CITATION.

This section will require the most work, it is a catch-all for a lot of different sections and I’m still figuring out how to integrate those

Link to air pollution article, link to waste article, detail some of that information here too. 

Content:

- What pollution is (definition) and explain why pollution should matter to the reader and the difference between
    - National pollution
    - International pollution
- Explain broad metrics
    - Ecological scarcity (species elimination as consequence of pollution): UNIT, MEANING
    - Eutrophication: UNIT, MEANING
    - Ecotoxicity (freshwater, marine and terrestrial)
    - Acidification
    - Particle emissions (into health)
    - Radiation (into health)
    - Don’t be confused by eco points (used by BFE in CITE) - it includes ecological scarcity but also other factors (such as EXAMPLE), which have little to do with the meaning we usually assign to the word “eco”
- What do we emit?
    - particle, chemical and radiological pollution
- How do we pollute
    - air - air quality index (AQI) is usually the metric for local air quality
    - ground
    - water
- tailings dams and failing rates (waste inevitably ends up washing into the environment)
- nuclear waste storage

## Health aspects - pollution and accidents

Will require a deeper article, mortality and morbidity need to be explained here and we link to 'which power source is the safest'

Content:

Talk about the difference between effects of pollution and accidents (two primary causes of negative health aspects from electricity generation)

- accident risk
- risk vs hazard
- morbidity
- mortality
- Disclaimer about unknowns for mortality and morbidity, e.g.
    - small accidents usually not listed, Variable renewables highly likely to primarily have these events since they require more installation work for more but smaller sites
    - accidents in supply chains (e.g. tailings dam failings)
- conclusions

## Scalability

Scaling limits in this document are factors which limit the maximum power that can be produced with an electricity generation method. For renewable energy sources we have provided the amount of energy Switzerland could produce per year with the resources it has. For non-renewable energy we have limited ourselves to scaling limits associated with overall fuel availability, providing the number of years for which the world could be powered if the current primary energy consumption remained constant at the global consumption level of 2021 (595 EJpa [5][p.9]) if all energy were sourced from the generator under investigation and with only those resources which are confirmed to exist and are economically available. This value is not the number of years left of each resource at our current ate of consumption for that resource. Estimating the future global energy consumption is a very complex process, highly dependent on assumptions and consequently few estimates agree with each other, although the average is an increasing trend until at least 2050 [6][p.817]. Estimating the amount of energy that would be consumed per resource is even more assumption dependent and thus we chose to provide a different value which is independent of these assumptions.

- Geographic limitations
    - e.g. only certain places have the geography needed for dams, sun and wind availability differ geographically, thermal PPs need cooling water.
- Fuel limitations

## Land usage (m2/kWh)

Why does this matter to the reader

- Local land usage: energy infrastructure in nature (Solar PV in the alps, on fields and wind turbines in forests, visible from home, on mountains, etc.), waste storage from NPPs, flooding of nature from dams
- International land usage: mining and waste storage abroad, destruction of nature, possibly against the will of the people (e.g. Mayenmar, Papua New Guinea)
- Possibly taking away land from other uses such as farming

Content:

- Figure comparing land usage of different sources of electricity
- Disclaimer about nonsensical differences in how waste storage is accounted for: 100’000 years for nuclear waste storage vs 100 years for forever waste from the mining sector. Warning that it is difficult to find numbers which give fair comparisons and that there are a lot of unstated underlying assumptions flowing into any estimate (e.g. does the wind turbine end in a landfill or does everything get recycled? Often scientists just take the standard from a dataset, which may not be applicable to your specific situation)
- Discuss how solar PV and wind turbines have different numbers to detail land usage
- Solar PV on rooftops isn’t taking away any further usable land when installed (some additional land used for structural purposes)
- Installed wind turbine footprint may be listed as the footprint of the tower, the area diameter of the blades or the entire area which is unusable for the next turbine (i.e. how much area does an individual turbine need before the next one can be built behind it)
- NPP smallest local footprint (I think), smallest mining impact (I think), waste is stored underground and deteriorates over time.
- Gas and coal require their fuel to be mined
- Biomass-based fuels require the most land. This can lead to increased carbon intensity if land needs to be cleared for biofuel crops to be planted (high initial emissions from a grassy field being converted into a biofuel crop field).

## Piloting potential

Piloting potential describes the degree of control which a producer has over the output of its electricity generator. Power demand is not constant; thus, the price of electricity varies. As such, it is desirable to be able to control the amount of power one produces if a valuable commodity is consumed during the production of electricity. Additionally, an overall grid needs to be able to match demand and thus needs to have sufficient overall piloting potential to always match demand when needed (a high degree of variable renewables in a grid makes this challenging).

The unit used in this document (ramp rate) is the degree to which a generator can change its power output as a percentage of its maximum power per minute once it is operating. Some methods of generating power, such as solar PV and wind, do not allow much control over the output since their output is dependent on environmental circumstances. Wind turbines can be slowed down intentionally, so there is some control over the ramp-down rate.

### Ramp rate (% per minute/hour)

Variable renewable sources of electricity such as wind and solar power are becoming more prevalent in global electricity production and are usually not pilotable. Taking solar PV as an example: there are daily peaks in production, lower rates of production in the mornings and evenings and essentially no electricity production at night. Additionally, clouds, rain and snow may affect daily production unexpectedly. Seasonally we expect a significantly lower electricity production from solar power in winter than in summer.

This leaves gaps in electricity production which need to be filled by alternative electricity producers, necessitating power plants to increase or decrease their production on demand. The rate at which a power plant can change its output, the ramp rate, is usually reported as percentage change of total output by which it can increase or decrease its output per minute. In many electricity networks specialised power producers which focus on very fast delivery of power in shorter windows, such as open cycle gas turbines (OCGT) are needed. These are usually more expensive in their LCOE than their CCGT counterparts since they usually do not operate continuously. In Switzerland the large hydroelectric sector usually addresses the national peak demand, with imports covering what remains.

Besides the ramping rate is relevant on a daily basis and shorter time-frames, the time needed to start up a power plant after it has been shut down is important when looking at longer time-frames, as maintenance and extenuating circumstances often require it. The hot start-up time is the time a power plant requires to achieve normal operating conditions after it has been shut down for less than 8 hours (or if the boiler and turbine have been pre-heated on thermal power plants).

Ramping rates are not constant for most power generation methods over their entire spectrum of operation. A cold start (at ignition of fuel for thermal power plants) may mean several hours or even days of operation before the full power output can be achieved. Currently the vast majority of US hydroelectric plants require fewer than 10 minutes to achieve full power from a cold start, whilst the vast majority of the US nuclear power plants require more than 12 hours [4] Shorter start-up times are preferred over longer start-up times. Nuclear power has particularly long start-up times due to reactor poisons being high in concentration shortly after a reactor shutdown, as well as the safety measures which are taken when nuclear reactors start up. Since nuclear reactors are usually shut down at most once per year the long start-up time is not of great importance, as reflected by its relatively high capacity factor. It is not in the interest of the nuclear power plant operator to follow load in most cases due to the low cost of fuel and increased maintenance costs from ramping.

## *Water usage*

*This section probably won't appear in the final article, but if it did then it would speak about the threat of droughts in the uncertain climate of the future where extreme weather is likely going to become more regular than today (citing historic extreme weather event increase rates). It would then highlight how most electricity sources use water at some point of their life-cycle, every one in the equipment production (because mining and refining require lots of water) and most (barring wind and solar power) also during operation. Interesting data in this section would be the relative water intensity of hydroelectricity and nuclear power, showing the amount of water which currently evaporates per kWh in Swiss hydroelectric dams.*

## Costs (e.g. LCOE)

The LCOE is the amount of money which a power producer needs to receive per unit of energy for the life of the power plant to break even. It is calculated by dividing the all of the costs accrued throughout the life of a power producer by the power it will likely produce. This takes into account the capital and operating costs, such as the power plant and fuel, as well as the cost of capital which is associated with necessary bank loans or investors expected returns, namely the discount rate. This latter parameter is particularly important for projects with high capital costs (up-front costs), since the rate of return expected by investors can have a large impact on the overall LCOE. Of the widespread electricity generation methods nuclear power is most sensitive to the discount rate [2] {IT IS POSSIBLE THAT HYDRO IS AS SENSITIVE, LONG OP LIFE}. There are more nuanced aspects of calculating an LCOE, but those will not be covered here. Suffice it to say that the LCOE calculation assumes some parameters associated with costs and is summarised as a cost per unit of electricity, such as USD or CHF per kWh.

# Assigment 3

## 1. What is the approximate energy consumption per year
**Estimate the approximate annual energy consumption for a functional unit including an AI solution that you must choose.**

In this study, we consider an agricultural UAV equipped with an integrated artificial intelligence (AI) system for real-time crop monitoring and targeted pesticide application. Such drones combine multispectral or RGB imaging with onboard machine learning models that detect crop stress or pest infestations and autonomously trigger localized spraying.

Recent research shows that agricultural UAVs equipped with onboard AI systems can perform real-time decision-making during flight. For instance, a low-cost autonomous spraying drone using a deep learning model for palm plantations was shown to operate with an AI module consuming only about 1.5 W during inference [10]. In such platforms, the overall energy consumption is dominated by propulsion and spraying operations, while the embedded AI represents less than 1% of the total power demand.

According to empirical field data, spraying UAVs are typically active for about 95 to 140 hours per year, depending on crop type and region [11].
Considering a realistic spraying workload of approximately 100 hours of effective flight per year and an average flight power of 6–10 kW (values typical for professional spraying drones such as the DJI Agras series [12]), the annual energy consumption of such an AI-enhanced UAV can be estimated as:

$
E_{annual}​=P_{flight}​×t_{annual}​=8000W×100h=800 kWh/year
$

Including the energy consumption of the onboard AI, the total energy consumption reaches approximately 0.9 MWh per year for a fully operational AI-enabled agricultural drone.

In summary, a modern multifunctional drone integrating multispectral imaging and onboard AI typically operates for around 100 hours per year, consuming between 0.8 and 0.9 MWh annually. The overall energy consumption is primarily due to propulsion and spraying operations, while the onboard AI accounts for less than 1% of the total energy consumption.

## 2. Are there any Life Cycle Assessment (LCA) studies for your equipment?
**Do any LCA analyses covering your type of equipment or similar systems exist? Which phase of the life cycle (e.g. manufacturing, use, end-of-life) has the greatest environmental impact?**

There are Life Cycle Assessment (LCA) studies covering UAV sprayers used in agriculture. A comprehensive study by Seo et al. (2023) specifically assessed the environmental impact of agricultural UAV sprayers used in Japanese rice farming [8]. This study compared UAV sprayers with conventional boom and power sprayers across multiple environmental impact categories. Additionally, a systematic review of environmental assessments in digital agriculture identified that several LCA studies have been conducted on UAVs and drones used in agricultural settings [4].

Regarding the life cycle phases assessed, the studies reveal important patterns. The hardware production phase, including "the production and assembly of the hardware components, and transportation," was considered in thirteen studies, while "the hardware use phase was part of the system boundaries in 10 studies" [4]. However, end-of-life assessment was less common, with "only 5 studies including it in their system boundaries" [4]. For UAVs specifically, the inputs included materials such as carbon fiber reinforced plastic (CFRP) and aluminum for the body, as well as lithium-ion batteries and chargers [8].

The manufacturing/production phase consistently emerges as having the greatest environmental impact. In the Japanese rice farming study, "machinery accounted for 20–93% of the total impact in each category" for UAV treatments [8]. This finding aligns with broader research showing that "the production of electronic components is an impactful process" which "requires rare-earth elements whose extraction triggers environmental impacts on mineral resource, toxicity and eutrophication" [4]. Furthermore, "it would appear that the more hardware used in DAT, the higher the environmental impacts" [4].

In contrast, the use phase has relatively low environmental impact. For UAV operations, "the contribution of energy to the total environmental impact was <1% throughout the categories" [8]. This is attributed to the short flight times and high operational efficiency of UAVs compared to conventional machinery. Studies that included the complete life cycle of high-tech DATs like UAVs and robots found "contrasting differences, from 19% to 155%, on ecotoxicity, human toxicity, mineral resource use, marine eutrophication, land use and ionising radiations" when production, use, and end-of-life phases were all systematically included [4].

Overall, UAV sprayers demonstrate environmental advantages compared to conventional equipment, as "UAV spraying exhibited a lower environmental impact than did boom- and power spraying – attributed to the weight and fuel consumption of boom and power spraying, which increase the environmental impact associated with material production and energy consumption" [8]. However, the environmental benefits must be weighed against the impacts from hardware production, which remains the dominant contributor to the total environmental footprint of these systems.

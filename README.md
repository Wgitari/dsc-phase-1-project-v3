## Business understanding

### Business problem

Your company is expanding into aviation for commercial and private operations and needs to assess aircraft risks. Your task is to evaluate and identify the lowest-risk aircraft and provide practical recommendations to guide the head of the aviation division in making informed purchase decisions

### Business Objective

The objective is to identify low-risk aircraft for commercial and private operations to support the company's expansion into the aviation industry, ensuring well-informed purchasing decisions.

### Data and Stakeholders Questions

we will use aviation dataset from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters. The dataset can be downloaded from [kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

Shareholders question:
1. What criteria are being used to assess aircraft risk?
     How will safety records, operating costs, maintenance requirements, and regulatory compliance be evaluated to determine the     lowest-risk aircraft?
  
### Data Understanding
### column description

1. Investigation.Type - Describes the type of investigation conducted that is if the event was a full accident investigation or an incident investigation.
2. Injury.Severity - Describes the severity of injuries resulting from the event. I.e Fatal, Non-Fatal Major , minor etc
3. Aircraft.damage - Specifies the extent of damage to the aircraft that is if Destroyed, Substantial or Minor etc.
4. Aircraft.Category - Refers to the classification of the aircraft, such as Airplane, Helicopter, Glider, Balloon etc.
5. Make - The manufacturer of the aircraft, e.g., Boeing, Airbus, Cessna, or other aircraft makers 
6. Model - The specific model of the aircraft, such as 737, A320 and C172 which gives more detailed information about the aircraft's design and specifications.
7. Number.of.Engines - The total number of engines on the aircraft.
8. Engine.Type - Describes the type of engine used in the aircraft, such as Turboprop,Jet, Reciprocating or Electric.
9. Purpose.of.flight - Describes the reason or purpose for which the aircraft was in flight, such as Commercial and Private. 
10. Total.Fatal.Injuries - The total number of fatalities resulting from the accident or incident.
11. Total.Serious.Injuries - The number of serious injuries reported, as defined by aviation regulations, where serious injuries are typically more severe but non-fatal.
12. Total.Minor.Injuries - The total count of minor injuries, which may include injuries that did not require hospitalization or were less severe.
13. Total.Uninjured - The number of people involved in the accident or incident who were unharmed.
14. Broad.phase.of.flight - Describes the general phase of the flight when the accident or incident occurred. Common phases include Takeoff, limb, Cruise, Descent and Landing.
15. Publication.Date - The date when the investigation report or initial findings were published. This can help track the timeline of the investigation and findings.

### Interactive Dashboard

The interactive dashboard serves as a dynamic tool comprising various views that allow users to manipulate and explore different aspects of the dataset. You can view the dashboard [Here](https://public.tableau.com/app/profile/winfred.gitari.karimi/viz/Book1_17258175785820/Dashboard1?publish=yes)

### Summary of data Visualization, interplation and conclusion
**Gragh 1:TOP 10 AIRCRAFT MODELS WITH LOW-RISK ACCIDENTS**- The aircraft model with the highest bar (in this case, "152") is the most frequently involved in accidents that were categorized as low-risk.The accidents did not result in fatalities or serious injuries thus making it a reliable interms of safety for both private and commercial ventures. Model  172, and 150, rank second and 3rd best based on this anlysis  thus could also be realible options.
         
**Gragh 2 :INJURIES BY AIRCRAFT CATEGORY**-•	Based on the graph, blimps, gliders, gyrocraft, powered-lift, ultralight, and balloons appear to represent the lowest-risk aircraft categories. These categories either have no significant fatal or serious injuries, or their contribution to aviation injuries is extremely low. Airplanes and helicopters show a significantly higher risk of injuries, particularly fatal ones, and thus are not considered low-risk.

**Gragh 3 :TOP 5 AIRCRAFT MODELS WITH ONLY MINOR INJURIES**-• Models 172,  150, 172, have highest number of minor injuries meaning the damage in accidents has been minimal and does not pose significant risks to the safety of passengers or crew. This makes these models ideal for less risky operations where safety is important but occasional minor incidents are acceptable.


**CONCLUSION:** Models 152, 172, and 150 consistently show that they are involved in incidents with only minor injuries. These aircraft should be prioritized for purchase, particularly for operations that require reliability and safety.
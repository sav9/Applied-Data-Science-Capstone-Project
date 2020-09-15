Introduction/Business Problem:
The problem we are trying to address is of car accidents in Seattle city. Accidents happen at all times, but if the main causes of accidents are determined, advance warning or mitigating methods can be performed. For example, certain intersections may be more susceptible to accidents due to heavy usage or the way they are constructed. As a result, better street lights can be added (only protected left and right turns) or traffic personnel can be used to direct the cars. We want to analyze the accident “severity” in terms of human fatality, traffic delay, property damage, or any other type of accident bad impact so that advance warning and mitigation strategies can be developed based on insights of what avoidable reasons case these accidents.

The target audience of this analysis is the Seattle government and transportation department. It should identify key causes of accidents and allow them to identify trends for when accidents can be prevented. This will reduce the number of accidents and injuries for the city.

Data: 
The data comes from collision and accident reports in Seattle during the years 2004-present. It was collected by the Seattle Police Department and Traffic Records department. There are 194,673 observations and 38 variables in this data set. Since we would like to identify the factors that cause the accident and the level of severity, we will use SEVERITYCODE as our dependent variable Y, and try different combinations of independent variables X to get the result. Since the observations are quite large, we may need to filter out the missing value and delete the unrelated columns first. Then we can select the factor which may have more impact on the accidents, such as address type, weather, road condition, and light condition.

The target Data to be predicted under (SEVERITYCODE 1-prop damage 2-injury) label.

Other important variables include:
• ADDRTYPE: Collision address type: Alley, Block, Intersection
• LOCATION: Description of the general location of the collision
• PERSONCOUNT: The total number of people involved in the collision helps identify severity involved
• PEDCOUNT: The number of pedestrians involved in the collision helps identify severity involved
• PEDCYLCOUNT: The number of bicycles involved in the collision helps identify severity involved
• VEHCOUNT: The number of vehicles involved in the collision identify severity involved
• JUNCTIONTYPE: Category of junction at which collision took place helps identify where most collisions occur
• WEATHER: A description of the weather conditions during the time of the collision
• ROADCOND: The condition of the road during the collision
• LIGHTCOND: The light conditions during the collision
• SPEEDING: Whether or not speeding was a factor in the collision (Y/N)
• SEGLANEKEY: A key for the lane segment in which the collision occurred
• CROSSWALKKEY: A key for the crosswalk at which the collision occurred
• HITPARKEDCAR: Whether or not the collision involved hitting a parked car


#### Details of the files are as follows: 
#### Predict the damage caused to the buildings due to earthquake
#### train.csv : 

|Varaible| Descrition|
|--------|-----------|
|area_assesed|Indicates the nature of the damage assessment in terms of the areas of the building that were assessed|
|building_id|A unique ID that identifies every individual building|
|damage_grade|Damage grade assigned to the building after assessment (Target Variable)|
|district_id|District where the building is located|
|has_geotechnical_risk|Indicates if building has geotechnical risks|
|has_geotechnical_risk_fault_crack|Indicates if building has geotechnical risks related to fault cracking|
|has_geotechnical_risk_flood|Indicates if building has geotechnical risks related to flood|
|has_geotechnical_risk_land_settlement|Indicates if building has geotechnical risks related to land settlement|
|has_geotechnical_risk_landslide|Indicates if building has geotechnical risks related to landslide|
|has_geotechnical_risk_liquefaction|Indicates if building has geotechnical risks related to liquefaction|
|has_geotechnical_risk_other|Indicates if building has any other  geotechnical risks|
|has_geotechnical_risk_rock_fall|Indicates if building has geotechnical risks related to rock fall|
|has_repair_started|Indicates if the repair work had started|
|vdcmun_id|Municipality where the building is located|

#### test.csv

Contains the same variables as the train.csv except the 'damage_grade' which is the target variable/ varaible to be predicted.

#### Building_Ownership_Use.csv: 

|Varaible|Description|
|--------|-----------|
|building_id|A unique ID that identifies every individual building|
|district_id|District where the building is located|
|vdcmun_id|Municipality where the building is located|
|ward_id|Ward Number in which the building is located|
|legal_ownership_status|Legal ownership status of the land in which the building was built|
|count_families|Number of families in the building|
|has_secondary_use|indicates if the building is used for any secondary purpose|
|has_secondary_use_agriculture|indicates if the building is secondarily used for agricultural purpose|
|has_secondary_use_hotel|indicates if the building is secondarily used as hotel|
|has_secondary_use_rental|indicates if the building is secondarily used for rental purpose|
|has_secondary_use_institution|indicates if the building is secondarily used for institutional purpose|
|has_secondary_use_school|indicates if the building is secondarily used as school|
|has_secondary_use_industry|indicates if the building is secondarily used for industrial purpose|
|has_secondary_use_health_post|indicates if the building is secondarily used as health post|
|has_secondary_use_gov_office|indicates if the building is secondarily used as government office|
|has_secondary_use_use_police|indicates if the building is secondarily used as police station|
|has_secondary_use_other|indicates if the building is secondarily used for other purpose|


#### Building_Structure.csv

|Variable|Description|
|--------|-----------|
|building_id|A unique ID that identifies every individual building|
|district_id|District where the building is located|
|vdcmun_id|Municipality where the building is located|
|ward_id|Ward Number in which the building is located|
|count_floors_pre_eq|Number of floors that the building had before the earthquake|
|count_floors_post_eq|Number of floors that the building had after the earthquake|
|age_building|Age of the building (in years)|
|plinth_area_sq_ft|Plinth area of the building (in square feet)|
|height_ft_pre_eq|Height of the building before the earthquake (in feet)|
|height_ft_post_eq|Height of the building after the earthquake (in feet)|
|land_surface_condition|Surface condition of the land in which the building is built	|
|foundation_type|Type of foundation used in the building|
|roof_type|Type of roof used in the building|
|ground_floor_type|Ground floor type|
|other_floor_type|Type of construction used in other floors (except ground floor and roof)|
|position|Position of the building|
|plan_configuration|Building plan configuration|
|has_superstructure_adobe_mud|indicates if the superstructure of the building is made of Adobe/Mud|
|has_superstructure_mud_mortar_stone|indicates if the superstructure of the building is made of Mud Mortar - Stone|
|has_superstructure_stone_flag| indicates if the superstructure of the building is made of Stone|
|has_superstructure_mud_mortar_brick|indicates if the superstructure of the building is made of Cement Mortar - Stone|
|has_superstructure_cement_mortar_brick|indicates if the superstructure of the building is made of Mud Mortar - Brick|
|has_superstructure_timber|indicates if the superstructure of the building is made of Timber|
|has_superstructure_bamboo|indicates if the superstructure of the building is made of Bamboo|
|has_superstructure_rc_non_engineered|indicates if the superstructure of the building is made of RC (Non Engineered)|
|has_superstructure_rc_engineered|indicates if the superstructure of the building is made of RC (Engineered)|
|has_superstructure_other| indicates if the superstructure of the building is made of any other material|
|condition_post_eq|Actual contition of the building after the earthquake|

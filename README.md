# EV-Battery-Analysis
Analyzing Factors or Features strongly related to Battery Characteristics of a EV. Helpful in studying the health or life of the Battery of the EV. <br><br> Lizmotors Mobility assessment
<hr>

## Analysing Battery Health or Battery life of a EV

<b>Problem Statement:</b> What are the Features or Factors that are affecting the life or health of the Battery ?

<b>Tasks to be Done</b>
```
1) Extracting Significant Feautres based on Correlation. Metric: Feature that has correlation >= 70% with atleast 1 another feature in the dataset
2) Need to Study how Location_and_Movement, TIre_Info and External Factors affects Battery_Characterstics using Correlation
3) Need to Study how Location_and_Movement, TIre_Info and External Factors affects Battery_Characterstics Overtime using Time_information
```
<b>Analysing the Date and Time given in the Data</b><br>
 - <b>Start Date:</b> 2022-05-23<br>
 - <b> End Date:</b> 2023-08-01<br>
 - <b> Range (in days):</b> 434

<hr>

### Result of Analysis
Findings from EDA 2 - Point 1 - Both Heatmaps
```
1) The Outdoor temperature has a robust and direct impact on the battery's temperature. As the outdoor temperature rises, it leads to an elevation in the heating, minimum, maximum, and five other crucial temperatures that significantly influence the overall health and lifespan of the battery.

2) The Indoor temperature has a moderate yet positive impact on the battery's temperature. As the Indoor temperature rises, it contributes to a corresponding rise in the battery's temperature, albeit to a lesser extent compared to the direct influence of outdoor temperature

3) The overall temperature of the tires has a moderate yet positive correlation with the battery temperature. An increase in tire temperature contributes to a corresponding rise in the battery's temperature, albeit to a lesser extent compared to the direct influence of outdoor temperature

4) The overall Pressure of the tires has a low yet positive correlation with the battery temperature. An increase in tire pressure contributes to a corresponding rise in the battery's temperature, albeit to a lesser extent compared to the direct influence of Tire Temperature.

5) The overall Location and Movement metrics like Altitude, DistanceAccuracy, and Distance Trip has a moderate yet positive correlation with the battery temperature. An increase these values contributes to a corresponding rise in the battery's temperature, albeit to a lesser extent compared to the direct influence of outdoor temperature.

6) Location and Movements measures like Altitude, DistanceAccruacy, DistanceTotal and DistanceTrip has a robust and direct impact on the Cumulative charge current, cumulative discharge current, cumulative energy charged and cumulative energy discharge
```
<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gaurav-Van/EV-Battery-Analysis/assets/50765800/29c2b763-5dad-45c2-a14c-33d5965dc6c2" alt="Image 1" width="46%">
    <img src="https://github.com/Gaurav-Van/EV-Battery-Analysis/assets/50765800/8ec4d22b-1d72-49ca-8306-1d68b97984aa" alt="Image 2" width="48%">
</div>
<br>
Findings from EDA 2 - Point 2 - Data Over Time<br><br>

```
A) The relationship between OutdoorTemperature and Battery Temperature is further proven by the Line plot over time. During cold temperatures the Battery temperatures decreases so does the outside temperature and in hot temperature they both increase

B) Similarly the moderate and positive relation between IndoorTemperature and Battery Temperature is proven
```

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gaurav-Van/EV-Battery-Analysis/assets/50765800/622401f3-e666-4492-b869-5707a62315e9pg" alt="Image 1" width="48%">
    <img src="https://github.com/Gaurav-Van/EV-Battery-Analysis/assets/50765800/34599544-1de9-419a-a91c-c5529ef2eae0" alt="Image 2" width="48%">
</div>

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gaurav-Van/EV-Battery-Analysis/assets/50765800/880f821a-e1c3-4eee-9902-bac7c42287c3" alt="Image 1" width="48%">
    <img src="https://github.com/Gaurav-Van/EV-Battery-Analysis/assets/50765800/3b50fde9-6e2b-48bc-a9d4-8d6be7804729" alt="Image 2" width="48%">
</div>

<hr>

### Overall Result

The analysis aims to identify the factors or features that affect the battery health or life of an electric vehicle (EV). The analysis uses correlation and time series plots to examine the relationship between the battery characteristics and the environmental and operational variables. The main findings are:
```
- The outdoor temperature has a substantial and direct impact on the battery's temperature. As the outdoor temperature escalates, it induces an increase in the heating, minimum, maximum, and five other critical temperatures that profoundly affect the overall health and lifespan of the battery. Therefore, it is recommended to avoid exposing the EV to extreme outdoor temperatures and to use appropriate cooling or heating systems to regulate the battery's temperature.

- The indoor temperature also affects the battery's temperature but to a lesser degree than the outdoor temperature. An increase in indoor temperature results in a corresponding rise in the battery's temperature. Therefore, it is suggested to maintain a moderate indoor temperature and to avoid parking the EV in enclosed spaces with poor ventilation.

- The tire temperature and pressure have moderate and low positive correlations with the battery temperature, respectively. An increase in tire temperature or pressure contributes to a slight rise in the battery's temperature. Therefore, it is advised to check the tire condition regularly and to ensure that they are properly inflated and aligned.

- The location and movement metrics such as altitude, distance accuracy, and trip distance have moderate positive correlations with the battery temperature and the cumulative charge and discharge currents and energies. An increase in these values contributes to a corresponding rise in the battery's temperature and the energy consumption and production of the battery. Therefore, it is recommended to plan the route and the driving style carefully and to avoid unnecessary or excessive acceleration, braking, or idling.
```
In conclusion, the health of an EV's battery is strongly influenced by both its internal and external environments. While outdoor temperature is the most significant factor affecting the battery's temperature, other factors such as tire temperature and pressure, as well as location and movement metrics, also play crucial roles. These factors influence the overall performance and lifespan of the battery. Understanding these relationships is key to optimizing battery health and extending the life of EV batteries. The analysis provides insights and suggestions on how to achieve this goal.



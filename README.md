<img width="1292" height="725" alt="Screenshot 2025-08-22 174705" src="https://github.com/user-attachments/assets/e4b78815-c257-44ed-927f-ee956625c7ed" />
<img width="1291" height="724" alt="Screenshot 2025-08-22 174849" src="https://github.com/user-attachments/assets/d17b5a35-7b92-4288-a344-810604837442" />
<img width="1291" height="726" alt="Screenshot 2025-08-22 174815" src="https://github.com/user-attachments/assets/784c2f82-3a1c-4bef-9542-fb13ed204de7" />
# Azul-Plus Made By WxChaser

WxChaser's Custom Azul as Seen on Youtube.

Whats Included.
Metro Forecast and Observation Map

Regional Observation Map

8 City Observations

Full Speed Radar and Weather Icons on Maps.


Steps to Get Azul Plus Working Correctly:

1. Adjust the MachineProductCfg file.

2. Fill in the 3 PrimaryLatitudeLongitude values.
   
   - These are required because metro and regional maps have their own latitude/longitude values.
  
   - Regional Map uses PrimaryLatitudeLongitude2
     
   - MetroMap Uses PrimaryLatitudeLongitude1.

4. Fill in all 8 NearbyLocation values.
   
   - These are used for local observations.

6. Update your MetromapCities.
   
   - Adjust them to match the new metro map zoom level.
     
   - This is for MetroMap

8. Update your MapCities.
   
   - This is for the regional maps.
   
10. Road Signs for MetroMap and Regional Observations Map
    
-Road Signs needs to be Moved manually to your locations coordinate on viz due to the Designdestinastion Plugin being turned off. 

-DesignDestination was Giving issues when using a map width less then about 200 miles or when a "city" is too close to another. 

- Roads and Borders Remain Working, Its just for the Road Signs. Sorry:/ but its easily fixable if it annoys you.

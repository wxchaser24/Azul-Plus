Whats Included.
Metro Forecast and Observation Map
Regional Observation Map
8 City Observations
Full Speed Radar and Weather Icons on Maps.
Azul Data Fixes


Steps to Get Azul Plus Working Correctly:

1. Adjust the MachineProductCfg file.

2. Fill in the 3 PrimaryLatitudeLongitude values.
   - These are required because metro and regional maps have their own latitude/longitude values.
   - Regional Map uses PrimaryLatitudeLongitude2
   - MetroMap Uses PrimaryLatitudeLongitude1.

3. Fill in all 8 NearbyLocation values.
   - These are used for local observations.

4. Update your MetromapCities.
   - Adjust them to match the new metro map zoom level.
   - This is for MetroMap

5. Update your MapCities.
   - This is for the regional maps.
   
6. Road Signs for MetroMap and Regional Observations Map
-Road Signs needs to be Moved manually to your locations coordinate on viz due to the Designdestinastion Plugin being turned off. 
-DesignDestination was Giving issues when using a map width less then about 200 miles or when a "city" is too close to another. 
- Roads and Borders Remain Working, Its just for the Road Signs. Sorry:/ but its easily fixable if it annoys you.
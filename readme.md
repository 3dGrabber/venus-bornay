```
Paths

DC:

/0/Current              Current in Amps. Value/10
/0/Power                Power in watts 
/0/Voltage              Voltage in volts. Value/10

Flags:

/ChargedBattery         0=No; 1=Yes If the battery is charged sets this flag
/FanState               0=Off; 1=On Status of the fan
/ElevatedVoltage        0=No; 1=Yes 
/ElevatedWind           0=No; 1=Yes 
/EmergencyButton        0=Off; 1=On Status of emergency button
/Extrem                 0=No; 1=Yes flag to elevated speed
/ExternSupply           0=No; 1=Yes Fail of extern supply

History:

/Overall/MaxRPM         Maximum revolutions reached in revolutions per minute

Mppt:

/AbsortionTime          Time in absorbtion in seconds
/BoxTemp                Temperature of the box in degrees /10
/ChargerState           0=standby; 1=charging; 2=charged.
/DuttyCycle             Dutty cycle 0 to 100%
/Phase                  Phase of Full-Bridge 0 to 100%
/RefMEF                 Bat Power Reference in watts
/SinkTemp               Temperature of sink in degrees /10
/StatusMEF              State of the states machine

Turbine:

/AvailablePower         Calculated available power in watts
/BatPowerLastHour       Calculated Batery Power charged last hour in watts.
/BatPowerLastMin        Calculated Batery Power charged last minute in watts.
/BreakerPowerLastMin    Calculated Braker Power derivated to resistors last minute in watts.
/EstimatedWind           Wind speed estimated value/10
/IBrk                   Current of the braker in Amps
/RPM                    Revolutions of the turbine in revolutions per minute
/Stop                   Wind Turbine Brake 0=Run; 1=Stop Writable value. 
/VDC                    Voltage of DC system in volts Value/10
/WindSpeed              Wind speed (m/s) Value /100 
/WindSpeedLastHour      Calculated Wind speed last hour in m/s
/WindSpeedLastMin       Calculated Wind speed last minute in m/s

Note: 
Paths to show in Color Control
/0/Current              
/0/Power                
/0/Voltage             
/RPM 
/WindSpeed   (if there are anemomemeter)

Paths to adjust.
/Stop                     Wind Turbine Brake 0=Run; 1=Stop Writable value. 
Anemometer                yes/not --> Only If yes then windspeed is showed in color control```

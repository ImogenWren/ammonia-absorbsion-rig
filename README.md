# ammonia-absorbsion-rig
 Labview interface for Mass Flow Meters


##TODO 
Recommitting to main, delete all other branches from here

## Usage Instructions
1. Select `setup` tab, ensure correct COM port & Channel for each device.

2. To start Data Aquisition press `Start` button

3. Select Setpoint for `MFC1` & `MFC2`

4. View Graphs in `graphs` tab

5. Pause and Unpause data aquisition with `pause` button

6. To export data to Excel, right click on topmost graph view 
     and select:
     - `Export` -> `Export  Data to Excel`
     - Name & Save Excel file
        _(Note: All data will be exported not just "active" plots)_


7. To Clear sensor history press `Stop` button
     - While stopped, setup controls are available

8. To Exit program, click `Exit` Button

9. If Error shows, attempt to remedy error then press
     `clear error` button. Program will revert to Setup


## UI - Tab Based
### Run Tab
![image](https://github.com/ImogenWren/ammonia-absorbsion-rig/assets/97303986/c6ff0260-6c46-4e6a-867e-27e8612076a5)


### Graphs Tab
![image](https://github.com/ImogenWren/ammonia-absorbsion-rig/assets/97303986/fefd2ad3-b469-4655-a722-2c1701582340)

### Setup Tab
![image](https://github.com/ImogenWren/ammonia-absorbsion-rig/assets/97303986/d46a686d-d506-442f-9fd5-52f768849089)


### Errors Tab
![image](https://github.com/ImogenWren/ammonia-absorbsion-rig/assets/97303986/a55a44d4-42e9-4af6-9db5-cd13f8112070)



 
## Requirements

### Hardware 
 - Control Flow with 2x MFC (Mass Flow Controllers)
 - Read Flow value from 2x MFM (Mass Flow Meters)
 - read value from K-type thermocouple

### Software
- Graph all 5 output values
	- Timebase of entire experiment
- Output data to a CSV file
- Provide ability to name CSV output file

 

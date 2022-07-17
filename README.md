# Design of Bandgap Reference (BGR)
- Cadence GPDK 90 nm technology is used and designed in Cadence Virtuoso.

<br /><br />

## BGR with Current Mirror – 10 µA

- BGR has a PTAT slope of 1.703652mV / °C and a CTAT slope of -1.698179mV / °C.
- The reference output voltage of BGR is 1.179V at 2.5 VDD w.r.t temperature (-40 °C to 120 °C).
- The slope of the Reference output voltage of BGR w.r.t Supply voltage VDD is 83.71mV / V.
<br />

![BGR_1](https://user-images.githubusercontent.com/84563214/179386770-4e62ce1c-cbf4-4c62-b35a-7120d67a5229.png) 
![BGR_2](https://user-images.githubusercontent.com/84563214/179386905-8a483424-ab7e-48ed-8a8f-9159aed8512e.png)

### CTAT & PTAT
![BGR_3](https://user-images.githubusercontent.com/84563214/179386910-f570c2a5-fbd6-441d-84d8-ae945b707066.png)

### Reference voltage (Vref)
![BGR_4](https://user-images.githubusercontent.com/84563214/179386915-8829988a-5657-4d84-ab57-6867a43d0f26.png)
![BGR_5](https://user-images.githubusercontent.com/84563214/179386918-2d3bf751-fb26-4c9a-92ea-8bfe74ca13ab.png)

### Reference voltage vs Supply voltage
![BGR_6](https://user-images.githubusercontent.com/84563214/179386923-43e396f4-81ad-4245-91d4-e852ab6f2d9c.png)

<br /><br /><br /><br /><br />

## BGR with Cascode Current Mirror – 10 µA

- Cascode current mirror is used to obtain nearly the same voltage on either side. 
[ i.e., source voltage (Vs) of NM0 = 656.257mV, NM1 = 655.313mV (ΔV = 0.944mV), but in case of BGR without cascode current mirror the Vs of NM0 = 656.490mV, NM1 = 658.646mV (ΔV = 2.156mV). Therefore Cascoding reduces the ΔV ]
- BGR has a PTAT slope of 1.696381mV / °C and a CTAT slope of -1.696375mV / °C.
- The reference output voltage of BGR is 1.164V at 2.5 VDD (with a concave down curvature) w.r.t temperature (-40 °C to 120 °C).
- The slope of the Reference output voltage of BGR w.r.t Supply voltage VDD is 7.37mV / V. (reduction of slope by using cascode current mirror)
<br />

![BGR_7](https://user-images.githubusercontent.com/84563214/179386930-7ff014f5-af84-4e95-b96c-ee92d5372467.png)
![BGR_8](https://user-images.githubusercontent.com/84563214/179386931-55e33801-564e-4c94-a2f5-860ab8192d91.png)
![BGR_9](https://user-images.githubusercontent.com/84563214/179386932-2eeac238-9189-4100-8489-38373a39658e.png)
![BGR_10](https://user-images.githubusercontent.com/84563214/179386933-0dc34b77-ecf1-472b-8f5a-def5303a2c86.png)

### CTAT & PTAT
![BGR_11](https://user-images.githubusercontent.com/84563214/179386934-e95318e1-26bd-4dd8-8b8d-ed764b6c3765.png)

### Reference voltage (Vref)
![BGR_12](https://user-images.githubusercontent.com/84563214/179386937-805b5c50-9fc1-43e9-a56e-5e26151ec423.png)
![BGR_13](https://user-images.githubusercontent.com/84563214/179386941-1d064f51-03ac-4757-8ff3-549d29c13ab0.png)

### Reference voltage vs Supply voltage
![BGR_14](https://user-images.githubusercontent.com/84563214/179386947-75a6b2c8-f37c-4869-bcef-721163ade2d5.png)

<br /><br /><br /><br /><br />

## Comparison : Reference voltage (Cascode Current Mirror) & Reference voltage (Current Mirror) w.r.t Supply voltage 
![BGR_15](https://user-images.githubusercontent.com/84563214/179386950-7eebba55-ad0c-46d5-8ea8-9938a84b60cf.png)


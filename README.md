# Design of Bandgap Reference (BGR)
- Cadence GPDK 90 nm technology is used and designed in Cadence Virtuoso.
- Cascode current mirror is used to obtain nearly the same voltage on either side. 
- BGR has a PTAT slope of 1.696381mV / °C and a CTAT slope of 1.696375mV / °C.
- The reference output voltage of BGR is 1.164V at 2.5 VDD with a concave down curvature in w.r.t temperature (-40 °C to 120 °C).
- The slope of the Reference output voltage of BGR w.r.t Supply voltage VDD is 7.37mV / V.

## BGR with Current Mirror – 10 µA
![image](https://user-images.githubusercontent.com/84563214/179386342-b4f4abd3-a984-467a-a091-fc939672950b.png)
![image](https://user-images.githubusercontent.com/84563214/179386346-8e6d0dac-0a83-4ab9-b9a4-ea3d1b69562d.png)

### CTAT & PTAT
![image](https://user-images.githubusercontent.com/84563214/179386356-dcb38904-ef08-4ad7-b972-870d13522e04.png)

### Reference voltage (Vref)
![image](https://user-images.githubusercontent.com/84563214/179386366-5794cb09-e5df-4a80-b6a0-81833a7e2e8f.png)
![image](https://user-images.githubusercontent.com/84563214/179386380-d62cb9d2-9d3f-433e-bdbd-2517d87bb26e.png)

### Reference voltage vs Supply voltage
![image](https://user-images.githubusercontent.com/84563214/179386386-0c19c9d5-742d-49d6-bcbb-0cf833cda931.png)

## BGR with Cascode Current Mirror – 10 µA
![image](https://user-images.githubusercontent.com/84563214/179386393-817b40fe-89b2-4922-935a-806919d68d46.png)
![image](https://user-images.githubusercontent.com/84563214/179386408-b4a52865-7909-4b1d-9a20-51ad6c6576e4.png)
![image](https://user-images.githubusercontent.com/84563214/179386411-a5aae016-7474-4e69-ac1c-5221cca37de0.png)
![image](https://user-images.githubusercontent.com/84563214/179386413-3ad2da12-5a72-4b41-b6b5-e42943443566.png)

### CTAT & PTAT
![image](https://user-images.githubusercontent.com/84563214/179386419-a68a77f7-4565-459d-83e1-10e26bf2bb35.png)

### Reference voltage (Vref)
![image](https://user-images.githubusercontent.com/84563214/179386423-8d494337-69fe-4bd6-8eab-42faa8c26274.png)
![image](https://user-images.githubusercontent.com/84563214/179386430-9ac8aca6-186a-41e7-8fcb-d168cacf2dac.png)

### Reference voltage vs Supply voltage
![image](https://user-images.githubusercontent.com/84563214/179386434-cc4b2871-3228-49eb-91f4-91efb61c080a.png)

## Comparison : Reference voltage (Cascode Current Mirror) & Reference voltage (Current Mirror) w.r.t Supply voltage 
![image](https://user-images.githubusercontent.com/84563214/179386439-da67df68-26d7-4eb6-8f71-23a3324e0533.png)

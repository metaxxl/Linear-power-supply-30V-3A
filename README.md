# Linear-power-supply-12-3A
Regulated lab power supply 0-12, 0-3A 

I used 2x 12V AC transformer 120W.
Negative voltage has been used to ensure the regulation goes all the way to 0V and 0A.

To maintain a constant output voltage, 
a feedback signal after the shunt is phase inverted and adjusted to
compensate the voltage drop across the shunt resistor

Highly precise OPA2187 has been used to ensure precise regulation.
Precision:

-Voltage regulation 0-12V DC (5mV)

-Current regulation 0-3A (1mA)

The regulator takes 70ms to stabilise the voltage.

Voltage regulation under no load:
<img width="2256" height="1504" alt="image" src="https://github.com/user-attachments/assets/2d10502a-20df-4a2c-93d0-efd993c90cce" />

Voltage regulation under load:
<img width="2256" height="1504" alt="image" src="https://github.com/user-attachments/assets/5a12f359-ef98-4a9b-9033-45e4b5ca1d9b" />

Voltage regulation under pulse load 0-3A:
<img width="2256" height="1504" alt="image" src="https://github.com/user-attachments/assets/6b1e1443-019c-4ce5-bc62-0bd1b4318023" />

Short ciruit reaction time 70us:
<img width="2256" height="1504" alt="image" src="https://github.com/user-attachments/assets/890843f3-cc00-4ed7-81e7-8ca34388773a" />

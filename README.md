# Sensitive-Intruder-alarm
We designed this intruder alarm system to be simple and 
easy to use there is a trip wire that is connected to a 555 
timer which is also connected to a voltage source. When 
the wire trips or if someone steps on the wire the circuit 
gets open which generates interrupt signal to 555 timer, 
which then generates an analog signal a buzzer and a 
LED, this is a brief explanation of how this model works. 
![image](https://github.com/2110040010/Sensitive-Intruder-alarm/assets/110652930/f292e383-0c4d-40df-9159-0c3ded769378)


![image](https://github.com/2110040010/Sensitive-Intruder-alarm/assets/110652930/2550c64c-4600-41f9-9ce3-d4492b974b66)



Intruder alarms are popular devices used in high-security areas as well as 
civilian houses to detect and alarm the presence of any intruders. There 
are different kinds of intruder detection alarms, some detect movements 
by using a laser, some use pressure variations etc. The circuit diagram of 
Super Sensitive Intruder alarm, detects an intruder passing nearby the 
circuit is enough to trigger the alarm. In this circuit 555 time is in 
Astable mode. The pin 4 of IC is an Active low reset pin. This means 
when low signal is applied to it the output will be inactive. When reset 
pin is connected to logic 1 the output will become active. The rest pin is 
connected to ground using the thin strand of copper wire which will be a 
trip wire. When trip wire is inactive the reset pin will be in low state. 
Therefore, the alarm does not receive any signal. If an intruder enters the 
house breaks the trip wire which actives the reset pin to high, then an 
interrupt signal triggers the alarm and makes the user alert.

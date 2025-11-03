## HC-05-BLUETOOTH-MODULE

# Test in Serial Monitor: 
A few commands:
+ AT
+ AT+NAME?
+ AT+ADDR?
+ AT+UART?
+ AT+VERSION?

# Wiring:
+ HC-05 VCC → Arduino 3.3V” (5V didnt work for me)
+ HC-05 GND → Arduino GND”
+ HC-05 TXD → Arduino Pin 10 
+ HC-05 RXD → Arduino Pin 11 
+ HC-05 KEY → Arduino Pin 9 (for AT mode)

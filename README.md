# UART_PIC16F877A
UART Communication with two different pic considering master and slave
This project holds the communication protocol uart in which two same pic16f877a microcontroller is implemented for master and slave with the two pins for transfer of data from master to slave in real time simulation
Primarily Push buttons are connected with master in PORTB register and two different leds are connected in PORTD registers 
Secondarily lcd is connected with PORTD Register in second microcontroller (SLAVE) 
The condition is that when push buttons are pressed led should blink in alternative way and then it should be bits accordingly to the slav from TX pin and slave should recieve it from RX pin and displays the value  provided from the master accordingly as from A to B char simultaneoulsy from both the microcontroller so that both pic transmits and receives the datas

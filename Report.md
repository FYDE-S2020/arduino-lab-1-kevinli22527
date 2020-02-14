Name: Kevin Li	

EID: kal3552

Team Number: 10

## Questions

1. Why does your program need a setup and a loop?

    Set up defines which ports do what. The loop makes code run continuously to handle real time.

2. What is the downside to putting all your code in a loop?

    Bad latency and sometimes difficult to read.

3. Why does your code need to be compiled?

    It needs to be translated into machine code that the board can understand.

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    The frequency is too low and the human eye can see the obvious on and off state. The solution is to drastically increase the frequency such that the human eye cannot discern.

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    The logic analyzer needs to know a point of reference to compare to.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous requires a clock to operate.

7. Profile of UART: Sent X bytes in Y time 

    3 bytes/0.247 milliseconds to send

8. Profile of SPI: Sent X bytes in Y time

    6 bytes/0.15 milliseconds to send

9. Why is SPI so much faster than UART?

    SPI is syncronous and simple

10. list one pro and one con of UART

    Only requires 2 pins. Slower speed.

11. list one pro and one con of SPI

    Fast speed and simple. Uses many more pins.

12. list one pro and one con of I2C

    It only requires 2 pins. It is extremely sensitive to interference.

13. Why does I2C need external resistors to work?

    The lines are open drain and may short out.

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](img/FYDE1.png)

Procedure A, step 4:
![Put path to your image here ->](img/Uhoh.png)

Procedure B, UART:
![Put path to your image here ->](img/UART.png)

Procedure B, SPI:
![Put path to your image here ->](img/spi.png)

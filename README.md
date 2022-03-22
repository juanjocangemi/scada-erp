# SCADA System applied to an Industrial Process of Concentration

In this project, I designed a SCADA (Supervisory Control and Data Acquisition) for an Industrial Process of Juice Concentration. 

The system has 5 main windows, which are:

- Main Window or Industrial Process Window.
- Window of Setup of Production.
- Window of Data Adquisition.
- Window of Log Alarms.
- Window of Temperature Monitoring.


# Main Window or Industrial Process Window

[![1.png](https://i.postimg.cc/ZnM2WJbv/1.png)](https://postimg.cc/SYcD5Fzm)

Refs.
1. Indicator of Process ON of Process OFF.
2. Quantity of product and number of batch in the deposit.
3. Indicator of current production setup (Size batch and concentration)
4. Input juice concentration
5. Information window
6. Indicators of alerts and alarms.
7. Navigation buttoms
8. Emergency Stop Button and Continue Production Button.
9. Selection of serial port communication and disconect buttom.


# Window of Setup of Production

[![2.png](https://i.postimg.cc/CMPWPsGM/2.png)](https://postimg.cc/4ncLnt2j)

Refs.
1. Setup of input tank and concentration
2. Setup of output: batch size and concentration
3. Indicator of input setup
4. Indicator of output product (batch size and concentration)
5. Indicator of setups reception by the system


# Windows of Data Adquisition
In this windows, we can see all the information that the system adquire and save in a external database.

[![3.png](https://i.postimg.cc/MKnghf57/3.png)](https://postimg.cc/6yNHZ3Dq)


# Window of Log Alarms

In this windows, the system registry all the main events previously set like "Insufficient input", "Stop of the process", etc:

[![4.png](https://i.postimg.cc/xTBBYjpW/4.png)](https://postimg.cc/dLm5jFYB)


# Window of Temperature Monitoring

Additionally, the system can monitor and display an external relevant parameter, like temperature. It's possible to set an alarm if the temperature goes out of a specific range.

[![5.png](https://i.postimg.cc/pdfwsNZ3/5.png)](https://postimg.cc/DWzpzMRc)


# Flowsheet of the Process and equation of the models.
To test the system, I coded the process into a microcontroller to simulate signals of input/output. The model and the equations (balance of mass) to get these signals were the following: 

[![6.png](https://i.postimg.cc/Y09T2vHw/6.png)](https://postimg.cc/DJ9xBy0C)

[![a.png](https://i.postimg.cc/7Lx7TwJ6/a.png)](https://postimg.cc/w1G3CKV8)

[![8.png](https://i.postimg.cc/wvFSdhnV/8.png)](https://postimg.cc/344LXD84)

[![9.png](https://i.postimg.cc/rmqvbhZs/9.png)](https://postimg.cc/cK59tcSG)

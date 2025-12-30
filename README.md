📌 Project Description

The GSM Based Temperature Monitoring and Alert System Using LPC2148 is an embedded system designed to continuously monitor temperature in real time and provide alerts when the temperature exceeds a predefined threshold value. The system uses a temperature sensor interfaced with the LPC2148 microcontroller to measure temperature and display it on an LCD.

When the temperature crosses the set limit, the system sends an SMS alert to a predefined mobile number using a GSM module. This helps in taking immediate action to prevent damage or unsafe conditions.

🎯 Objectives

To monitor temperature continuously in real time

To display temperature on an LCD

To send SMS alerts when temperature exceeds the threshold

To ensure safety and prevent overheating conditions

🧩 System Components
Hardware Requirements

LPC2148 Microcontroller

Temperature Sensor (LM35 / similar)

GSM Module (SIM800 / SIM900)

16x2 LCD Display

Buzzer / LED (Alert indication)

Power Supply

Connecting Wires

Software Requirements

Keil µVision IDE

Embedded C

Flash Magic (for programming LPC2148)

Proteus (optional for simulation)

⚙️ Working Principle

The temperature sensor continuously senses the surrounding temperature and sends analog data to the LPC2148 microcontroller. The microcontroller converts this data into digital form using its internal ADC. The current temperature is displayed on the LCD.

If the measured temperature exceeds the predefined threshold value, the microcontroller activates an alert mechanism. A buzzer or LED is turned ON, and an SMS alert is sent to the user through the GSM module. This ensures timely notification and quick response.

🔁 Block Diagram (Textual)

Temperature Sensor → LPC2148 (ADC) → LCD Display
                  → GSM Module (SMS Alert)
                  → Buzzer / LED

📂 Project Folder Structure
GSM-Temp-Monitoring-System/
│
├── src/            # Source code files (.c)
├── inc/            # Header files (.h)
├── hex/            # Generated HEX files
├── doc/            # Project report & documentation
├── proteus/        # Simulation files (if any)
├── README.md

🚀 Applications

Industrial temperature monitoring

Server room monitoring

Cold storage and warehouses

Laboratories

Home and office safety systems

✅ Advantages

Real-time monitoring

Remote alert through SMS

Reliable and cost-effective

Easy to implement and maintaing

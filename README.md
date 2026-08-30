# 💊 Smart Pill Dispenser

An Arduino-based Smart Pill Dispenser designed to automatically dispense tablets at scheduled times and notify the user through GSM.

## 🚀 Features

- ⏰ Scheduled medicine reminders
- 📅 DS3231 Real-Time Clock
- 📱 Bluetooth alarm configuration
- 🔄 Automatic servo-based tablet dispensing
- 🔊 Buzzer alert
- 💡 LED indication
- 👁️ IR sensor to detect whether the tablet was taken
- 📲 GSM SMS notifications
- 🔄 Automatic slot management

## 🛠️ Hardware

- Arduino Uno R3
- DS3231 RTC Module
- 16×2 LCD Display
- 10K Potentiometer
- HC-05 Bluetooth Module
- SIM800L / SIM900 GSM Module
- SG90 Servo Motor
- IR Sensor Module
- 5V Buzzer
- LED
- 220Ω Resistor
- Breadboard
- Jumper Wires
- 7–12V DC Power Supply
- 5V/2A Power Supply for GSM
- 5V Voltage Regulator / Buck Converter
- SIM Card
- Pill/Tablet Container

## 📌 Pin Configuration

| Component | Arduino Pin |
|---|---|
| LCD RS | D13 |
| LCD E | D12 |
| LCD D4 | D11 |
| LCD D5 | D10 |
| LCD D6 | D9 |
| LCD D7 | D8 |
| Servo | D7 |
| IR Sensor | D6 |
| Buzzer | D5 |
| LED | D4 |
| HC-05 RX/TX | D2/D3 |
| DS3231 SDA | A4 |
| DS3231 SCL | A5 |
| GSM | D0/D1 |

## 📱 Bluetooth Format

Send multiple medicine times using:

`12:20,13:30,20:30,21:30`

The system supports up to 5 scheduled alarms.

## 📲 SMS Notifications

The GSM module can send:

- Tablet Dispatched
- Tablet Taken
- Tablet Not Taken
- Refill the Dispenser

## 🔧 Working

1. User sets medicine times through Bluetooth.
2. DS3231 keeps track of the current time.
3. When the scheduled time arrives, the servo moves to the required slot.
4. Buzzer and LED provide an alert.
5. IR sensor checks whether the tablet was taken.
6. GSM sends the corresponding SMS notification.

## 📷 Project

Add your project photos and connection diagram here.

## 👨‍💻 Author

mugesh m

## 📄 License

This project is for educational and prototype purposes.

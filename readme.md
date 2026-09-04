# 💡 Basic LED Blink

A basic Arduino project that demonstrates how to **turn an LED ON and OFF at regular intervals** using an Arduino.

This is one of the simplest projects for getting started with Arduino and understanding **digital output**.

---

## 🛠️ Components Required

* Arduino UNO
* LED
* 220Ω resistor
* Breadboard
* Jumper wires

---

## 🔌 Circuit

| LED Component   | Arduino                      |
| --------------- | ---------------------------- |
| LED Anode (+)   | Digital Pin 7                |
| LED Cathode (-) | GND                          |
| Resistor        | Connected in series with LED |

> ⚠️ Always use a resistor with an LED to limit the current.

---

## 💻 Code

The Arduino program:

1. Sets **digital pin 7** as an output.
2. Turns the LED **ON**.
3. Waits for **5 seconds**.
4. Turns the LED **OFF**.
5. Waits for **5 seconds**.
6. Repeats continuously.

---

## 🎯 Concepts Learned

* `pinMode()`
* `digitalWrite()`
* `delay()`
* Digital OUTPUT
* Basic Arduino programming
* LED control

---

## 🚀 How It Works

**Arduino Pin 7**
↓
**LED ON**
↓
**Wait 5 seconds**
↓
**LED OFF**
↓
**Wait 5 seconds**
↓
**Repeat**

> 💡 Any suitable digital pin can be used instead of Pin 7 by changing the pin number in the code.

---

## 📌 Note

This project is intended as a **beginner-level Arduino experiment** to understand how Arduino controls digital outputs.

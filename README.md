# Digital Clock

Owner: Adit Mugdha Das

A digital clock implemented in Logisim, capable of displaying time in a digital HH:MM format using seven-segment displays. This project demonstrates the use of counters, decoders, logic gates, and a clock generator to simulate a real-time clock.

✨ Features

🕒 Four-Digit Display: Displays time in HH:MM format.

⏰ Clock Signal: Provides a stable timing source for the circuit.

🔢 Counters:

🕑 Minutes Counter: Counts up to 59 minutes before resetting.

🕓 Hours Counter: Operates in either a 12-hour or 24-hour mode (configurable).

🔄 Seven-Segment Display Decoding: Converts binary counter outputs to a human-readable digital format.

🔁 Reset Functionality: Ensures the clock can be reset to its initial state.

🛠️ Components Used

⏳ Clock Generator

Generates pulses to drive the counters.

🧮 Counters

Modular counters for minutes and hours.

Carry-out signals ensure proper cascading between counters.

🗺️ Decoders

Convert binary values from counters to drive the seven-segment displays.

🔢 Seven-Segment Displays

Used to visually represent digits for time.

⚙️ Logic Gates

Handle carry-over, resets, and control logic.

🔐 Flip-Flops

Provide synchronization and state management for the clock.

🧭 How It Works

⏳ Clock Signal:

The clock generator produces pulses that increment the minutes counter.

🕑 Minutes Counter:

Counts from 0 to 59 and resets. Upon reaching 59, a carry-out signal is sent to the hours counter.

🕓 Hours Counter:

Operates in either a 12-hour or 24-hour mode, resetting at the appropriate value.

🔢 Display:

The binary outputs of the counters are decoded and displayed on the seven-segment displays in a HH:MM format.

🌟 Possible Enhancements

🕰️ AM/PM Indicator: Add a toggle for distinguishing between morning and evening in 12-hour format.

⏲️ Alarm Functionality: Enable alarm settings with additional logic.

🎛️ User Input: Add buttons to adjust hours and minutes manually.

📟 LCD Integration: Replace seven-segment displays with a modern LCD display for enhanced aesthetics.

🚀 Usage

Open the .circ file in Logisim.

Simulate the circuit by starting the clock.

Observe the time updating in real-time on the digital displays.

📂 File Details

📁 Circuit File: Digital Clock.circ

Contains the complete Logisim project for the digital clock.

📜 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the license terms.

Feel free to contribute to this project by creating pull requests or reporting issues! 🚀

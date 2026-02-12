🚁 Drone Telemetry Monitor

A creative and interactive Drone Telemetry Dashboard built using HTML, CSS, and JavaScript.
This project simulates real-time drone telemetry data including altitude, speed, battery percentage, GPS coordinates, and system status.

📌 Project Overview

This project was developed as part of a software internship task to create a simulated drone telemetry interface where:

Telemetry values update every 1 second

The simulation runs for 30 seconds

The interface looks modern and visually engaging

Data is displayed in a clear and structured format

The UI is inspired by real mission control dashboards and ground station telemetry systems.

🛠️ What I Built

I created a one-page telemetry dashboard that includes:

⏱️ Mission Timer with progress bar

📊 Circular animated gauges for:

Altitude

Speed

Battery

Distance

📍 Live GPS Coordinates section

⚡ System Status (Voltage, Current, Temperature, Flight Mode)

✈️ Flight Data (Heading, Pitch, Roll, Vertical Speed)

🟢 System Active indicator

Mission completion screen after 30 seconds

The telemetry values change dynamically every second using JavaScript.

⚙️ How It Works

JavaScript setInterval() updates telemetry values every 1000ms.

Randomized but realistic drone values are generated within safe limits.

Circular progress gauges update using CSS conic gradients.

Mission timer counts down from 30 seconds.

After 30 seconds:

The mission status changes to COMPLETE

Final telemetry values remain displayed

All calculations and animations are handled on the frontend.

💻 Tools & Technologies Used

HTML5 – Structure

CSS3 – Styling, layout, gradients

JavaScript – Telemetry simulation logic

No external libraries used

Output:
<img width="1901" height="923" alt="output1" src="https://github.com/user-attachments/assets/2d029a9c-986e-41db-addb-5d5375d39d18" />
<img width="1874" height="906" alt="output2" src="https://github.com/user-attachments/assets/ddb7f159-2641-491f-b957-378625063163" />

📂 Project Structure
drone-telemetry-monitor/
│── index.html
│── style.css
│── script.js
│── README.md
│── outputduringmission.png
│── outputaftermission.png


🚀 Features

Real-time simulation updates

Mission timer with completion state

Fully responsive layout

Simple and lightweight implementation

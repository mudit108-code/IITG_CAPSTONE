🚗 Dynamic Pricing for Urban Parking Lots

A real-time, intelligent pricing engine for urban parking lots using Python, Pathway and Bokeh.
The model dynamically adjusts parking prices based on live demand signals including occupancy, queue length, traffic conditions and special events—delivering smooth, explainable pricing decisions in real-time.

📌 Overview
This project addresses the challenges of static parking pricing in dynamic urban environments. By simulating live parking lot data, we implement a multi-stage pricing system and visualize price evolution using Bokeh for transparency and policy optimization.

🧠 Key Features
Real-Time Data Simulation using Pathway
Live Bokeh Plot: Interactive visualization of parking price evolution

🚀 Real-Time Pricing Logic
The price is computed based on:

Occupancy Rate
Traffic Conditions Nearby
Vehicle Type (2W/4W)
Queue Length
Special Day Flag
Competitor Pricing Reference
Price Smoothing Constraints:

🧮 Three Pricing Models:
Baseline Linear Model: Adjusts prices based on occupancy
Demand-Based Model: Incorporates queue length, vehicle type, traffic, and special events
Advanced Real-Time Model: Powered by Pathway with bounded price constraints

📊 Final Output Table: Tabulated pricing summary

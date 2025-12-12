# Servo-Load-Calculator
Calculates servo torque required for a control surface based on a number of parameters.
📘 Servo Load Calculator

A comprehensive web-based tool to calculate required servo torque for RC aircraft control surfaces.

✈️ Overview

This project provides a fully interactive servo torque calculator for radio-controlled aircraft.
It computes hinge moments, aerodynamic loads, linkage geometry effects, and final servo torque requirements in both metric and imperial units.

The calculator supports direct airspeed, prop-derived speed, air density modeling, surface geometry, and even analog vs digital servo behavior.
It is designed for builders, designers, and hobbyists who want realistic torque estimates before choosing servos.

The live version is hosted using GitHub Pages:

👉 https://dizzydee3000-spec.github.io/Servo-Load-Calculator/

⭐ Features
Aerodynamic Calculations

Hinge moment calculation using dynamic pressure

Airspeed from:

Direct entry (m/s, km/h, mph)

Prop pitch + RPM + prop efficiency

Air density from:

Direct ρ entry

Automatic calculation based on altitude + temperature

Built-in city → altitude lookup (editable table)

Control Surface Geometry Modes

Supports three geometry types:

Direct area + chord

Rectangular (span × chord)

Tapered (trapezoid) with automatic MAC (Mean Aerodynamic Chord)

Each mode converts units automatically:

meters / centimeters / millimeters / inches

m² / cm² / mm² / in²

Servo & Linkage Modeling

Servo arm length

Control horn length

Center-of-pressure fraction (0–1)

Safety factor multiplier

Analog vs Digital servo compensation

Digital: full rated torque

Analog: automatically increases required torque (default +25%)

Multiple Surface Profiles

Presets included for:

Aileron

Elevator

Rudder

Each preset configures default sizes, linkage geometry, and safety factors.

Import / Export Configurations

You can:

Click Export → JSON copied to a text box

Click Import → restore exact calculator state

Useful for:

Saving multiple surfaces (L/R aileron, elevator halves)

Sharing configs between builders

Storing project profiles

Full Metric + Imperial Outputs

Calculates and displays:

Hinge moment (N·m, kg·cm, oz·in)

Required servo torque (N·m, kg·cm, oz·in, lb·in, lb·ft)

📸 Screenshots (optional – replace with real images later)

You can upload screenshots and then update the README like this:

![Screenshot](images/screenshot-main.png)

🚀 How to Use

Open the live calculator:
https://dizzydee3000-spec.github.io/Servo-Load-Calculator/

Choose your control surface tab (Aileron / Elevator / Rudder)

Enter aircraft speed:

Direct airspeed

or prop-based estimation

Select air density mode:

Enter ρ manually

or calculate from altitude & temperature

or type a city and click “Lookup altitude”

Choose a surface geometry method

Area + chord

Rectangular

Tapered (root & tip chords)

Enter linkage geometry (servo arm & horn arm)

Select servo type:

Digital

Analog (+25% torque margin)

Click Calculate Required Servo Torque

That's it — results instantly appear with unit conversions included.

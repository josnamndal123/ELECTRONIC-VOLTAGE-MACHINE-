- **Name:** `JOSNA MANDAL`  
- **Company:** `CODTECH IT SOLUTIONS`  
- **ID:** `CITS2604`  
- **Domain:** `EMBEDED SYSTEMS`  
- **Internship Duration:**  `June 12, 2026` – `July 10, 2026`
- 
## Project Title

Electronic Voting Machine (EVM) Using Arduino Uno

## Objective

To design and implement an Electronic Voting Machine using Arduino that allows users to cast votes for different candidates and displays the vote count on an LCD screen.

## Components Required

- Arduino Uno
- 16×2 LCD Display
- 3 Push Buttons
- Breadboard
- Jumper Wires
- 10k Potentiometer
- USB Cable
  
## Circuit Connections
  
- LCD to Arduino
- RS → Pin 7
- EN → Pin 6
- D4 → Pin 5
- D5 → Pin 4
- D6 → Pin 3
- D7 → Pin 2
- 
#include <LiquidCrystal.h>

LiquidCrystal lcd(7,6,5,4,3,2);

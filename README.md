# 🌍 Environmental Impact Tracker

A comprehensive Python command-line application for tracking daily environmental impact, focusing on carbon footprint and water usage monitoring.

---

## 📋 Table of Contents

- [Project Information](#project-information)
- [Features](#features)
- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [System Requirements](#system-requirements)
- [File Structure](#file-structure)
- [Contributors](#contributors)
- [License](#license)

---

## 📝 Project Information

| *Field* | *Details* |
|-----------|-------------|
| *Project Name* | Environmental Impact Tracker |
| *Author* | ISHANI VERMA |
| *Registration Number* | 25BOE10013 |
| *Course* | Fundamental of AI ML |
| *Instructor* | Dr. Vivek Parashar |
| *Institution* | Vellore Institute of Technology, Bhopal |
| *Academic Year* | 2025 |
| *Programming Language* | Python 3.x |

---

## ✨ Features

### 🎯 Core Functionality

1. *Multi-Activity Tracking*
   - 🚗 *Transportation*: Car, Bus, Train, Bike, Walk
   - ⚡ *Electricity*: Power consumption in kWh
   - 💧 *Water*: Usage tracking in litres
   - 🗑 *Waste*: Generation monitoring in kg

2. *Environmental Impact Calculation*
   - Automated CO2 emissions calculation
   - Water usage aggregation
   - Activity-based carbon footprint analysis

3. *Data Management*
   - 💾 Save activities to JSON file
   - 📂 Load existing data
   - 🗑 Delete individual or all activities
   - 📊 Persistent data storage

4. *Analytics & Reporting*
   - 📈 Summary dashboard with key metrics
   - 📋 Detailed activity logs
   - 📊 Statistical breakdowns by activity type
   - 🌍 Comparison with global averages

5. *Smart Recommendations*
   - Context-aware sustainability suggestions
   - Personalized eco-friendly tips
   - Positive reinforcement for good habits

---

## 🚀 Installation

### Prerequisites

- *Python 3.x* (Python 3.6 or higher recommended)
- Standard Python libraries (pre-installed):
  - datetime
  - json
  - os
  - collections

### Setup Steps

1. *Clone or Download* the project files
   bash
   git clone <repository-url>
   cd environmental-impact-tracker
   

2. *Verify Python Installation*
   bash
   python --version
   # or
   python3 --version
   

3. *Run the Application*
   bash
   python environmental-impact-tracker.py
   # or
   python3 environmental-impact-tracker.py
   

---

## 📖 Usage Guide

### Starting the Application

1. *Launch the program*
   bash
   python environmental-impact-tracker.py
   

2. *Load existing data* (if prompted)
   - Select yes to load previous activities
   - Select no to start fresh

### Main Menu Options


╔════════════════════════════════════════════════════════════╗
║   ENVIRONMENTAL IMPACT TRACKER - MAIN MENU                 ║
╠════════════════════════════════════════════════════════════╣
║  1.  Add transport activity                                ║
║  2.  Add electricity usage                                 ║
║  3.  Add water usage                                       ║
║  4.  Add waste generation                                  ║
║  5.  View summary                                          ║
║  6.  View activity log                                     ║
║  7.  Get sustainability suggestions                        ║
║  8.  Delete activity                                       ║
║  9.  Save data to file                                     ║
║  10. Load data from file                                   ║
║  11. View detailed statistics                              ║
║  12. Compare with global averages                          ║
║  13. Clear all data                                        ║
║  14. Exit                                                  ║
╚════════════════════════════════════════════════════════════╝


### Example Workflows

#### 🚗 Tracking Transportation

1. Select option "1" (Add transport activity)
2. Choose transport type: car/bus/train/bike/walk
3. Enter distance in kilometers
4. System calculates and displays CO2 emissions


#### ⚡ Logging Electricity Usage

1. Select option "2" (Add electricity usage)
2. Enter consumption in kWh
3. System calculates CO2 emissions


#### 📊 Viewing Impact Summary

1. Select option "5" (View summary)
2. See total carbon footprint, water usage
3. View activity breakdown by category


#### 💾 Saving Your Data

1. Select option "9" (Save data to file)
2. Enter filename or press Enter for default
3. Data saved as JSON file


---

## 💻 System Requirements

### Minimum Requirements

| *Component* | *Specification* |
|---------------|-------------------|
| *OS* | Windows 7+, macOS 10.12+, Linux (any modern distribution) |
| *Python* | 3.6 or higher |
| *RAM* | 256 MB |
| *Storage* | 10 MB free space |
| *Display* | Terminal/Command Prompt access |

### Recommended

| *Component* | *Specification* |
|---------------|-------------------|
| *Python* | 3.9+ |
| *Terminal* | Modern terminal with emoji support |

---

## 📁 File Structure


environmental-impact-tracker/
│
├── environmental-impact-tracker.py    # Main application file
├── environmental_data.json            # Data storage (auto-generated)
├── README.md                          # This file
├── DOCUMENTATION.md                   # Technical documentation
│
└── docs/                              # Additional documentation
    ├── flowcharts/                    # System flowcharts
    ├── pseudocode/                    # Algorithm pseudocode
    └── examples/                      # Usage examples


---

## 🎯 Key Metrics & Constants

### Carbon Emission Factors

| *Activity* | *Emission Factor* | *Unit* |
|--------------|---------------------|----------|
| Car | 0.171 kg CO2 | per km |
| Bus | 0.089 kg CO2 | per km |
| Train | 0.041 kg CO2 | per km |
| Bike/Walk | 0.000 kg CO2 | per km |
| Electricity | 0.475 kg CO2 | per kWh |
| Waste | 0.500 kg CO2 | per kg |

### Reference Values

| *Metric* | *Average Daily Value* |
|------------|------------------------|
| Carbon Footprint | 11.0 kg CO2 |
| Water Usage | 150 litres |

---

## 👥 Contributors

This project was developed by :

- *ISHANI VERMA* (25BOE10013) - Lead Developer & Project Coordinator

*Course Instructor*: Dr. Vivek Parashar  
*Institution*: Vellore Institute of Technology, Bhopal


---

## 🔄 Version History

| *Version* | *Date* | *Changes* |
|-------------|----------|-------------|
| 1.0.0 | Nov 2025 | Initial release with core functionality |

---

## 📚 Documentation

For detailed technical documentation, including:
- System architecture
- Algorithm flowcharts
- Pseudocode
- Code breakdown
- API reference

Please refer to *[DOCUMENTATION.md](DOCUMENTATION.md)*

---

## 🌱 Environmental Impact

This application is designed to promote environmental awareness and sustainable living practices. By tracking your daily activities and their environmental impact, you can make informed decisions to reduce your carbon footprint and conserve resources.

### Sustainability Goals
- 🎯 Reduce personal carbon emissions by 20%
- 💧 Decrease water consumption by 15%
- ♻ Increase recycling and waste reduction efforts
- 🚴 Promote eco-friendly transportation alternatives

---

## 🙏 Acknowledgments

- Dr. Vivek Parashar for project guidance
- VIT Bhopal for academic support
- Environmental data sources for emission factor references
- Open-source Python community

---

## 📄 License

This project is developed for academic purposes as part of the Fundamental of AI ML course at VIT Bhopal. 

*Academic Use Only* - Not for commercial distribution.

---

## 🚀 Future Enhancements

Planned features for future versions:
- 📱 GUI interface using Tkinter/PyQt
- 📊 Data visualization with matplotlib
- 🌐 Web-based dashboard
- 📈 Trend analysis and predictions
- 🏆 Achievement system and gamification
- 🔔 Reminder notifications
- 📤 Export reports to PDF/Excel

---

*Made with 💚 for a sustainable future*

Every small action counts towards a better planet! 🌍

# FETP - Field Epidemiology Training Program
## Jamovi Module for Epidemic Curve Analysis

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Nivi3107/FETP-jamovi-module/releases)
[![Jamovi](https://img.shields.io/badge/jamovi-2.3+-green.svg)](https://jamovi.org)

## Overview

The FETP module provides comprehensive epidemic curve analysis tools specifically designed for Field Epidemiology Training Programs.

## ✨ Features

- 🗓️ **Mixed date format support**: dd-mm-yyyy, dd.mm.yyyy, dd/mm/yyyy, and more
- ⏰ **Time unit aggregation**: Day, week, month, year analysis
- 🎨 **Color customization**: 5 built-in color schemes + custom group colors
- 📊 **Professional styling**: Grid control, date formatting options
- 📋 **Summary tables**: Automatic case count aggregation
- 🔧 **Robust error handling**: Clear messages for data issues

## 📥 Installation

### Method 1: Direct Download (Easiest)

1. **Download the module**:
   - Go to [Releases](https://github.com/Nivi3107/FETP-jamovi-module/releases)
   - Download `FETP.jmo` from the latest release

2. **Install in jamovi**:
   - Open jamovi
   - Click the **⊕ Modules** button (top-right)
   - Click **"Install from file"** or **"Sideload"**
   - Browse and select the downloaded `FETP.jmo` file
   - Click **Install**

3. **Verify installation**:
   - New **"FETP"** menu should appear in jamovi
   - Look for **"Epidemic Curve"** under FETP → Descriptive Analysis

### Method 2: From jamovi Store (Future)
*Coming soon - module will be submitted to the official jamovi library*

## 🚀 Quick Start

1. **Load your data** in jamovi
2. **Go to**: FETP → Descriptive Analysis → **Epidemic Curve**
3. **Select variables**:
   - **Date Variable**: Your onset date column
   - **Case Count Variable**: (optional) If you have case counts
   - **Grouping Variable**: (optional) For grouped analysis
4. **Customize**:
   - Time Unit: Day/Week/Month/Year
   - Color Scheme: Blue/Red/Green/Purple/Orange
   - Date Format: Various display options
5. **View results**: Epidemic curve + summary table

## 📋 Requirements

- jamovi ≥ 2.3.0
- R packages: ggplot2, lubridate (auto-installed)

## 📖 Usage Examples

### Basic Epidemic Curve
- Date Variable: `onset_date`
- Leave other options as default

### Grouped Analysis
- Date Variable: `onset_date` 
- Grouping Variable: `case_classification`
- Time Unit: `week`
- Color Scheme: `blue`

### Custom Styling
- Show Background Grid: ☑️
- X-Axis Date Format: `dates_and_months`
- Group Colors: `#3498db,#e74c3c,#2ecc71`

## 🐛 Troubleshooting

**Date parsing issues?**
- Ensure dates are in format: dd-mm-yyyy, dd.mm.yyyy, or dd/mm/yyyy
- Module automatically handles mixed separators in same column

**Module not showing?**
- Check jamovi version ≥ 2.3.0
- Restart jamovi after installation

## 📧 Support

- **Issues**: [GitHub Issues](https://github.com/YourUsername/FETP-jamovi-module/issues)
- **Email**: drnivenkrishnan@gmail.com
- **FETP Community**: https://ncdc.mohfw.gov.in/

## 📄 License

GPL-3 License - Free for educational and research use

---
*Developed for Field Epidemiology Training Programs worldwide*



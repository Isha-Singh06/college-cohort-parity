# College Admissions Parity Simulator

## CPSC 564: Algorithms and their Societal Implications
Yale University, Fall 2024

## Overview
This project addresses the critical challenge of achieving demographic parity in college admissions by considering both admission offers and enrollment decisions. While many institutions strive for diversity in their admission offers, the final enrolled cohort often shows significant demographic disparities due to varying enrollment rates across different groups. Our simulator demonstrates how these disparities arise and proposes a modified admission strategy to achieve better representation in the final student body.

## Features
- Interactive GUI to simulate admission and enrollment processes
- Adjustable enrollment rates for different demographic groups
- Visualization of enrollment patterns across gender and racial categories
- Comparison between traditional and modified admission strategies
- Real-time calculation of parity metrics
- Bootstrap analysis for robust statistical estimates

## Components
- `app.py`: Main application with GUI interface
- `simulated.py`: Core simulation logic and statistical analysis
- `mba.py`: Data processing and visualization utilities

## Installation

Clone the repository:
```bash
git clone https://github.com/[username]/college-cohort-parity
```

Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python app.py
```

2. Adjust parameters using the sliders:
   - Set enrollment rates for different demographic groups
   - Modify total student population and admission targets
   - Choose between unmodified and modified admission strategies

3. View results:
   - Gender and racial enrollment distributions
   - Confidence intervals for enrollment rates
   - Parity metrics comparing demographic groups

## Key Findings
- Traditional admission strategies focusing only on offer parity can lead to significant enrollment disparities
- Our modified approach demonstrates improved demographic parity in final enrollment while maintaining academic standards
- The simulation reveals how varying acceptance rates across groups impact cohort composition

## Contributors
- Isha Singh
- Jonathan Elkobi
- Bhavya Kasera

## Acknowledgments
This project was developed for CPSC 564 under the guidance of Professor Nisheeth K. Vishnoi.

## Note
This project uses AI tools for code development and proofreading, as acknowledged in our project documentation.

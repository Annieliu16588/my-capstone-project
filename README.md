# Rice Leaf Color Analysis System

An intelligent system for analyzing rice leaf coloration to optimize fertilizer application through automated color chart analysis.

## System Requirements
### Hardware Requirements
- Model: MacBook Pro
- Processor: 2.3 GHz Dual-Core Intel Core i5
- Memory: 8GB 2133MHz LPDDR3 RAM
- Camera: Built-in webcam or external USB camera

### Software Requirements
- Operating System: macOS Catalina (10.15)
- Python 3.8+
- OpenCV 4.5.3
- NumPy 1.19.2
- Matplotlib 3.3.2

## Installation

1. Clone the repository
```bash
git clone https://github.com/Annieliu16588/my-capstone-project.git
cd my-capstone-project

2. pip install -r requirements.txt

3. python mainsystem.py

## Project Structure

my-capstone-project/
│
├── mainsystem.py         # Main system script
├── subcam.py            # Camera calibration script
├── requirements.txt     # Project dependencies
├── background1.png      # Background image
└── lcc_pic/            # Leaf color chart images
    └── lcc/            # Reference images

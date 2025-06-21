# Federated Learning IDS for IoT Healthcare

## Overview
Federated learning implementation for intrusion detection in IoT healthcare systems. Contains:
- Dataset: `icu-dataset/` (Attack.csv, patient/environment monitoring)
- Analysis notebook: `FL-privacy-icu-iot.ipynb`
- Research paper: *A Framework for Malicious Traffic Detection...*

## Directory Structure
```
.
├── A Framework for Malicious Traffic Detection...pdf
├── FL-privacy-icu-iot.ipynb
├── IoT Healthcare Security Dataset.md
└── icu-dataset/
    ├── Attack.csv
    ├── environmentMonitoring.csv
    └── patientMonitoring.csv
```

## Dataset Notes
- `Attack.csv` (73MB): Labeled network traffic data
- Key features: `timestamp`, `sensor_reading`, `device_id`, `malicious_activity`

## Setup
1. Clone repository:  
   ```bash
   git clone https://github.com/abyasham/FL-IDS-iot-healthcare.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt  # (create if needed)
   ```
3. Run analysis:  
   ```bash
   jupyter notebook FL-privacy-icu-iot.ipynb
   ```

## Contributing
- Use standard Git workflow
- Large files require [Git LFS](https://git-lfs.github.com) configuration

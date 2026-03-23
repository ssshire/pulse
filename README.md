### Core Concept

The tool begins by loading **customer (patient) information**, which acts as the user profile to initialize the device’s program.

Once initialized, the system begins piping in selected patient health data for **live monitoring**.

---

### Tracked Data

The system is designed to track key health metrics, including:

- Blood Pressure  
- Heart Rate  
- Oxygen Levels (SpO2)  
- Body Temperature  
- Sleep Stages  

The fields are selected and associated with each patient profile.

---
### System Flow

After loading a profile, the system performs one of two actions:

1. **Live Tracking** – monitors patient data in real time  
2. **Recorded Analysis** – stores data over time for later review  

---

### Design Focus

- Load and manage patient data  
- Separate live tracking and analysis logic  
- Keep system modular and efficient using Rust  

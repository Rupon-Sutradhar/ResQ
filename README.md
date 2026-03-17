# ResQ

Detect accidents. Trigger rescue. Save lives.

---

## Overview

ResQ is a real-time accident detection and emergency response system designed to reduce response time and improve road safety. It processes video input to identify accident scenarios and immediately notifies emergency services with location details.

---

## Features

- Real-time accident detection  
- Video-based monitoring  
- Location-based alert system  
- Instant emergency notifications  
- Fast response triggering  

---

## How It Works


Video Input → Detection System → Accident Identified → Alert Triggered


- The system processes video frames continuously  
- It detects abnormal events such as collisions or sudden stops  
- The location of the incident is identified  
- An alert is sent to the emergency service  

---

## Architecture


Camera / Video
↓
Detection Module (OpenCV / YOLO)
↓
Accident Detection
↓
Backend (FastAPI)
↓
Alert System (Email / WhatsApp)


---

## Tech Stack

- Python  
- OpenCV  
- FastAPI  
- NumPy  
- YOLO (optional)  

---

## Project Structure

```bash
ResQ/
├── backend/
│   ├── main.py
│   └── alert.py
│
├── detection/
│   ├── detect.py
│   └── model.py
│
├── data/
│   └── videos/
│
├── requirements.txt
└── README.md

```

```bash

#Installation
git clone https://github.com/your-username/ResQ.git
cd ResQ
pip install -r requirements.txt
Run the Project
python detection/detect.py

or

uvicorn backend.main:app --reload
Demo

```

```bash
#Run the system

Play a sample accident video

The system detects the event

An alert is triggered
```

---
### Future Improvements

<br>
Severity classification of accidents
<br>
Integration with live GPS data
<br>
Mobile notification system
<br>
Deployment in traffic monitoring environments
---

### Contributors

Rikim
<br>
Prakash
<br>
Rupon
<br>
Yogesh
<br>
Dinesh
<br>
Sagar

---

### License
This project is intended for academic and demonstration purposes.

---
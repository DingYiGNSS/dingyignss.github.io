---
title: "York-Huawei Smartphone Collaboration Project"
duration: 2021 – 2023  
role: GNSS Algorithm Developer / Project Lead
collaboration: York University × Huawei 
collection: projects
excerpt: "Design of core RTK and PPP GNSS+IMU C++ code for smartphone navigation in realistic driving environments <br/><img src='HW.png' style='width: 500px;'>"
---

### Project Overview
This project focused on the **development and evaluation of advanced smartphone-based GNSS positioning algorithms** for realistic vehicle navigation scenarios. The primary objective was to design and implement **core RTK and PPP GNSS+IMU C++ processing software, Jaqen**, enabling high-accuracy positioning using low-cost smartphone sensors in challenging driving environments.

An end-to-end framework covering algorithm development, field experimentation, and performance validation was established through close collaboration between **York University and Huawei**.

---

### Phase 1: RTK GNSS + IMU Algorithm Development
- Developed **multi-GNSS (GPS, GLONASS, Galileo, BeiDou) single- and dual-frequency float RTK software** using a **Sequential Least Squares (SLS) estimator**.
- Designed an **Extended Kalman Filter (EKF)** architecture supporting both **loosely coupled** and **tightly coupled RTK+IMU integration**.
- Implemented robust measurement modeling and state propagation tailored to **smartphone-grade GNSS and IMU sensors**.

---

### Phase 2: Vehicle Field Testing and RTK+IMU Evaluation
- Customized **pre-processing and post-processing modules** to accommodate smartphone-specific GNSS characteristics.
- Organized and conducted **vehicle field tests** across diverse environments, including:
  - Open-sky highways  
  - Vegetation-covered roads  
  - Moderate urban environments  
  - Overpasses and complex road geometries
- Evaluated positioning performance in **simulated real-time mode**, achieving acceptance criteria for:
  - **95th and 68th percentile horizontal accuracy**
  - **Positioning success rate**

---

### Phase 3: PPP GNSS + IMU Algorithm Development
- Extended the RTK+IMU framework by integrating **Precise Point Positioning (PPP)** functionalities.
- Developed **multi-GNSS single- and dual-frequency float PPP processing modules** with an **ionospheric-constrained strategy**.
- Participated in the **2022 Google Smartphone Decimeter Challenge (GSDC)**, achieving a score of **2.485** using simulated real-time solutions.

---

### Phase 4: Vehicle Field Testing and PPP+IMU Evaluation
- Enhanced traditional PPP solutions by incorporating **code-only satellites and measurements**.
- Led large-scale **vehicle measurement campaigns** and validated PPP+IMU performance under realistic driving conditions.
- Successfully met the same acceptance criteria as RTK+IMU testing for:
  - Horizontal accuracy percentiles  
  - Positioning robustness and reliability
- Coordinated **York–Huawei technical meetings** and led the submission of final project deliverables.

---

### Key Outcomes
- End-to-end **C++ GNSS+IMU processing software** for smartphone-based RTK and PPP applications.
- Demonstrated **Accurate positioning performance (<1.5 m>)** in realistic driving environments using low-cost sensors.
- Provided a solid technical foundation for subsequent research on **smartphone PPP, multi-sensor integration, and urban navigation**.

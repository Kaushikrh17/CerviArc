# 🤰 CerviArc: Advanced Cervical Dilation Measurement System

## 🌟 Project Goal
CerviArc is an innovative medical device designed to **accurately and objectively measure cervical dilation**. The primary objective is to standardize labor assessment and enhance the safety and effectiveness of childbirth management, overcoming the subjectivity of the current method, the digital vaginal examination.

---

## ✨ Why CerviArc? (Key Features)

CerviArc moves beyond traditional, subjective methods to provide critical, real-time data.

| Feature | Description |
| :--- | :--- |
| **Objective Measurement** | [cite_start]Provides precise, numerical data, eliminating the guesswork associated with manual finger-based examination[cite: 15]. |
| **Innovative Design** | [cite_start]Utilizes a **mini inverted umbrella mechanism** for safe, gradual expansion and measurement within the cervical canal[cite: 50]. |
| **Patient-Centric** | [cite_start]Constructed from flexible, **biocompatible materials** (like Medical-Grade Silicone) for safe and comfortable use during labor[cite: 49, 70]. |
| **Real-Time Feedback** | [cite_start]Equipped with sensors that provide **immediate dilation status** and pressure feedback, aiding in enhanced clinical decision-making[cite: 51, 120]. |

---

## 🛠️ System Components and Technology

The device integrates a mechanical design with a novel pressure sensor and advanced signal processing.

### 1. Mechanical Structure: Layered Hollow Cylinder

[cite_start]The main structure is a multi-layered hollow cylinder designed for durability and comfort[cite: 67].

| Layer | Material | Purpose |
| :--- | :--- | :--- |
| **Outer** | Medical-Grade Silicone | [cite_start]Superior comfort, pliability, and high **biocompatibility**[cite: 68]. |
| **Middle** | Polyurethane (PU) | [cite_start]Added support and durability; strong enough to resist deformation when the mini umbrella expands[cite: 68]. |
| **Inner** | PEEK or UHMWPE | [cite_start]Structural backbone providing **mechanical strength** and resistance to internal pressure[cite: 68]. |

### 2. Novel Pressure Sensing (Primary Method)

[cite_start]The core of the measurement is an innovative sensor concept for continuous pressure monitoring[cite: 80].

| Component | Working Principle |
| :--- | :--- |
| **Deformable Sphere** | [cite_start]A hollow, biocompatible sphere that deforms under pressure from the cervical wall[cite: 84]. |
| **Quartz Crystal** | [cite_start]Embedded within the sphere, the compression generates an electrical signal due to the **piezoelectric effect** (Signal Transduction)[cite: 86, 106]. |

### 3. Instrumentation and Filtering

[cite_start]The small electrical signal from the quartz crystal is processed to ensure accuracy[cite: 143].

* [cite_start]**Signal Amplification:** An **instrumentation amplifier** boosts the weak sensor signals to measurable levels[cite: 146, 208].
* [cite_start]**Noise Reduction:** Filtering circuits, specifically a **Chebyshev 4th Order Filter**, are used to remove high-frequency electrical noise and interference from the sensor data[cite: 152, 220, 224].
* [cite_start]**Digital Conversion:** Analog-to-digital conversion allows the processed sensor data to be handled by a microcontroller[cite: 153, 154].

---

## 💻 Alternative Approach: Image Processing

In addition to the pressure sensor, an image processing approach using **Circle Detection** was explored as an alternative method for measuring dilation.

The methodology involves:
1.  **Image Pre-processing:** Reading and resizing the cervix image.
2.  **Color Masking:** Converting the image to HSV and applying a mask (using `cv2.inRange`) to isolate the cervix region.
3.  **Contour Detection:** Finding the contours of the masked region.
4.  **Diameter Calculation:** Determining the maximum distance between any two points on the main contour to find the **diameter/width** of the opening.
5.  **Conversion:** Converting the pixel width into centimeters using a predefined calibration factor (`cm_per_pixel`).

This approach provides a visual and computationally derived measurement of the dilation opening.


---

## 🛣️ Development Status and Future Scope

### Current State
[cite_start]The cervical wall pressure sensor is currently in the **prototype development stage** and is undergoing rigorous testing and refinement[cite: 126].

### Future Directions
1.  [cite_start]**Clinical Trials & Regulatory Approval:** The device will proceed to clinical trials to evaluate safety and performance, followed by seeking regulatory approval[cite: 128, 130].
2.  [cite_start]**Therapeutic Dilation:** Explore actively **inducing CerviArc into the uterus** to expand cervix walls for pregnant women experiencing slow dilation[cite: 137].
3.  [cite_start]**Predictive Delivery:** Integration of AI/ML and image processing is planned to help **predict the delivery of the baby**[cite: 138, 264].
4.  [cite_start]**Advanced Sensor Fusion:** Further integrate a **microphone array** for audio-based detection to supplement existing data[cite: 496].

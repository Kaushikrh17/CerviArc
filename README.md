# 🤰 CerviArc: Advanced Cervical Dilation Measurement System

## 🌟 Project Goal
CerviArc is an innovative medical device designed to **accurately and objectively measure cervical dilation**. The primary objective is to standardize labor assessment and enhance the safety and effectiveness of childbirth management, overcoming the subjectivity of the current method, the digital vaginal examination.

---

## ✨ Why CerviArc? (Key Features)

CerviArc moves beyond traditional, subjective methods to provide critical, real-time data.

| Feature | Description |
| :--- | :--- |
| **Objective Measurement** | Provides precise, numerical data, eliminating the guesswork associated with manual finger-based examination. |
| **Innovative Design** | Utilizes a **mini inverted umbrella mechanism** for safe, gradual expansion and measurement within the cervical canal. |
| **Patient-Centric** | Constructed from flexible, **biocompatible materials** (like Medical-Grade Silicone) for safe and comfortable use during labor. |
| **Real-Time Feedback** | Equipped with sensors that provide **immediate dilation status** and pressure feedback, aiding in enhanced clinical decision-making. |

---

## 🛠️ System Components and Technology

The device integrates a mechanical design with a novel pressure sensor and advanced signal processing.

### 1. Mechanical Structure: Layered Hollow Cylinder

The main structure is a multi-layered hollow cylinder designed for durability and comfort.

| Layer | Material | Purpose |
| :--- | :--- | :--- |
| **Outer** | Medical-Grade Silicone | Superior comfort, pliability, and high **biocompatibility**. |
| **Middle** | Polyurethane (PU) | Added support and durability; maintains flexibility and resists deformation during umbrella expansion. |
| **Inner** | PEEK or UHMWPE | Structural backbone providing **mechanical strength** and resistance to internal pressure. |

### 2. Novel Pressure Sensing

The core of the measurement is an innovative sensor concept for continuous pressure monitoring.

| Component | Working Principle |
| :--- | :--- |
| **Deformable Sphere** | A hollow, biocompatible sphere that deforms when the cervical wall exerts pressure on it. |
| **Quartz Crystal** | Embedded within the sphere, the compression generates an electrical signal due to the **piezoelectric effect**. |

### 3. Instrumentation and Filtering

The small electrical signal from the quartz crystal is processed to ensure accuracy.

* **Signal Amplification:** An **instrumentation amplifier** boosts the weak sensor signals to measurable levels, ensuring even minor changes in dilation are detected.
* **Noise Reduction:** A **Chebyshev 4th Order Filter** is used to remove high-frequency electrical interference, providing a cleaner signal for accurate real-time measurements.
* **Digital Conversion:** Analog-to-digital conversion prepares the data for processing by a microcontroller.

---

## 🧠 AI and Image Processing Integration

The project includes advanced computational methods for enhanced clinical utility:

* **Predictive Modeling:** Advanced AI/ML algorithms are applied to analyze real-time sensor data patterns to develop models that **accurately estimate cervical dilation progression**.
* **Image Processing:** Techniques like **Circle Detection** and thresholding are utilized to visually and numerically measure the radius of the cervical opening, providing an objective visual cross-reference.

---

## 🛣️ Development Status and Future Scope

### Current State
The cervical wall pressure sensor is currently in the **prototype development stage** and is undergoing rigorous testing and refinement.

### Future Directions
1.  **Clinical Trials & Regulatory Approval:** After prototype finalization, the device will proceed to clinical trials to evaluate safety and performance, followed by seeking regulatory approval.
2.  **Therapeutic Dilation:** Future advancements include exploring the possibility of actively **inducing CerviArc into the uterus** to expand cervix walls for pregnant women experiencing slow dilation.
3.  **Predictive Delivery:** Integration of image processing is planned as a major development to help **predict the delivery of the baby**.
4.  **Miniaturization:** Further size reduction and integration with other medical devices are planned.

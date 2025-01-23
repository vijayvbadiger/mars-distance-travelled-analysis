# mars-distance-travelled-analysis
Analysis of the distance travelled by Mars relative to Earth using WebGeoCalc
# Project Documentation: Mars Distance Travelled Analysis

## **Objective**<img width="1433" alt="Screenshot 2025-01-21 at 1 52 48 PM" src="https://github.com/user-attachments/assets/5ef3e684-b903-43f6-a7d5-0abbc4f960cc" />

To calculate the distance travelled by Mars when observed from Earth over a specified time range using NASA's WebGeoCalc tool and SPICE kernels.

---

## **Overview**
This project utilizes the **Distance Finder** tool in WebGeoCalc to calculate the total distance Mars travelled relative to Earth within a specific time range. The calculation is based on SPICE kernel data, ensuring precise and accurate ephemeris data for Mars and Earth.

---

## **Inputs Used**

### **1. Kernels Selected**
- **Ground Stations Kernels**
- **Solar System Kernels** (`v0059.tm`)
- **Latest Leap Seconds Kernel** (`v0004.tm`)
- **SPICE Class - Mars Express Geometric Event Finding Lesson Kernels**

### **2. Target and Observer**
- **Target**: Mars
- **Observer**: Earth

### **3. Aberration Correction**
- **None**: No light-time corrections were applied.

### **4. Time Range**
- **Start Time**: `2020-01-21 13:00:00 UTC`
- **Stop Time**: `2020-01-22 13:00:00 UTC`
- **Step Size**: 24 hours

### **5. Event Condition**
- **Distance Condition**: Distance between Mars and Earth over time.

---

## **Outputs**

### **Result Summary**
- **Start Time**: `2020-01-21 13:00:00 UTC`
- **Stop Time**: `2020-01-22 13:00:00 UTC`
- **Duration**: `86400 seconds` (1 day)

### **Plot Analysis**
- The plot generated illustrates the distance travelled by Mars when observed from Earth during the specified time range.
- The distance interval shows continuous motion of Mars relative to Earth over the 24-hour period.

---

## **Tools and Methods**

### **Tools Used**
1. **WebGeoCalc**: A web-based interface for SPICE calculations.
2. **SPICE Kernels**: Provide accurate planetary and spacecraft ephemeris data.

### **Calculation Methodology**
- The **Distance Finder** tool was used to calculate the distance between Mars and Earth over the specified time range.
- Data was visualized to analyze Mars's relative motion.

---

## **Conclusion**
The analysis provides a precise measurement of Mars's distance travelled relative to Earth within the specified time range, aiding in understanding Mars's orbital dynamics. The plot confirms consistent motion over the analyzed period.

---

## **Results Visualization**
Below is the plot generated for this project:

![Mars Distance Travelled Plot](Screenshot%202025-01-21%20at%201.52.48%20PM.png)


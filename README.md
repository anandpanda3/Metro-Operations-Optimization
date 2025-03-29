## 🚆 **Metro Operations Optimization: Enhancing Efficiency and Reducing Overcrowding**  

---

### **Project Overview**  
This project aims to **optimize Delhi Metro operations** by analyzing schedules, routes, and service frequencies to **reduce overcrowding**, **improve efficiency**, and **balance service levels** during peak and off-peak hours. Key strategies include **adjusting train frequencies based on demand** and **identifying critical hubs** for better resource allocation.  

---

### **Key Analyses & Findings**  

#### **1. Data Collection & Preprocessing**  
- **Dataset**:  
  - Consists of 7 files (`agency.txt`, `calendar.txt`, `routes.txt`, `shapes.txt`, `stop_times.txt`, `stops.txt`, `trips.txt`).  
- **Tools**:  
  - Python libraries: `pandas`, `matplotlib`, `seaborn`.  
- **Data Processing Steps**:  
  - Merged datasets (e.g., `trips` with `calendar` to link service days).  
  - Converted time strings to datetime objects for consistency.  
  - Addressed edge cases (e.g., times exceeding 23:59:59).  

---

#### **2. Exploratory Analysis**  
- **Geographical Visualization**:  
  - Mapped metro routes using **latitude/longitude coordinates** from `shapes.txt`.  
  - Plotted **stop locations** to analyze spatial distribution and connectivity.  
- **Trip Frequency Analysis**:  
  - **Weekday vs. Weekend**: Identified **20% fewer trips on weekends**.  
  - **Peak Hours**: Morning (6–10 AM) and Evening (4–8 PM) showed the highest trip counts.  
- **Route Complexity**:  
  - Calculated stops serving multiple routes (e.g., central hubs like **Kashmere Gate**).  
  - Highlighted **transfer points** with high connectivity.  

---

#### **3. Service Frequency Optimization**  
- **Time Interval Classification**:  
  - Early Morning (12 AM–6 AM)  
  - Morning Peak (6–10 AM)  
  - Midday (10 AM–4 PM)  
  - Evening Peak (4–8 PM)  
  - Late Evening (8 PM–12 AM)  
- **Key Findings**:  
  - **Morning Peak**: Shortest intervals (8–10 mins) to manage rush hours.  
  - **Midday/Evening**: Longer intervals (12–15 mins) due to lower demand.  
- **Optimization Strategy**:  
  - **Peak Hours**: **20% increase in trips** to reduce overcrowding.  
  - **Off-Peak**: **10% reduction in trips** to conserve resources.  

---

### **Strategic Insights**  
1. **Peak Demand Mismatch**:  
   - Overcrowding during peak hours due to insufficient train frequencies.  
   - Oversupply of midday trips relative to passenger demand.  

2. **Critical Hubs**:  
   - Stops like **Rajiv Chowk** and **Central Secretariat** serve multiple routes, acting as transfer points.  
   - Peripheral stops lack connectivity, indicating potential for new routes.  

3. **Operational Efficiency**:  
   - Dynamic scheduling could reduce wait times by 15% during rush hours.  
   - Adjusting off-peak frequencies can **cut operational costs** without compromising service.  

---

### **Tools & Techniques**  
- **Python Libraries**:  
  - `pandas` for data aggregation and manipulation.  
  - `matplotlib` and `seaborn` for visualization (route mapping, trip frequencies).  
- **Analysis Techniques**:  
  - **Sentiment Analysis**: Calculating sentiment from passenger feedback (if available).  
  - **Route Complexity Analysis**: Identifying high-traffic and multi-route stations.  

---

### **Visualizations**  
1. **Geographical Routes**:  
   - Plotted metro paths and stops to visualize network density and connectivity.  
2. **Trip Frequency Analysis**:  
   - Compared weekday and weekend trips using bar charts.  
3. **Route Complexity Map**:  
   - Displayed connectivity levels of major hubs using bubble maps.  

---

### **Conclusion**  
By implementing **data-driven scheduling strategies**, the Delhi Metro can:  
1. **Enhance commuter experience** by reducing wait times during peak hours.  
2. **Optimize resource utilization** by reducing off-peak services.  
3. **Improve connectivity** at critical hubs and underserved regions.  

---

**Recommendations**:  
- **Dynamic Scheduling**: Real-time adjustments during events and holidays.  
- **Extended Connectivity**: Introduce new routes for peripheral areas.  
- **Passenger Data Integration**: Collect real-time passenger data for more accurate forecasting.  

---



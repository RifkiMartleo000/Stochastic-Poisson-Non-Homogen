## 📱 Stochastic Process: Non-Homogeneous Poisson Process (NHPP)  
### **Case Study: Customer Order Arrivals in StudentEXpress WhatsApp Group**

This repository analyzes **customer order arrivals** in the **StudentEXpress WhatsApp group** using a **Non-Homogeneous Poisson Process (NHPP)** — modeling time-varying order intensity based on **primary observational data**.

---

### Data Source:
- **Primary Data** collected via **direct observation**  
- **Date**: Monday, **16 June 2025**  
- **Time**: **06:00 – 24:00 WIB** (18-hour window)  
- **Platform**: StudentEXpress WhatsApp Group  

---

### Key Variables:
| Variable | Description |
|--------|-------------|
| **Order Timestamp** | Every one hour interval |
| **Number of Customers** | Total orders per time interval |

---

### Methodology:
- **NHPP Modeling** with time-dependent intensity **λ(t)**  
- **Intensity Function**: Peaks during breakfast (07–09), lunch (12–14), and evening (18–21)  
- **Estimation**: Maximum Likelihood Estimation (MLE) from observed arrivals  
- **Simulation**: Thinning & inverse transform methods  

---

### Key Features:
- Event timeline & cumulative order plot  
- Estimated **λ(t)** intensity curve  
- Goodness-of-fit tests (Kolmogorov-Smirnov)  
- Peak hour identification & queue prediction  

> **Insight**: Order rate surges **about 4x** during meal times — critical for staffing & response planning.

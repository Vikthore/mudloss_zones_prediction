
# 🛢️ Mud Loss Prediction in Niger Delta Oil Wells Using Machine Learning

## Overview

Mud loss during drilling is a costly and risky event that can compromise well integrity and delay operations. This project presents a **static HTML dashboard** generated using Python and visualized with **Seaborn** and **Matplotlib**. It evaluates the performance of three machine learning models—**Isolation Forest**, **Mixture Density Network (MDN)**, and **Convolutional Neural Network (CNN)**—on historical data from Niger Delta oilfields to predict mud loss occurrences.

## 📁 Project Structure

```
Inventory_data_analytics.html   ← Fully rendered dashboard file
README.md                       ← Project overview and instructions
```

## ⚙️ Project Highlights

- **Dataset**: Historical drilling records from Niger Delta wells, including mud weight, depth, rate of penetration, and flow rate.
- **ML Models Evaluated**:
  - Isolation Forest (Anomaly detection)
  - Mixture Density Network (Probabilistic modeling)
  - Convolutional Neural Network (Deep learning for sequence classification)
- **Performance Metrics**:
  - CNN leads across all metrics: F1 = 0.81, Precision = 0.83, Recall = 0.80, ROC-AUC = 0.95, Average Precision = 0.89
  - MDN performs well, especially with uncertainty-aware outputs.
  - Isolation Forest is the least effective due to its limited capability in structured sequences.

## 📊 Visualization Tools

- **Seaborn**: For advanced statistical plotting.
- **Matplotlib**: For base-level static and comparative charting.

All visual outputs are embedded in the HTML file for ease of review and sharing.

## 💡 How to Use

1. Download or clone the repository.
2. Open `Inventory_data_analytics.html` in any modern browser (Chrome, Firefox, Edge).
3. Interact with the static visualizations and compare model performance.
4. Use insights to guide predictive modeling in real-world drilling environments.

## 🔍 Key Takeaways

- CNN is highly recommended for real-time mud loss prediction.
- MDNs provide valuable probabilistic insight, useful in high-risk scenarios.
- Isolation Forest may be unsuitable for complex, temporal drilling data.

## 📚 Future Directions

- Integration with real-time rig monitoring systems.
- Incorporation of **physics-informed models** for better field alignment.
- Development of a lightweight web interface or app for operational use.

## 📫 Contact

**Victor Ikechukwu**  
📧 Email: [vikechukwu43@gmail.com](mailto:vikechukwu43@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/victor-ikechukwu-1169942a7](https://www.linkedin.com/in/victor-ikechukwu-1169942a7?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
📍 Location: Port Harcourt, Nigeria

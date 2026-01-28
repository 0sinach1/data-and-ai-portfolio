## Business Recommendations

- Implement continuous anomaly monitoring at both total and category levels

- Investigate anomaly periods for operational, pricing, or supply-chain causes

- Combine statistical and ML-based detection for higher reliability

- Integrate anomaly detection with forecasting models for proactive planning



## ✍️ Z-Score vs Isolation Forest

Add a short comparison paragraph:

Comparing statistical (Z-score) and machine learning–based (Isolation Forest) anomaly detection revealed both overlapping and distinct anomaly periods.
Z-score detection was more sensitive to sudden short-term spikes and drops, while Isolation Forest captured broader pattern irregularities across multiple features.

This suggests that combining both approaches provides a more robust monitoring system, where statistical methods offer transparency and machine learning methods provide adaptability.


## 🔚 Final Conclusion

_This project demonstrated how sales anomaly detection can be applied to retail data using both statistical and machine learning approaches._
By aggregating sales over time and applying rolling statistics, the analysis successfully identified abnormal sales behavior relative to recent trends.

Extending the analysis to the product category level revealed that certain anomalies were driven by specific categories rather than overall sales performance, highlighting the importance of granular monitoring.

Finally, the use of Isolation Forest introduced a machine learning–based approach capable of detecting complex and non-linear irregularities that traditional statistical methods may overlook. The comparison between methods showed that no single technique is sufficient on its own, and a hybrid approach provides stronger decision support.

From a business perspective, anomaly detection enables early identification of risks and opportunities, supports proactive investigation, and forms a foundation for more advanced systems such as demand forecasting and automated alerting. This project establishes a scalable framework for intelligent sales monitoring in real-world environments. 
Enhancing Anomaly Detection for Water Pumps for Siemens
used K-means(1/7) and Forest Isolation(6/7)


This project explores a real-world industrial sensor dataset simulating a Siemens pump. The goal is to detect abnormal operating conditions using unsupervised methods, because the BROKEN class is extremely rare.

What I Did

Cleaned and prepared 50+ sensor streams

Visualized individual sensors and compared NORMAL vs RECOVERING vs BROKEN

Performed dimensionality reduction using PCA (3 components)

Applied three anomaly detection methods:

PCA + IQR thresholds

KMeans distance-based anomalies

Isolation Forest

Compared each method against actual machine states

Key Insight

PCA+IQR is highly sensitive (catches most abnormal patterns)

KMeans is strict and flags fewer anomalies

Isolation Forest provides a balanced middle ground



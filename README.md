Dataset Context
Data Collection: The dataset was created by capturing network packets over six days (April 26-28, May 9, 11, and 15) at different times of the day.

Volume: The dataset contains 3,577,296 instances stored in a CSV file.

Content
Features: It includes 87 features, such as:

Source and destination IP addresses

Ports

Inter-arrival times

Layer 7 protocol (application layer) used as the class

Numeric, nominal, and timestamp-based attributes

Flow Statistics Tools:

CICFlowMeter: Used to compute flow statistics (e.g., IPs, ports, inter-arrival times).

Ntopng (Deep Packet Inspection): Used to label the application-layer protocol.

Purpose
The dataset enables machine learning models to classify network traffic and identify not just general types of traffic (e.g., WWW, DNS) but specific applications (e.g., Facebook, YouTube, Instagram) based on IP flow statistics.

Acknowledgments
The dataset was developed with support from Universidad del Cauca and Colciencias (Colombian Science, Technology, and Innovation Department).

Inspiration
This dataset is unique in its aim to detect specific applications from IP flow data, advancing beyond general traffic classification.

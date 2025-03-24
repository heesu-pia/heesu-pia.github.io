<!-- <img src="https://github.com/oneQuery/oneQuery.github.io/assets/24229051/59754b18-5a66-4ec7-b8c2-5f6166af9485" width="141" height="180"> -->

# Heesu Kim
_AI Researcher | Deep Learning Architect | Vision-Language Fusion Specialist_  
📍 Seoul, South Korea | ✉️ heesu-kim@outlook.com | 📞 +82-10-2382-7494 | [GitHub](https://github.com/heesu-pia) | [Scholar](https://scholar.google.com/citations?hl=en&user=foCKZlQAAAAJ)

## Summary
AI Researcher with 7+ years of experience in deep learning and real-world AI applications across smart transportation, intelligent surveillance, and human-centered AI systems. Proven track record in both academic research and large-scale enterprise deployment, with expertise in multi-modal fusion, scene understanding, and real-time edge optimization. Strong communicator with cross-functional leadership and full-cycle system design experience.

## Core Expertise
- Multi-modal Learning: Text-Video Retrieval, VLMs, Cross-modal Fusion (Image/Text)
- Vision AI: Object Detection, Pose Estimation, Semantic Scene Understanding
- AI Optimization: TensorRT, Deployment Pipelines (GCP, Docker)
- Research Skills: Deep RL, Transformer Architectures, Attention & Embedding Design
- Tech Stack: Python, PyTorch, OpenCV, Git, Sphinx, ROS, Linux
- Language: English (Study & research in US/UK), Korean (Native)

## Work Experience

| Period             | Position              | Organization     | Key Responsibilities                                                                                          |
|--------------------|------------------------|------------------|----------------------------------------------------------------------------------------------------------------|
| 2023.07 – Present  | AI Team Lead           | PIA Space        | Built text-video retrieval and anomaly detection models. Optimized inference latency and integrated models into real-time pipelines. Leading [MACS](https://pia.space/#MACS) development and deployment, designing scalable multi-modal retrieval pipelines (CLIP4Clip, BLIP, VLM), and system-wide integration. |
| 2022.07 – 2023.06  | AI Researcher          | SNUAILAB         | Co-developed [Waffle](https://github.com/snuailab/waffle_hub): a modular DL training framework focused on scalability and reproducibility.              |
| 2022.01 – 2022.06  | Research Associate     | Inha University  | Implemented RL-based collision avoidance for unmanned surface vehicles (ROS-based navigation stack).         |
| 2021.08 – 2021.12  | Research Assistant     | Univ. of Virginia| Built RL-based evaluation framework for simulated surgical skill assessment.                                 |
| 2019.08 – 2021.07  | Research Assistant     | Univ. of Iowa    | Built CNN-based seatbelt misuse and posture detection system. Applied HPE for ergonomic risk evaluation.     |
| 2017.12 – 2018.07  | Research Intern        | KRISO            | Contributed to ship autopilot integration and early development of autonomous navigation logic.              |

<!--
### **AI Solution Team Leader / Tech Lead, [PIA Space](https://pia.space/)**
_2024–Present_
- Lead architect of "[MACS](https://pia.space/#MACS)": real-time AI CCTV solution with multi-modal event detection.
- Designed scalable pipelines for vision-language fusion (CLIP4Clip, BLIP, custom VLMs).
- Deployed solutions in smart cities, industrial sites, and urban infastructure systems.

### **AI Engineer, [PIA Space](https://pia.space/)**  
_2023-2024_
- Developed text-to-video retrieval & temporal grounding algorithms for scene analysis.
- Built training pipelines using large-scale video-text datasets and optimized inference latency.

### **AI Researcher, [SNUAILAB](http://www.snuailab.com/)** 
_2022-2023_
- Co-developed "[Waffle](https://github.com/snuailab/waffle_hub)": a modular deep learning framework for scalable training/inference.
- Focused on reproducibility, adaptive scheduling, and model compression.

### **Research Associate, Inha University**  
_2022_
- Implemented collision avoidance for unmanned surface vehicles using RL on ROS.

### **Research Assistant, University of Virginia**  
_2021-2022_
- Developed reinforcement learning framework to evaluate surgical skills using simulation.

### **Research Assistant, University of Iowa**  
_2019-2021_
- Designed CNN-based driver monitoring system detecting seatbelt misuse and posture.
- Integrated pose estimation for ergonomic assessment.

### **Internship, KRISO**  
_2017-2018_
- Worked on **ship autopilot system integration**, contributing to **autonomous navigation algorithms**.
-->

## **Project Experience**

### Smart Port Surveillance @ Incheon (2024.07-12, ~5 months)
- Role: AI Researcher
- Contribution: Deployed MACS into international passenger terminal. Developed fine-tuned VLM for loitering/falling detection.
- Impact: 99.74% F1 on KTL-certified test. Reduced false positives >40% vs. CNN baseline.

### Tunnel Emergency Detection AI (2024.07-12, ~5 months)
- Role: Lead Architect
- Contribution: Built embedded inference system to detect loitering/intrusion/falling in tunnels. Implemented TensorRT-optimized models.
- Impact: Achieved 17.89 FPS real-time performance with 88.8% mAP, cost 80% less than traditional smart CCTV.

### KTT-Coupang Surveillance PoC (2024.06-12, ~6 months)
- Role: AI Researcher
- Contribution: Developed multi-modal Top-K similarity retrieval model to detect clothing changes, box opening, and unauthorized access in logistics.
- Impact: Enabled multi-camera MACS deployment across 16 streams with scalable retrieval API.

### City-Scale Disaster Monitoring (2024.06-12, ~6 months)
- Role: Lead Architect
- Contribution: Integrated multi-modal anomaly detection across 30+ live CCTV channels (violence/fire/flood). Developed scene-level decision logic.
- Impact: Scaled surveillance for urban response. Deployment verified in public infrastructure scenario.

### LG U+ Industrial Safety AI (2024.02-04, ~2 months)
- Role: AI Researcher
- Contribution: Built VLM-based real-time behavior detector (fire/smoke/fall/high-place), prompt-driven anomaly recognition, stable RTSP relay on 600+ cameras.
- Impact: F1-score improved 2.5× (baseline 38 → 96). Integrated into LG U+ infrastructure under 10 Gbps load.

### Data Voucher Project (2023.06-12, ~6 months)
- Role: AI Researcher
- Contribution: Created text-video retrieval module for CCTV query search.
- Impact: Recall@10 improved 16.8%p on in-domain evaluation set.

### HanaTour Video Retrieval Platform (2023.05-10, ~5 months)
- Role: AI Researcher
- Contribution: Applied CLIP4Clip for 4TB of travel footage. Customized descriptor ranking model.
- Impact: Precision@5: 74.67%, MRR: 69.83%. Automated short-form recommendation.

## Certification
### **KISA AI Security Certification(2024)**
- Certified product: MACS-K (v1.0–v2.2), intelligent surveillance AI system.
- Validated on national CCTV benchmark (RGB/IR/weather), F1-score up to 99.0.
- Certified events: loitering, intrusion, falling, fire, fighting, abandonment.

## Solutions Engineering
- [MACS CCTV AI](https://pia.space/#MACS): Multi-modal anomaly detection + text-based retrieval, DeepStream + RTSP + CLIP4Clip stack.
- [Waffle Hub](https://github.com/snuailab/waffle_hub): Scalable DL training codebase with CLI abstraction, schedule tuning, & experiment tracking.

<!-- 
### Government R&D Projects (B2G)
- 2024 Municipal CCTV Video Analysis Technology Demonstration Project
  - Project Title: "Multi-modal AI-based Disaster Safety Anomaly Detection CCTV Solution for Emergency Response"​
  - Duration: 2024​
  - Role: Lead AI Architect​
  - Responsibilities: Developed and deployed multi-camera anomaly detection systems capable of identifying events such as violence, fire, and flooding.​
  - Achievements: Enhanced public safety measures through real-time monitoring and rapid response capabilities.​

- Incheon Startup Park TRYOUT Smart-X Open Innovation Program (Incheon Port Authority)
  - Project Title: "Multi-modal AI Video Analysis Solution to Improve CCTV Monitoring Accuracy for Port Facility Security Management"​
  - Duration: 2024​
  - Role: AI Researcher​
  - Responsibilities: Deployed the MACS system in terminal environments to detect anomalies such as loitering and falling.​
  - Achievements: Achieved a 99.74% F1-score in detecting specified events, significantly reducing false positives and enhancing security operations.​

- 2024 Digital Innovation Company's Global Growth Voucher (R) Support Project
  - Project Title: "Real-time Emergency Detection Multi-modal AI CCTV Solution Inside and Outside Tunnels"​
  - Duration: 2024​
  - Role: Lead AI Architect​
  - Responsibilities: Developed AI surveillance systems optimized for embedded hardware to monitor tunnel environments for emergencies.​
  - Achievements: Achieved real-time processing speeds of 17.89 fps, ensuring timely detection and response to tunnel emergencies.​

- 2023 Data Voucher Support Project
  - Project Title: "Development of AI-based Real-time CCTV Video Analysis Solution"​
  - Duration: 2023​
  - Role: AI Researcher​
  - Responsibilities: Developed a text-video AI retrieval system to enhance the accuracy of domain-specific data analysis.​
  - Achievements: Achieved a 16.8 percentage point improvement in Recall@10 on domain-specific datasets, enhancing the system's retrieval performance.


### Enterprise AI Deployments (B2B)
- KTT-Coupang AI Surveillance PoC
  - Client: Coupang, in partnership with Korea Transportation Technology (KTT)
  - Duration: 2024-Present
  - Role: AI Researcher​
  - Responsibilities: Developed and fine-tuned a video anomaly detection system for logistics centers using text-video retrieval and Top-K similarity scoring. Targeted events included box opening, clothing change, and unauthorized access.
  - Achievements: Successfully deployed MACS to 16 real-time CCTV channels at Coupang Dongtan Logistics Center. Enabled detection of operational anomalies with improved interpretability, supporting future scalability for national logistics monitoring.

- Ad-lib Hotel AI Safety Monitoring
  - Client: Ad-lib Hotel (B2B site deployment)
  - Duration: 2024-Present
  - Role: AI Researcher​
  - Responsibilities: Installed and tested multi-modal AI solution tailored for hospitality environments, targeting guest - safety and behavioral anomaly detection.
  - Achievements: Improved response to unattended luggage and loitering scenarios. Demonstrated lightweight deployment feasibility for mid-sized facilities with minimal latency.
  
- LG U+ Industrial AI Safety System
  - Client: LG U+
  - Duration: 2024
  - Role: AI Researcher​
  - Responsibilities: Designed a vision-language model pipeline to detect abnormal behaviors in industrial environments such as fire, smoke, falling, and working at heights. Leveraged prompt-based event definitions and real-time RTSP integration.
  - Achievements: Verified F1-score improvement (96 vs. 38 baseline) across over 600 CCTV streams. Demonstrated seamless integration into LG U+ surveillance infrastructure with stability under high network throughput (10 Gbps backbone).
  
- HanaTour Smart Media AI Platform
  - Client: HanaTour
  - Duration: 2023
  - Role: AI Researcher​
  - Responsibilities: Built a short-form video editing support system by applying CLIP4Clip-based retrieval on 4TB of tour videos. Customized the ranking algorithm for travel-specific descriptors.
  - Achievements: Achieved Precision@5 of 74.67% and MRR of 69.83%. System significantly accelerated content curation, contributing to HanaTour’s digital transformation in travel media services.

## Solutions Development Highlights
### [MACS: Multi-modal AI CCTV Platform](https://pia.space/#MACS)
- Text-based retrieval + real-time visual event detection.
- Used CLIP/BLIP + spatio-temporal grounding.
- Deployed via Deepstream for scalable edge inference.

### [Waffle: Adaptive Deep Learning Framework](https://github.com/snuailab/waffle_hub)
- [GitHub](https://github.com/snuailab/waffle_hub)
- Designed training loop abstractions, auto-logging, checkpointing, scheduler integration.
-->

## Research Projects
- ROS Collision Avoidance (2022.01-06, ~5 months): real-time ship RL planner.
- Surgical RL (2021.08–2021.12, ~4 months): reward shaping for skill estimation.
- Driver Monitoring (2019.12–2021.7, ~6 months): CNN + HPE for in-vehicle posture/safety.
- USV Object Detection (2017.08-2018.07, ~11 months): Faster R-CNN.
- Genetic Path Planning (2017.01-07, ~6 months): Navigation route optimization.
<!--
- Driver Monitoring System(2021): CNN-based seatbelt & posture classification in vehicle footage.
- Surgical Skill Evaluation(2021-2022): RL reward-shaping system for virtual surgical tasks.
- ROS-based Collision Avoidance(2022): Real-time agent navigation in dynamic maritime settings.
- Stereo Vision Object Detection(2018): Faster R-CNN applied to USV maritime safety.
- Genetic Path Optimization(2017): Route planning for USV under environmental loads.
-->

## Patent
- System and Method for Monitoring at Least One Occupant Within a Vehicle Using a Plurality of Convolutional Neural Networks(2021)  
  - [US20210086715A1](https://patents.google.com/patent/US20210086715A1/en)  
  - Filed: Sep 2020, Published: Mar 2021

<!--
## Certifications

## **Teaching & Community**

### **ROKAF AI Training Program (2024)**
- Delivered 3-day curriculum on CV/NLP/fusion for military applications.
- Hands-on labs: CLIP-based retrieval, text classification, attention visualization.
-->

## Publications
- [**Kim, H.**, Kim, S.H., Jeon, M., Kim, J., Song, S. and Paik, K.J., "A study on path optimization method of an unmanned surface vehicle under environmental loads using genetic algorithm", Ocean Engineering, 2017](https://doi.org/10.1016/j.oceaneng.2017.07.040)
- [Jeon, M.R., **Kim, H.S.**, Kim, J.H., Kim, S.J., Song, S.S. and Kim, S.H., "A study on the dynamic positioning control algorithm using fuzzy gain scheduling PID control theory", Journal of the Society of Naval Architects of Korea, 2017](http://dx.doi.org/10.3744/SNAK.2017.54.2.102)
- [Song, S.S., Kim, S.H., **Kim, H.S.** and Jeon, M.R., "A study on the feedforward control algorithm for dynamic positioning system using ship motion prediction", Journal of the Korean Society of Marine Environment & Safety, 2016](https://doi.org/10.7837/kosomes.2016.22.1.129)

<!--
## Conference Publications
- **Heesu Kim**, Sehyun Chun, Stephen Baek. “Detecting Adequate Use of a Seat Belt for Driver Monitoring System”, Research Open House (Virtual), 2020, University of Iowa, USA
- **Heesu Kim**, Evangelos Bolourouris, Sanghyun Kim, “Object Detection Algorithm for Unmanned Surface Vehicle using Faster R-CNN”, WMTC, 2018, Shanghai, China
- **Heesu Kim**, Sanghyun Kim. “A Study on Heave and Pitch Motion Control of Fully-Submerged Hydrofoil using Deep Q-Network”, General Meeting and Annual Autumn Conference of the Society of Naval Architects of Korea, 2018, Changwon, Republic of Korea
- **Heesu Kim**, “A study on dynamic obstacle avoidance for Unmanned Surface Vehicle using Deep Q-Network”, PAAMES / AMEC, 2018,  BEXCO, Busan, Republic of Korea Joint Symposium, ICC JEJU, Jeju, Republic of Korea
- **Heesu Kim**, Evangelos Boulougouris. “A study on algorithm of vision-based real-time object recognition for USV using Faster R-CNN”, KAOSTS, 2018, Republic of Korea
- **Heesu Kim**, Evangelos Boulougouris. “Vision based collision risk for Unmanned Surface Vehicle using Faster Region based Convolutional Neural Network”, EKC, 2017, Stockholm, Sweden
- **Heesu Kim**, Sanghyun Kim. “A study on optimized path selection algorithm for unmanned surface vehicles under ocean environmental loads”, ANC, 2016, Yeosu Expo, Yeosu, Republic of Korea
- **Heesu Kim**, Sanghyun Kim. “A study on optimized path selection algorithm for unmanned surface vehicles under ocean environmental loads”, KAOSTS Joint Symposium, 2016, BEXCO, Busan, Republic of Korea
- **Heesu Kim**, Soonseok Song, Maro Jeon, Sanghyun Kim. “A study on the feedforward control algorithm for dynamic positioning system using ship motion prediction”,
ISFT, 2016, Harbin, China
-->

# Education
- Master of Engineering, Naval Architecture and Ocean Engineering, Inha University, Korea, 2019, _Thesis title: [Local path planning for autopilot of ship with quaternion ship domain(Korean)](https://inha.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma991009103061005086&context=L&vid=82KST_INH:INHA&lang=ko&search_scope=MyInst_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,%EA%B9%80%ED%9D%AC%EC%88%98&offset=0)_
- Master of Philosophy, Naval Architecture & Ocean and Marine Engineering, University of Strathclyde, United Kingdom, 2018, _Thesis title: [Stereo vision-based object detection algorithm for USV using faster R-CNN](https://stax.strath.ac.uk/concern/theses/4b29b6075)_
- Bachelor of Engineering, Naval Architecture and Ocean Engineering, Inha University, Korea

<!--
## Contact
hs.kim@pia.space
-->

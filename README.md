# 🚀 Victor's Portfolio

🚀Welcome to my data portfolio — a curated collection showcasing my journey, skills, and hands-on projects in the field of data science and analytics 🚀.

# 🙋About
<table>
  <tr>
    <td width="40%">
      <img src="https://github.com/Victortaiwo57/Data-Scientist/blob/main/Victor_.jpg" width="100%">
    </td>
    <td width="60%">
      <p>
        I am a results-driven IT Business Analyst and Data Scientist with over 4 years of experience delivering innovative, data-powered solutions that fuel business growth, streamline operations, and unlock strategic value.
        I specialize in translating complex business needs into actionable insights, with a proven track record in ERP optimization, stakeholder engagement, and end-to-end process improvement.
      </p>
      <p>
        Throughout my career, I’ve deployed impactful solutions including predictive models, automated data extraction systems, natural language processing (NLP) applications, and image-to-text tools to enhance accessibility and accelerate analysis.
        I also played a pivotal role in scaling an e-hailing company from ground zero to over ₦1 billion in annual revenue through actionable analytics and scalable reporting frameworks.
      </p>
      <p>
        I am always eager to contribute to forward-thinking teams that value innovation, collaboration, and measurable outcomes—whether through data-driven decision-making, digital transformation, or building solutions that truly make a difference.
      </p>
    </td>
  </tr>
</table>

## 📚 Table of Contents
- [SQL](#sql)
- [Power BI](#power-bi)
- [Python](#python)
- [Machine Learning AI](#machine-learning-ai)
- [Computer Vision & Road Safety Research](#computer-vision--road-safety-research)
- [Achievements](#achievements)

# SQL

| Project Link | Area of Analysis | Project Description | 
|---|---|---|
| 💡 [Week 1 SQL Challenges](https://github.com/Victortaiwo57/Case-Study-1---Danny-Dinner) | Data analysis, data cleaning, data transformation | This study reveals insights into customer visits, spending habits, and favorite items. These findings can help personalize experiences for loyal customers and support effective customer retention strategies. [#8WeekSQLChallenge](https://8weeksqlchallenge.com/case-study-1/). It showcases my ability to tackle various SQL challenges and demonstrates my proficiency in SQL query writing and problem-solving skills. | 

***

# Power BI

| Project Link | Project Description | 
|---|---|
| 🚗 [E-Hailing 2022 Report](https://github.com/Victortaiwo57/E-hailing-2022-Report/tree/main) | This repository contains four interactive dashboards designed to provide key insights into both driver operations and overall business performance. Built to guide strategic decision-making, the dashboards cover real-time KPIs, financial health, and performance benchmarking across the year (2023)| 
| 🚗 [Sale Analytics](https://github.com/Victortaiwo57/Product-Analytic/tree/main) | This project simulates a B2B sales pipeline for a multi-region company (Europe, North America, Asia-Pacific, Latin America) across seven industries. The goal was to design a report that three different audiences could use without modification (2026)| 
***

# Python

| Project Link | Area | Project Description | Libraries |    
|---|---|---|---|  
| 🛣️ [Reconciliation Platform](https://github.com/Victortaiwo57/reconciliation-app) | Automation | This app streamlines financial record-keeping in schools and training institutes by providing a secure, centralized platform to track enrollee payments and purchases. It features a clean, user-friendly interface with filters, confirmation dialogs, and export options—making it ideal for bursars, account officers, and admin staff seeking accurate and efficient reconciliation. | logging, shiny, datetime, pandas |   
| 🛣️ [Skin Care Product Web Scraping](https://github.com/Victortaiwo57/Skin-Care-Product-Web-Scraping) | Web Scraping | This project focuses on web scraping cosmetic product data from a static online store and analyzing similarities in their ingredient compositions. The goal is to discover how many products share ingredients and to group products based on overlapping formulations. | Beautifulsoap, requests, pandas, plotly|   

***

# Machine Learning AI

| Project Link | Area | Project Description | Libraries |    
|---|---|---|---|
| 🛣️ [Vehicle Mileage Extraction](https://github.com/Victortaiwo57/Image-text) | Image to Text | This application allows users to snap a photo of their vehicle's dashboard, and the system will automatically extract only the current vehicle mileage using OCR (Optical Character Recognition). It is designed to ensure accurate mileage logging for operational tracking and recordkeeping. | cv2, easyocr |   
| 🛣️ [Communication Test Grader]() | Word Processing | This project is a lightweight tool designed to automatically evaluate written communication tests. It scores user responses based on grammar, spelling, structure, clarity, tone, and overall communication effectiveness. | Pandas, NLP, Regex |  


***

# Computer Vision & Road Safety Research

Road traffic kills about 1.19 million people a year, and more than half are pedestrians, cyclists and motorcyclists ([WHO, 2023](https://www.who.int/publications/i/item/9789240086517)). These four projects use computer vision and vision foundation models to understand road users: what is on the road, what people will do next, where drivers look, and how realistic simulated road users are. Each one is a live Streamlit app with a README covering its importance, use cases, environment, method and limitations.

| Project Link | Area | Project Description | Libraries | Live App |
|---|---|---|---|---|
| 🚦 [RoadMind Lite](https://github.com/Victortaiwo57/roadmind-lite) | Object Detection | A baseline app that detects road users (pedestrians, cars, motorcycles, buses, traffic lights) in an uploaded road image with a pretrained YOLO11n model, and reports class counts, confidence scores, bounding boxes and a downloadable CSV. It is the first step towards understanding road-user behaviour, which the next three projects build on. | streamlit, ultralytics (YOLO), pandas | [Open app](https://roadvisionai.streamlit.app/) |
| 🚶 [Will This Pedestrian Cross?](https://github.com/Victortaiwo57/crossingintent) | Behaviour Prediction | Predicts from a car's dashcam whether a pedestrian will step into the road about one second before it happens, and tests whether frozen features from a vision foundation model (DINOv2) reveal intent cues, such as a head turn, that motion alone misses. The live demo trains a motion-only model and a motion + appearance model in the browser and shows how far ahead each one can predict. Planned experiment: JAAD dataset, plus a test on Lagos dashcam footage. | streamlit, scikit-learn, numpy, pandas, matplotlib (experiment: PyTorch, DINOv2) | [Open app](https://crossingintent.streamlit.app/) |
| 👁️ [Where Do Drivers Look?](https://github.com/Victortaiwo57/driver-attention-) | Driver Attention | Models where human drivers focus their attention, using a frozen DINOv2 encoder with a small decoder trained on real gaze maps, and measures which road users the model under-attends compared with people. The live demo is a playground for the four standard attention metrics (KLD, CC, SIM, NSS). It shows why a "look straight ahead" baseline is hard to beat, and how averaged scores can hide a missed pedestrian. Planned experiment: BDD-A gaze dataset. | streamlit, numpy, pandas, matplotlib, pillow (experiment: PyTorch, DINOv2, YOLO) | [Open app](https://driver-attention.streamlit.app/) |
| 🧪 [How Realistic Are Simulated Pedestrians?](https://github.com/Victortaiwo57/sim2real-road-users) | Simulation Realism | A measurable test of the sim-to-real gap: a classifier tries to tell simulated pedestrians (CARLA) from real ones (inD), with a real-vs-real control and held-out evaluation. The benchmark runs live in the app, with sliders to make simulated walkers more human-like and an upload option for your own trajectory data. It shows that much of an apparent gap can come from tracker noise and map layout rather than behaviour. | streamlit, scikit-learn, scipy, numpy, pandas, matplotlib | [Open app](https://sim2real-road-users.streamlit.app/) |

***

# Achievements

## 📚 Key Achievements as a Data Analyst/Data Scientist – LagosRide 

The image highlights key achievements as a data-driven professional, showcasing groundbreaking milestones achieved within just two and a half years.

<knb><img width="535" src="https://github.com/Victortaiwo57/Data-Scientist/blob/main/ZENO%20ach.jpg"></knb>



***

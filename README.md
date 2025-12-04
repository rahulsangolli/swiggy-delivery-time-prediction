<p align="center">
  <img src="https://raw.githubusercontent.com/rahulsangolli/swiggy-order-delivery-time-prediction/refs/heads/main/assets/afdae3cd-0a04-4d07-9d64-de3b92b5633d.png"
       alt="Banner" width="100%" style="max-height:240px; object-fit:cover; display:block; margin:0 auto;">
</p>

<div align="center">

<h1 style="font-size:42px; font-weight:800; margin-bottom:10px;">🛵 Swiggy Delivery Time Prediction</h1>

<p style="font-size:18px; max-width:850px; line-height:1.6;">
This project predicts how long it will take for a food order to reach the customer —  
just like Swiggy does in real life.  
Instead of manually estimating delivery time based on distance, traffic, or weather,  
this system looks at all important factors and instantly gives you a reliable prediction.
</p>

</div>

<hr/>

<h2 align="center" style="font-size:28px; font-weight:700;">📌 Overview</h2>

<p style="font-size:16px; line-height:1.65;">
The goal of the project is straightforward:  
<b>Use real delivery data → clean it → train a model → predict delivery time for new orders.</b>
<br/><br/>
The system is built with a complete end-to-end ML lifecycle in mind, involving:
</p>

<ul style="font-size:16px; line-height:1.7;">
  <li>Data Cleaning & Preprocessing</li>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Feature Engineering</li>
  <li>Model Selection & Hyperparameter Tuning</li>
  <li>MLflow Model Tracking</li>
  <li>FastAPI-based Deployment</li>
  <li>Dockerization</li>
</ul>

<p style="font-size:16px; line-height:1.7;">
The model considers real-world conditions such as distance, multiple delivery locations, rider performance, weather, and peak-hour traffic to estimate the delivery time accurately.
</p>

<hr/>

<h2 align="center" style="font-size:28px; font-weight:700;">🧠 Tech Stack</h2>

<ul style="font-size:16px; line-height:1.8%;">
<li><b>Language:</b> Python</li>
<li><b>ML Libraries:</b> Scikit-Learn, XGBoost, LightGBM</li>
<li><b>Data Processing:</b> Pandas, NumPy</li>
<li><b>Experiment Tracking:</b> MLflow</li>
<li><b>Pipeline Management:</b> DVC</li>
<li><b>Backend:</b> FastAPI</li>
<li><b>Deployment:</b> Docker</li>
</ul>

<hr/>

<h2 align="center" style="font-size:28px; font-weight:700;">⭐ Key Features</h2>

<ul style="font-size:16px; line-height:1.8%;">
<li><b>Real Delivery Data</b> — Includes distance, location, weather, and rider stats.</li>
<li><b>MLflow Integration</b> — Tracks all trained models and experiments.</li>
<li><b>FastAPI Endpoint</b> — Easily make predictions using a REST API.</li>
<li><b>DVC Pipelines</b> — Automates data and model workflow.</li>
<li><b>Docker Support</b> — Ensures consistent deployment anywhere.</li>
<li><b>Clean Modular Code</b> — Exactly how production-grade ML systems are structured.</li>
</ul>

<hr/>

<h2 align="center" style="font-size:28px; font-weight:700;">🧩 How the System Works…</h2>

<p style="font-size:16px; line-height:1.75;">
Let me walk you through how the entire system works in the simplest possible way.
<br/><br/>
Once the project is set up, we run the FastAPI backend using the terminal.  
Below is a screenshot from my terminal when I was testing the API locally:
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/rahulsangolli/swiggy-order-delivery-time-prediction/refs/heads/main/assets/Screenshot%202025-12-04%20at%209.34.27%E2%80%AFPM.png"
       alt="Terminal Output" width="90%" style="border-radius:8px;">
</p>

<p style="font-size:16px; line-height:1.75%;">
Here’s what is happening in the above screenshot:
</p>

<ul style="font-size:16px; line-height:1.75; margin-left:20px;">
  <li>The server starts using <b>Uvicorn</b>, which runs our FastAPI app.</li>
  <li>MLflow initializes and connects to the repository where all models are stored.</li>
  <li>The model and the preprocessing pipeline get loaded into memory.</li>
  <li>The API is now ready, listening for prediction requests.</li>
</ul>

<p style="font-size:16px; line-height:1.75%;">
So whenever a user sends order details through the API (like distance, time of day, weather, etc.),  
the backend instantly predicts the estimated delivery time.  
<br/><br/>
This gives you a real production-like experience of how Swiggy internally processes such requests.
</p>

<hr/>

<h2 align="center" style="font-size:28px; font-weight:700;">📈 Results</h2>

<ul style="font-size:16px; line-height:1.8%;">
<li>Accurately predicts delivery time across multiple conditions.</li>
<li>Successfully tracks all models using MLflow.</li>
<li>Provides a clean API for real-time predictions.</li>
<li>Imitates real-world food delivery systems effectively.</li>
</ul>

<hr/>

<div align="center">

<h2 style="font-size:32px; font-weight:800;">👨‍💻 Author</h2>

<strong style="font-size:24px;">Rahul Sangolli</strong><br>
<em style="font-size:16px;">Data Science & Machine Learning Practitioner</em>

<p style="font-size:16px;">
<a><b>🌐 LinkedIn</b></a> &nbsp;|&nbsp;
<a href="mailto:your-email"><b>✉️ Email</b></a>
</p>

</div>

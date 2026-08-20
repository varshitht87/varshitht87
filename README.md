<h1 align="center">hey, I'm Varshith 👋</h1>

<p align="center">
  <b>MSc Artificial Intelligence @ Dublin Business School</b><br>
  deep learning · reinforcement learning · NLP · cloud<br>
  <sub>Dublin, Ireland</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sai-krishna-varshith"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:varshitht87@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Dublin,%20Ireland-169B62?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/open%20to-graduate%20roles-blueviolet?style=for-the-badge" alt="Open to work">
</p>

---

## what I'm into

CS grad from VIT Chennai, now doing an MSc in AI at Dublin Business School and mostly living inside training loops.

Lately that's meant teaching five different RL agents to run a tram network, clustering live financial news into topics that actually mean something, and racing four CNN backbones against each other to see which one can tell Tesla models apart. Before Dublin it was protein function prediction, waste classification, and a voice-controlled airline booking system that was way harder to pull off than I expected.

The thing I care about isn't the model, it's whether the result holds up when you run it again. Fixed seeds, isolated runs, a metric that justifies the choice. When I'm not doing that I'm probably over-engineering something on AWS or reading too much about how transformers work.

---

## the stack

**languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**ml / dl**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![OpenAI Gym](https://img.shields.io/badge/OpenAI%20Gym-0081A5?style=flat-square&logo=openaigym&logoColor=white)

**what I use it for**

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-5A189A?style=flat-square)
![CNNs](https://img.shields.io/badge/CNNs-5A189A?style=flat-square)
![Reinforcement%20Learning](https://img.shields.io/badge/Reinforcement%20Learning-5A189A?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-5A189A?style=flat-square)
![Topic Modelling](https://img.shields.io/badge/Topic%20Modelling-5A189A?style=flat-square)
![Time Series](https://img.shields.io/badge/Time%20Series-5A189A?style=flat-square)
![Transfer Learning](https://img.shields.io/badge/Transfer%20Learning-5A189A?style=flat-square)

**cloud & tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## stuff I've built

### 🚊 Intelligent Tram Dispatcher
Five RL controllers — fixed-time baseline, Q-Learning, Monte Carlo, DDPG, TD3 — fighting over a five-station tram network in a custom Gym environment. Multi-term reward balancing throughput, cost and passenger wait time, plus a real-time 3D dashboard so you can actually watch them make decisions.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Gym](https://img.shields.io/badge/-OpenAI%20Gym-0081A5?style=flat-square) ![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

### 📈 FinQuery — Financial News Topic Modelling
Streamlit app that pulls live stock headlines and clusters them into interpretable topics. TF-IDF into LDA, running fully local with no API key. The part I'd point at first is the model selection: a sweep over topic counts scored on perplexity, coherence and diversity, so the config was chosen on evidence instead of vibes.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![LDA](https://img.shields.io/badge/-LDA-5A189A?style=flat-square) ![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

### 🎮 Steam Player Count Forecasting
Four sequence architectures on the same splits — stacked LSTM, GRU, CNN-LSTM, and CNN+attention+LSTM — forecasting concurrent player counts. The GRU won, which is a nice reminder that extra capacity isn't free performance.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![LSTM](https://img.shields.io/badge/-LSTM%20%2F%20GRU-5A189A?style=flat-square) ![Time Series](https://img.shields.io/badge/-Time%20Series-5A189A?style=flat-square)

### 🚗 Tesla Model Prediction
Fine-grained image classification across four pre-trained CNN backbones, dataset and training schedule held constant so the backbone was the only variable. Harder than it sounds — Teslas share a design language, so the distinguishing features are small and local.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Transfer Learning](https://img.shields.io/badge/-Transfer%20Learning-5A189A?style=flat-square)

### 📺 YouTube Virality Prediction
End-to-end pipeline predicting whether a video goes viral. A GCP VM running scheduled fetch jobs against the YouTube Data API, writing into a hosted database, scaling to ~4,000 videos unattended. Stacking ensemble on top. Most of the difficulty was the plumbing, not the model.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![GCP](https://img.shields.io/badge/-Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![REST API](https://img.shields.io/badge/-REST%20API-6DB33F?style=flat-square) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

<details>
<summary><b>earlier work (VIT, 2024–2025)</b></summary>

<br>

**🧬 Protein Function Prediction** — deep learning pipeline predicting protein function from structural data. Turns out biology and neural nets get along pretty well. Applications in drug discovery and genomics.

**✈️ Airline Reservation System** — fully voice-controlled flight booking. You talk, it books. Built the whole speech-to-text and entity recognition pipeline from scratch, including the cases where the transcription is close but wrong.

**🗑️ Waste Classifier** — CNN + ANN with feature fusion, classifying waste from images. Tested on 200 images, works better than expected.

**👤 RealTime VR** — real-time face recognition that pulls up your data on detection. Basically a memory aid disguised as a computer vision project.

**🤖 Automated Delivery Robot** — robot that adjusts speed based on road conditions from a pre-trained dataset. Yes, it actually moves.

</details>

---

## certs

<p>
  <img src="https://img.shields.io/badge/AWS%20Certified-Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS CCP">
  <img src="https://img.shields.io/badge/Microsoft%20Certified-Azure%20Administrator%20(AZ--104)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="AZ-104">
</p>

Plus Python and C training from IIT Bombay's Spoken Tutorial project, back when I was starting out.

---

## the numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=varshitht87&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varshitht87&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=varshitht87&theme=tokyonight&hide_border=true" alt="Streak">
</p>

---

## right now

Finishing the MSc (Jan 2027) and looking for graduate roles in Dublin — data science, ML/AI engineering, or cloud. If you're hiring, or you just want to argue about whether attention was worth it on a dataset that small, get in touch.

<p align="center">
  <a href="mailto:varshitht87@gmail.com"><img src="https://img.shields.io/badge/varshitht87@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

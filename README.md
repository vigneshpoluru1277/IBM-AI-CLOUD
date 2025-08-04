# IBM-AI-CLOUD
# Multimodal AI Skin Condition Diagnosis using IBM watsonx.ai

This project demonstrates how to use multimodal large language models (LLMs) — **Pixtral 12B** and **LLaMA 11B Vision-Instruct** — on IBM watsonx.ai to analyze and diagnose skin conditions from images using natural language queries.

---

##  Project Overview

In this project, we:
- Use **two skin disease images** as input
- Ask the question: *“What kind of disease this person is having?”*
- Compare outputs from **Pixtral 12B** and **LLaMA 11B Vision-Instruct**
- Display model responses side-by-side
- Visualize the verbosity of responses using a bar chart

---

##  Input Images

- Acne Type IV  
- Acne Type I  
Images are retrieved from the University of New Mexico Dermatology Skin Atlas.

---

## Technologies Used

 Tool                   Purpose                                  
 IBM watsonx.ai ------- Hosting and running foundation models   
 Pixtral 12B  --------- Image-text model from Mistral AI         
 LLaMA Vision-Instruct ------ Meta's multimodal LLM             
 Jupyter Notebook ------ Experimentation and model testing     
 Python (PIL, matplotlib) ---- Visualization & encoding       
 HTML/CSS   -------------- Final output presentation (index.html)   

---

##  Setup Instructions
 Follow this only if you're running the notebook locally with IBM watsonx.

1. Create a free IBM Cloud account and project at [watsonx.ai](https://dataplatform.cloud.ibm.com).
2. Generate your watsonx Runtime API Key and Project ID.
3. Clone this repo:
   ```bash
   git clone https://github.com/your-username/ai-skin-diagnosis-watsonx.git
   cd ai-skin-diagnosis-watsonx

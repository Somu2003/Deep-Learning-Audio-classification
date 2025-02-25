### Steps for Running This Project  

1. **Clone the Repository & Setup**  
   - Clone this project and extract the files.  
   - Open a terminal in the extracted project folder.  

2. **Create a Virtual Environment**  
   - Run the following command to create a virtual environment:  
     ```bash
     python3 -m venv audio-venv
     ```
     (Here, `audio-venv` is the name of the virtual environment.)  

3. **Activate the Virtual Environment**  
   - Use the following command:  
     ```bash
     source audio-venv/bin/activate
     ```  

4. **Install Dependencies**  
   - Run the following command:  
     ```bash
     pip install -r requirements.txt
     ```  

5. **Start the Django Server**  
   - Execute the following command:  
     ```bash
     python3 manage.py runserver
     ```  

6. **Stopping the Server**  
   - Press `Ctrl+Shift+C` or `Ctrl+Alt+C` to stop the server.  

---

### Abstract  

Audio classification, also known as sound classification, is the process of analyzing and categorizing audio recordings. This technique has diverse applications in AI and data science. In this project, we explore deep learning-based audio classification using models such as Artificial Neural Network (ANN), 1D Convolutional Neural Network (CNN1D), and 2D Convolutional Neural Network (CNN2D).  

The dataset consists of 8,732 labeled sound excerpts (each 4 seconds long) of urban sounds categorized into ten classes: air conditioners, car horns, children playing, dog barking, drilling, engine idling, gunshots, jackhammers, sirens, and street music. Before model development, data preprocessing and feature extraction are performed. Each model is evaluated based on accuracy, training time, and prediction time.  

This project also focuses on model deployment, allowing users to upload audio files and receive predicted sound classifications. The implementation details of the deployment are discussed in later sections.  

---

### Introduction  

Sound classification is one of the key applications of deep learning in audio processing. It involves identifying and categorizing sounds based on predefined classes. This technique has practical applications such as:  
- Classifying music clips to determine genres  
- Identifying speakers from short audio recordings  
- Recognizing environmental sounds for smart devices  

This project compares multiple deep learning models (ANN, CNN1D, and CNN2D) and successfully deploys them using Django. Prior to deployment, data preprocessing and feature extraction are performed to improve model performance. The models are evaluated based on accuracy, training time, and prediction time. The results of this evaluation are discussed in detail.  

To make this project impactful, we designed it with the goal of helping deaf individuals recognize and interpret surrounding sounds. The deployed system allows users to upload `.wav` audio files, process them through trained deep learning models, and receive a classification output, enabling them to understand their environment.  

---

### Objective & Goal  

The main objective of this project is to develop a deep learning-based system that helps deaf individuals interpret their surroundings through sound classification. Many people are born with the ability to hear, but those who are hearing-impaired often struggle to connect with the world. Our goal is to bridge this gap by providing a tool that enables them to upload audio files and receive a detailed classification of the sounds detected.  

This project not only enhances their ability to recognize environmental sounds but also helps them interact with the world more effectively. By leveraging deep learning, we aim to develop an accessible and user-friendly application that benefits individuals with hearing impairments.  

---

### Problem Statement  

Deep learning has become a crucial technology in modern IT, particularly in fields like audio and image processing. Inspired by its potential, we decided to develop an audio classification system using deep learning models.  

Audio classification has numerous applications in AI and data science, including:  
- Chatbots  
- Automated voice translators  
- Virtual assistants  
- Music genre recognition  
- Text-to-speech applications  

Many deaf individuals face challenges in interacting with their surroundings due to their inability to hear. As software engineering students, we recognized this as an opportunity to create a meaningful solution. Our project aims to develop a web application where users can upload audio files and receive an analysis of the sounds in their environment using deep learning models.  

For this, we selected three commonly used models—ANN, CNN1D, and CNN2D—and performed preprocessing and feature extraction before training them. The models are compared based on accuracy, training time, and prediction time. At the end of the project, we identify the best-performing model.  

By successfully deploying this web application, we enable deaf individuals to gain awareness of their surroundings, fulfilling the project's main objective.

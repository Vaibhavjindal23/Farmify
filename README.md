# 🌾 Farmify – AI-Driven Crop Management System

**Farmify** is an intelligent, AI-powered crop management platform designed to revolutionize modern farming. It helps farmers and agriculture researchers make informed decisions by predicting the most suitable crop based on soil data and detecting crop diseases through deep learning. The project integrates powerful machine learning models with a clean, responsive web interface for maximum usability.

## 🔍 Key Features

- 🌱 **Crop Recommendation System**
  - Predicts the optimal crop to grow based on soil parameters (NPK values, pH, temperature, rainfall, etc.)
  - Multiple ML models used (Random Forest, XGBoost, SVM, etc.)
  - Best-performing model selected via evaluation metrics

- 🦠 **Crop Disease Detection**
  - Deep CNN-based disease classification for multiple crops (e.g., rice, potato, corn)
  - Upload leaf images and get instant disease diagnosis
  - High accuracy using image augmentation and transfer learning

- 🌐 **User-Friendly Web Interface**
  - Developed using **React.js** (frontend) and **Flask**/**Django** (backend)
  - Responsive UI with Tailwind CSS and smooth user interactions
  - Clear visualizations using Chart.js for prediction confidence and disease classes

- 📈 **Dashboard & Reports**
  - Shows prediction history, model accuracy, and confidence levels
  - Displays soil health insights and suggested actions

---

## 🚀 Tech Stack

| Area            | Tools / Frameworks                          |
|-----------------|---------------------------------------------|
| Frontend        | React.js, Tailwind CSS, Axios               |
| Backend         | Flask / Django REST Framework               |
| ML Models       | scikit-learn, XGBoost, TensorFlow, Keras    |
| Image Handling  | OpenCV, Pillow                              |
| Deployment      | Render / Heroku / GitHub Pages / Netlify    |
| Dataset Sources | Kaggle, PlantVillage, Indian Agri Databases |

---

## 📊 ML Model Performance (Crop Recommendation)

| Model           | Accuracy |
|----------------|----------|
| Random Forest  | 96.2%    |
| XGBoost        | 95.8%    |
| SVM            | 93.1%    |
| Logistic Reg.  | 89.5%    |

➡️ **Random Forest** selected for deployment.

---

## 🤖 CNN Architecture (Crop Disease Detection)

- Input: 224x224 RGB image
- 3 Convolutional + MaxPooling layers
- Dense layers with Dropout
- Softmax classifier for final output
- Achieved **97.3% validation accuracy**

💡 Future Improvements
📲 Mobile App Integration (React Native)

🌍 Multilingual Voice Assistance for Farmers

📡 Real-time Weather & Market Price APIs

🛰️ Integration with Satellite & Drone Data

**Vaibhav Jindal**  
B.Tech Computer Science Engineering  
Vellore Institute of Technology, Bhopal University  
📍 India  
📧 [jindalvaibhav63@gmail.com](mailto:jindalvaibhav63@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/vaibhav-jindal-b1b917250/) | [GitHub](https://github.com/Vaibhavjindal23)

🚀 Passionate about Artificial Intelligence, Machine Learning, Web Development, and building solutions that impact real lives.

⭐ Contributing

Contributions are welcome! Open issues, suggest features, or submit pull requests.
This project is built with ❤️ to help digitize Indian agriculture and empower farmers through technology.

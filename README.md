# 🌱 SoilSense AI – Smart Soil Health & Crop Advisor

SoilSense AI is a web application powered by machine learning that analyzes soil data (temperature, moisture, nutrients, etc.) and gives:

✅ Crop recommendation based on soil conditions

✅ Smart soil health feedback (e.g., low nitrogen, low moisture)

✅ A user-friendly web interface with popup results

📁 Project Structure  

```
soil_sense_web/
├── app.py                
├── soil_dataset.csv      
├── templates/
│   └── index.html  
```  
## 🔧 Features

🧠 ML-based crop prediction using Random Forest

🧪 Soil health diagnosis (based on NPK and moisture)

🌍 Clean, responsive UI with popup feedback

💡 Easy to run locally with Flask

🚀 Getting Started


1. Clone the Repository

```
git clone https://github.com/your-username/soilsense-ai.git
cd soilsense-ai
```
2. Install Dependencies

Make sure you have Python installed (3.8+ recommended):

` pip install flask pandas scikit-learn 

3. Run the App

 ` python app.py

Visit the app at: http://localhost:5000

## 📊 Dataset Format
The app uses a custom dataset soil_dataset.csv with the following columns:

Temperature, Humidity, Moisture, Soil Type, Crop Type, Nitrogen, Potassium, Phosphorous, Fertilizer Name

## 🧪 Example Row:

26.0,52.0,38.0,Sandy,Maize,37,0,0,Urea

## 🖼️ Screenshot
After submitting the form, a popup displays the crop and soil advice (low nutrients, overwatering, etc.).

## ✅ Future Improvements
Add fertilizer prediction

Improve mobile responsiveness

Support local languages (e.g., Hindi, Tamil)

Add login & user history

## 📄 License

MIT License © 2025 Balakumaran S
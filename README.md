# 🌍 Indian Plot Price API

Neural network predicts plot prices: **sqft × location_score → price**

## 🚀 Start in 10 seconds

```bash
pip install -r requirements.txt
python train_model.py
uvicorn main:app --reload


curl -X POST "http://localhost:8000/predict" -H "Content-Type: application/json" -d '{"sqft":1000,"location_score":9.0}'


## **🎯 RUN:**

```bash
# Save 4 files above
pip install -r requirements.txt
python train_model.py     # Creates model.pth
uvicorn main:app --reload # API live!

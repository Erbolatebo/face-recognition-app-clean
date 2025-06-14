# face-recognition-app
liveness detection
"# face-recognition-app-clean" 
# Face Recognition & Liveness Detection System

Проект: **Classification of falsifications in biometric authentication systems using machine learning methods **

**Автор:** Усер Ерболат    
**Год:** 2025  

---

## Описание

Данный проект реализует **систему биометрической аутентификации**, которая использует методы машинного обучения для:

- Распознавания лица
- Проверки "живости" пользователя (liveness detection)
- Обнаружения аксессуаров (маска, очки, головной убор)

---

## Используемые технологии

- Python
- TensorFlow / Keras
- OpenCV
- CNN, MobileNetV2
- Flask + HTML (шаблоны)
- Jupyter Notebooks

---

##  Архитектура

- `face_CNN_MobilenetV2.ipynb` — обучение модели живости (CNN) и аксессуаров (MobileNetV2)
- `app2.ipynb` — основной веб-интерфейс на Flask
- `save_live_accessory.ipynb` — сохранение данных и предсказания
- `grafic.ipynb` — визуализация результатов обучения
- `/templates/` — HTML-шаблоны для регистрации, входа и тестирования
- `/plots/` — графики обучения и архитектура модели

---

## Архитектура сбора данных
![image](https://github.com/user-attachments/assets/90f993cb-596e-48bc-b789-9e956754a909)

---

## Liveness dataset
![image](https://github.com/user-attachments/assets/1934a33a-1df6-4135-95c0-aa01fda8858e)
![image](https://github.com/user-attachments/assets/24988c29-a532-4d5f-9227-06ca80b8e7f9)

---

## Accessory dataset
![image](https://github.com/user-attachments/assets/6a7286ea-1473-49ce-aac0-0fdfb7eeca45)
![image](https://github.com/user-attachments/assets/46075b21-c549-4551-a3e6-c653b715e871)

---

## Установка

1. Установите зависимости:

```bash
pip install -r requirements.txt

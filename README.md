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
## Модель обучение
![image](https://github.com/user-attachments/assets/cad8a1dc-2e3d-4cea-8f8f-38a9e1152a5e)
![image](https://github.com/user-attachments/assets/c841ffd4-9771-4529-9231-8dbecf282c9a)
![image](https://github.com/user-attachments/assets/0326f6aa-2d5d-434e-89d3-a74d22e7c65c)
![image](https://github.com/user-attachments/assets/6f5102c3-5758-4c79-89b3-7b9068a73bcb)
![image](https://github.com/user-attachments/assets/8116420d-5bb3-4cc0-9f16-300a246596ed)

---

## Архитектуар распознание
![image](https://github.com/user-attachments/assets/c90f74e3-ad10-47cf-ba91-3434156687ee)

---

## Архитектура веб-сайта
![image](https://github.com/user-attachments/assets/7e7e904d-f9a2-47d9-b1bb-2c99e0c01ba4)

---

## Results
![image](https://github.com/user-attachments/assets/5caac052-db16-4e99-ab57-74fced7531f8)

---

## Установка

1. Установите зависимости:

```bash
pip install -r requirements.txt

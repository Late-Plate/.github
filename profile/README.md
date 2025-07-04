# 🍽️ Late Plate – AI-Powered Smart Cooking Assistant

**Late Plate** is an AI-driven mobile application designed to revolutionize the home cooking experience. It integrates state-of-the-art artificial intelligence technologies to deliver personalized recipe generation, smart meal recommendations, and ingredient recognition — all tailored to the user's preferences and pantry.

---

## 🔍 Overview

In today’s fast-paced lifestyle, meal planning and cooking can be overwhelming. Late Plate aims to simplify these daily challenges by offering a smart assistant that helps users:

- Generate new recipes from available ingredients.
- Recognize ingredients from images using computer vision.
- Get meal suggestions based on personal tastes.
- Track kitchen inventory and dynamically create grocery lists.
- Follow real-time guided cooking instructions.

---

## 🧠 Core Features

### 📝 Recipe Generation
- Generates novel, coherent recipes using fine-tuned **GPT-2** and **LLaMA 3.2** language models.
- Recipes are based on user-specified ingredients and dietary preferences.

### ⭐ Recommendation Engine
- Combines **collaborative filtering** and **content-based filtering**.
- Suggests meals tailored to user preferences, history, and behavior.

### 🍅 Ingredient Recognition
- Real-time ingredient identification using **YOLOv11**, trained on a custom dataset of 60+ food classes.
- Helps users identify unknown ingredients from camera images.

### 📱 Mobile App & Backend
- **Frontend:** Android app built with Kotlin and Jetpack libraries.
- **Backend:** Flask and Spring Boot microservices.
- **Cloud & Auth:** Firebase for real-time data storage and user authentication.

---

## 🏗️ System Architecture

Late Plate is modularly structured into four main layers:

1. **Presentation Layer**
   - User interface: recipe suggestions, ingredient scanning, inventory management, etc.
2. **Logic Layer**
   - Core modules: recipe generator, ingredient detector, recommender engine, inventory checker.
3. **Persistence Layer**
   - Manages access to recipes, ingredients, users, and ratings via DAOs.
4. **Database Layer**
   - Centralized database supporting full CRUD operations.

![System Diagram](https://github.com/user-attachments/assets/f33b96ac-548f-422b-b133-aabbd1dc4459)

---

## 🎯 Project Objectives

Late Plate was created as a graduation project to explore the practical application of AI in everyday life. The system blends:

- Natural Language Processing (NLP)
- Computer Vision
- Neural Networks
- LLMs (Large Language Models)
- Recommender Systems

Its mission is to **make cooking easier, more personalized, and enjoyable** for everyone.

![Objectives](https://github.com/user-attachments/assets/dc3074aa-dbba-4bac-8dee-5ec6ebf71402)

---

## 📁 Repositories

This organization contains multiple repositories for different modules of the system:

- [**Frontend Mobile App**](https://github.com/Late-Plate/Mobile-App)
- [**Recipe Generator Service**](https://github.com/Late-Plate/AI-Models/tree/recipe-generation)
- [**Ingredient Recognition Model**](https://github.com/Late-Plate/AI-Models/tree/ingredient-detection)
- [**Recommendation System**](http://github.com/Late-Plate/AI-Models/tree/recipe-recommender)
- [**Backend APIs**](https://github.com/Late-Plate/Backend)

---

## 📱 Mobile App Demo

https://github.com/user-attachments/assets/516059cd-2e5f-48d6-9f64-2991ca8210d7

---

## 👥 Team & Contribution

A team of undergraduate students developed this project as part of their graduation project. Contributions and detailed module-level documentation can be found in the respective repositories.

---

## 📜 License

This project is released under the MIT License unless stated otherwise in individual repos.

---

Thank you for exploring **Late Plate**! We hope it helps make your cooking smarter and more enjoyable.

# Livakoland Grace

**Организатор симптомов для продуктивных визитов к врачу**  
*Symptom Organizer for Productive Doctor Visits*  

Никогда не выходите от врача с мыслью «Я забыл упомянуть...»  
*Never leave a doctor's appointment thinking "I forgot to mention..."*

**Приватность • Работает офлайн • Научные исследования**  
*Privacy-First • Offline-Capable • Research-Oriented*

## 🌟 О проекте / Overview
**Русский**: Livakoland Grace — это AI-помощник, который помогает пациентам структурировать симптомы для чёткого обсуждения с врачами. Проект некоммерческий, вдохновлённый благодатью: ошибки покрываются, Ливаки становятся лучше.  
**English**: Livakoland Grace is an AI-powered assistant that helps patients organize symptoms for clear medical discussions. A non-commercial project inspired by grace: mistakes are forgiven, and Livaqs get better.

## 🎯 Проблема / The Problem
- **Русский**: Пациенты забывают симптомы, врачи теряются в разрозненных историях. Livakoland Grace выявляет паттерны и предлагает диагностические пути.  
- **English**: Patients forget symptoms, doctors struggle with fragmented stories. Livakoland Grace identifies patterns and suggests diagnostic pathways.

## ✨ Возможности / Key Features
- **Интеллектуальный диалог**: Чат-бот задаёт вопросы по симптомам (например, "Чувствуете ли усталость?"), основываясь на онтологии и портретах агентов (висмут, витамины).  
- **Вероятности**: Оценивает состояния (дефицит, норма) с помощью весов симптомов.  
- **Приватность**: Работает офлайн, данные отправляются в IPFS только с согласия.  
- **Некоммерческий**: Бесплатно навсегда, без рекламы, развитие через сообщество.

## 🚀 Начало работы / Getting Started
### Установка / Installation
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/livakoland/livakoland-grace.git
   cd livakoland-grace

Backend:
bashpip install -r requirements.txt
python src/backend/api.py

Frontend:
bashcd src/frontend
npm install
npm start

Откройте http://localhost:3000 и начните диалог с чат-ботом.

Пример диалога / Example
textLivakoland Grace: Чувствуете ли усталость? [Да/Нет]
Вы: Да
Livakoland Grace: Это чаще днём? [Да/Нет]
Вы: Да
Вероятности: {'дефицит висмута': 85%}
🔬 Научная ценность / Research Value

Анонимные датасеты: Пользователи могут делиться результатами анализов в IPFS для исследований.
Пример: {"symptoms": {"S0000.0.1": "да"}, "predictions": {"script": 0.8}}.
Для врачей: Доступ к данным для изучения корреляций (например, дефицит висмута и усталость).

🔒 Приватность / Privacy

Всё локально: обработка на устройстве, интернет опционален.
Прозрачность: перед отправкой данных в IPFS — предпросмотр и согласие.
Анонимность: никаких персональных данных.

💰 Некоммерческий / Non-Commercial

Бесплатно навсегда, без премиум-функций и рекламы.
Лицензия: AGPL-3 с условием "No monetization".
Сообщество: Присоединяйтесь в Discord (Livakoland Grace)!

🛠️ Техническая архитектура / Technical Architecture

Онтология: ontology_tree.json — структура симптомов с базовыми весами.
Портреты агентов: nutrients/bismuth.json — веса симптомов (≥ 0.01).
Backend: Flask (api.py, dialog.py) для диалога и предсказаний.
Frontend: React PWA (App.jsx) для чат-бота.
Майнинг: Flower для дообучения нейронки (TinyML) на датасетах IPFS.

🤝 Как внести вклад / Contributing

Используйте чат-бот и делитесь анонимными данными.
Разрабатывайте: добавляйте агентов (B12, микрофлора), улучшайте алгоритмы.
Пушьте PR, но без монетизации (проверяется guard_grace.py).
Присоединяйтесь в Discord: Livakoland Grace.

📄 Лицензия / License
AGPL-3.0 — проект остаётся бесплатным и открытым.
🙏 Благодарности / Acknowledgments
Пациентам, врачам и сообществу, которые делают Livakoland Grace живым по благодати.

Empowering Patients, Supporting Doctors, Advancing Medical Research

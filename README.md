# 🐶 Cats vs. Dogs Classifier (PyTorch)

Классификация изображений кошек и собак с использованием сверточной нейронной сети (CNN), реализованной на PyTorch.

## 📂 Описание

Модель обучена на данных из соревнования [Dogs vs. Cats Redux: Kernels Edition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition). Финальная проверка производилась на моих домашних животных 🐱🐕 — в реальных условиях.

## 🧠 Архитектура

- Простая CNN с 3 сверточными блоками.
- Активации `ReLU`, слои `MaxPooling`, финальная классификация через `Sigmoid`.
- Используется `BCELoss` и `Adam` оптимизатор.

## 🚀 Результаты

- Точность на валидации: **~81.7%**
- Быстрое сходимость за 10 эпох.
- Графики Accuracy и Loss отображаются в конце обучения.

## 🛠️ Используемые технологии

- PyTorch
- torchvision.transforms
- PIL
- sklearn
- matplotlib

## 📦 Установка

```bash
pip install -r requirements.txt

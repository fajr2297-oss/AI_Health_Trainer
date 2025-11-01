# AI Health Trainer (English + Arabic)

## About المشروع
This is a simple bilingual (English + Arabic) AI Health Trainer project that predicts breast cancer (benign/malignant) using a small neural network built with Keras.

هذا مشروع صغير بلُغتين (العربية والإنجليزية) يدرّب شبكة عصبية بسيطة للتنبؤ بسرطان الثدي (حميد / خبيث) باستخدام مكتبة Keras.

---

## Project Structure هيكل المشروع

- `src/` : Contains source code (Python scripts for data prep, model, training, prediction, CLI)
- `artifacts/` : Saved trained models and scalers
- `requirements.txt` : Python dependencies
- `README.md` : This file

---

## Quick Start كيفية التشغيل

1. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate   # On Windows use: .venv\Scripts\activate
2.	Install dependencies:
pip install -r requirements.txt
3.	Train the model:
python -m src.cli train --epochs 10 --batch-size 32
4.	Make predictions:
python -m src.cli predict --sample-size 5
Notes ملاحظات
	•	You can use your own CSV dataset by modifying data_prep.py.
	•	Model architecture is simple and can be tuned for better accuracy.
	•	يمكنك استخدام مجموعة بيانات CSV خاصة بك عن طريق تعديل data_prep.py.
	•	يمكن تحسين دقة النموذج عن طريق تعديل البنية والمعاملات.

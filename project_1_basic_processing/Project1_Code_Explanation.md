# 🧠 Project 1 – X-ray Image Loading & Display  
## 🇬🇧 English / 🇩🇿 العربية

---

## 📌 مقدمة Introduction

🇬🇧
This project is the first step in learning medical image processing using Python.
The goal is to:
- Load a medical X-ray image
- Display it using Matplotlib
- Handle grayscale images
- Build the foundation for more advanced computer vision projects

🇩🇿
هذا المشروع هو الخطوة الأولى لتعلم معالجة الصور الطبية باستخدام بايثون.  
الهدف منه هو:
- تحميل صورة X-ray طبية
- عرضها باستخدام Matplotlib
- التعامل مع الصور بتدرج الرمادي
- تجهيز الأساس لمشاريع Computer Vision المتقدمة

---

## 👇 الكود Code Example

🇬🇧 / 🇩🇿 شرح كل سطر Code Explanation:

`python
# OpenCV library for image processing
# مكتبة OpenCV لمعالجة الصور
import cv2

# Matplotlib library for displaying images
# مكتبة Matplotlib لعرض الصور
import matplotlib.pyplot as plt

# Load X-ray image in grayscale
# قراءة الصورة الطبية بصيغة رمادية
img = cv2.imread("xray.jpg", cv2.IMREAD_GRAYSCALE)

# Resize the image to 512x512
# تغيير حجم الصورة إلى 512x512
img_resized = cv2.resize(img, (512, 512))

# Create a display window of size 6x6 inches
# إنشاء نافذة عرض بحجم 6×6 إنش
plt.figure(figsize=(6,6))

# Add title to the image
# إضافة عنوان أعلى الصورة
plt.title("X-ray Image")

# Show the image using grayscale colormap
# عرض الصورة باستخدام تدرج الرمادي
plt.imshow(img_resized, cmap="gray")

# Hide axis for a cleaner display
# إخفاء الإحداثيات حول الصورة
plt.axis("off")

# Display the image
# عرض الصور
plt.show()

🎯 ماذا تعلمنا؟ / What we learned
🇬🇧
How to read medical images in Python
Display images using Matplotlib
Work with grayscale images
Resize images for consistent processing
Build a foundation for advanced computer vision projects
🇩🇿
كيفية قراءة الصور الطبية باستخدام بايثون
عرض الصور باستخدام Matplotlib
التعامل مع الصور الرمادية
تغيير حجم الصور لتسهيل المعالجة لاحقاً
تجهيز قاعدة للمشاريع المتقدمة في Computer Vision



🚀 المشروع القادم / Next Project
🇬🇧 Project 2: Image Enhancement – Noise Removal, Histogram, Filters
🇩🇿 المشروع القادم: تحسين الصور – إزالة الضوضاء، Histogram، الفلاتر





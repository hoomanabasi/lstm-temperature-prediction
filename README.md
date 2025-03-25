# lstm-temperature-prediction
# پیش‌بینی دما با LSTM / LSTM Temperature Prediction

## توضیحات / Description

این پروژه یک مدل شبکه عصبی بازگشتی (LSTM) رو برای پیش‌بینی دمای ساعتی با استفاده از دیتاست Jena Climate پیاده‌سازی می‌کنه. هدف این پروژه، پیش‌بینی دمای آینده بر اساس داده‌های گذشته با استفاده از یادگیری عمیق در TensorFlow است.

This project implements a Long Short-Term Memory (LSTM) neural network to predict hourly temperature using the Jena Climate dataset. The goal is to forecast future temperatures based on historical data using deep learning in TensorFlow.

---

## دیتاست / Dataset

- **نام:** Jena Climate Dataset  
- **منبع:** [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/jena_climate)  
- **توضیحات:** این دیتاست شامل داده‌های هواشناسی ساعتی از شهر ینا (آلمان) بین سال‌های 2009 تا 2016 است. ما از ستون دما (`T (degC)`) برای پیش‌بینی استفاده کردیم.

---

## پیش‌نیازها / Prerequisites

برای اجرای این پروژه، به ابزارهای زیر نیاز دارید:  
You need the following tools to run this project:

- Python 3.7 یا بالاتر / Python 3.7 or higher  
- Google Colab (اختیاری، برای اجرا در فضای ابری) / Google Colab (optional, for cloud execution)  

### نصب وابستگی‌ها / Install Dependencies

وابستگی‌ها رو با دستور زیر نصب کنید:  
Install the dependencies using the following command:

```bash
pip install -r requirements.txt

# Phishing_URL_Detection

This project implements a machine learning-based system to classify URLs into four categories: **Phishing**, **Malware**, **Defacement**, and **Benign**. It leverages advanced classification algorithms such as **Random Forest**, **LightGBM**, and **XGBoost** to detect malicious URLs with high accuracy.

---

## Project overview

The system performs:

- **Feature extraction** from raw URLs  
- **Model training and evaluation** using multiple classifiers  
- **Performance comparison** to identify the most accurate and robust model for real-world deployment

---

## Dataset Information

The dataset was compiled from multiple trusted sources:

- A **Kaggle dataset** with labeled phishing, malware, and benign URLs  
- A **phishing domain list** from a popular GitHub repository  
- **Malicious-only links** from the [abuse.ch](https://abuse.ch) threat intelligence feed  

---

## Model Accuracy

After testing, the following accuracies were achieved:

- **Random Forest**: 94.8%  
- **LightGBM**: 94.5%  
- **XGBoost**: 93.1%

---

## Future Enhancements

- Deploy as a web API or browser extension  
- Include real-time threat feeds  
- Add visualization dashboards for detection trends  

---

## Acknowledgments

This project was inspired and developed by extending the ideas from the following repository:

- [Malicious URL Detection using Machine Learning by wisdomml2020](https://github.com/wisdomml2020/Malicious_url_detection_using_MachineLearning)
- [Research on Malicious URL Detection using Machine Learning by MDPI](https://www.mdpi.com/1424-8220/23/18/7760)

I combined and improved upon the models and approach presented in the above project, incorporating additional datasets and conducting detailed model comparison to enhance accuracy and performance.

## Note

This project is for educational and research purposes only.

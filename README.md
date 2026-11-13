
# End-to-End Student Exam Performance Indicator

A machine learning web application that predicts a student's **Mathematics Score** from demographic and academic inputs, deployed on **AWS Elastic Beanstalk** with automated CI/CD via **AWS CodePipeline**.

## Live Demo
- **Live Web App:**
- [Click here to try the Student Exam Performance Predictor](http://studentsperformance-env.eba-ujaw58np.ap-southeast-2.elasticbeanstalk.com/predictdata)

## Tech Stack & Cloud Architecture
- **Machine Learning:** Python, Pandas, NumPy, Scikit-Learn (`LinearRegression` selected after comparing multiple regression models including CatBoost, XGBoost, Random Forest, and Gradient Boosting).
- **Web Framework:** Flask, HTML/CSS, Gunicorn.
- **Cloud & CI/CD:** GitHub connected to **AWS CodePipeline** for continuous deployment to **AWS Elastic Beanstalk** (Python 3.11 on Amazon Linux 2023).
- **Dependency Management:** Separated lightweight production runtime dependencies (`requirements.txt`) from training/EDA libraries (`requirements-dev.txt`).
-

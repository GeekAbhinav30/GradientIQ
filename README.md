# GradientIQ

GradientIQ is a Machine Learning project that evaluates factors such as study hours, tutoring, absences for a specific semester, parental support, extracurricular activities, and sports to deliver a comprehensive **SGPA prediction**. Beyond predictions, it offers visual insights and actionable feedback, empowering students to maximize their academic efforts. 

---

Key Features
Accurate SGPA Forecasting: Predicts semester grades with up to 95% precision to help students anticipate their academic performance.

Insightful Visualizations: Displays a pie chart summarizing input factors and a comparative graph showing actual study hours against the recommended benchmark of 15 hours per week for optimal results.

Customized Study Tips: Delivers actionable advice such as:

Aim for 12–15 hours of dedicated study time weekly, covering lectures, assignments, and personal preparation.

Improve attendance by organizing time and commitments more effectively.

Seek extra learning support or tutoring to enhance understanding in weaker subjects.

---

## 🛠️ Technologies & Libraries Used

- Flask==3.0.3  
- numpy==2.1.2  
- pandas==2.2.3  
- matplotlib==3.9.2  
- seaborn==0.13.2  
- scikit-learn==1.5.2  
- joblib==1.4.2  
- gunicorn==21.2.0

> **Note:** `gunicorn` was not installed by default. To install it, run:

```bash
pip install gunicorn==21.2.0

git clone https://github.com/GeekAbhinav30/GradientIQ.git
cd GradientIQ
pip install -r requirements.txt

python app.py


# Diabetes Prediction System

## Overview
The Diabetes Prediction System is a web-based application developed using Django and a machine learning model. The system predicts the likelihood of diabetes in individuals based on various health metrics. By combining data science with web development, this project provides an accessible tool for early diagnosis and proactive healthcare management.

## Features
- **User-Friendly Interface:** Easy-to-use web interface for data input and result display.
- **Real-Time Predictions:** Instant prediction of diabetes risk based on user inputs.
- **Machine Learning Model:** Logistic regression model trained on relevant health data.
- **Scalability:** Designed to handle multiple users simultaneously.
- **Responsive Design:** Accessible on various devices including desktops, tablets, and smartphones.

## Technologies Used
- **Backend:** Django, Python
- **Machine Learning:** Scikit-learn (Logistic Regression)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (or any other database you used)
- **Deployment:** Deployed on a server using [mention server or hosting service]

## Installation and Setup
To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-system.git
   cd diabetes-prediction-system
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the Application:**
   Open your web browser and navigate to `http://localhost:8000`.

## Usage
1. Open the web application in your browser.
2. Input your health metrics into the provided fields.
3. Click the "Predict" button to receive an instant prediction of your diabetes risk.

## Model Development
The logistic regression model was trained using a dataset containing various health metrics such as age, BMI, glucose levels, and blood pressure. The model was evaluated using accuracy, precision, recall, and AUC-ROC curve metrics.

## Testing
The system has been tested using a separate testing dataset to ensure the accuracy of predictions. Additionally, the web application has been tested for usability, responsiveness, and performance.

## Future Enhancements
- **Advanced Algorithms:** Incorporating more sophisticated machine learning models to improve prediction accuracy.
- **Expanded Dataset:** Including data from more diverse populations to enhance model generalization.
- **Additional Features:** Adding user authentication, data visualization, and personalized recommendations.

## Contributing
If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please reach out to:

- **Name:** Shreyas
- **Email:** [Your Email Address]
- **LinkedIn:** [Your LinkedIn Profile]

---

Thank you for checking out this project! Your feedback and contributions are appreciated.

# Diabetes-Prediction
Data Science project on Diabetes Prediction

# Introduction:
Diabetes is one such chronic ailment that grips millions of people all over the world and leads to serious health complications if the condition is not diagnosed and managed at an early stage in life. Machine learning, in this context, can predict the on-set of diabetes with the help of data-driven technologies, and timely interventions can be facilitated. The objective of this project is to develop a Diabetes Prediction System using Django by creating a logistic regression model and making it functional through a user-friendly web application. The system can take in measurements of various health metrics and return immediate predictions, thus enabling early diagnosis and prophylaxis.

Logistic regression is then used to identify a pattern between input variables, such as age, BMI, glucose levels, and other health indicators, assessing the probability of diabetes. A web-based application designed to reach a large part of users will provide a smooth and user-friendly interface where one can easily feed in their data and get results.

The project aims at achieving full integration of machine learning with web development, showing how these technologies can be harmonized to be impactful in healthcare. Besides, the system is developed in such a way as to provide scalability for possible future upgrades, such as adding more predictive models or health metrics.

This is a diabetes prediction system to be used in helping people live healthy lives and as proof of concept on how predictive analytics can do much more in healthcare. It is able to help in early diagnosis, allowing health providers and patients to become proactive in fighting diabetes and its associated complications by offering real-time, data-driven insights.

# ScreenShots (Output):

                                               HOME PAGE

![Screenshot 2024-08-11 220327](https://github.com/user-attachments/assets/0eb9d8ff-01d6-467a-b5d6-d4951807d86a)

                                            
                                            PREDICTION PAGE

![Screenshot 2024-08-11 220428](https://github.com/user-attachments/assets/bdd585e7-c8ef-42ed-bb32-a2abac23769f)


# Conclusion
The Diabetes Prediction System exemplifies the integration of machine learning with web development to create a practical tool for assessing diabetes risk. By offering an accessible and user-friendly interface, this system facilitates early diagnosis and encourages proactive health management. Future improvements could focus on enhancing model accuracy through the incorporation of more sophisticated algorithms and broadening the dataset to encompass more diverse populations. This project underscores the transformative potential of predictive analytics in healthcare, highlighting the pivotal role of technology in improving patient outcomes.

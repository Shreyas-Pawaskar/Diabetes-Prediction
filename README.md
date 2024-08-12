
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


# ScreenShots (Output):

                                               HOME PAGE

![Screenshot 2024-08-11 220327](https://github.com/user-attachments/assets/0eb9d8ff-01d6-467a-b5d6-d4951807d86a)

                                            
                                            PREDICTION PAGE

![Screenshot 2024-08-11 220428](https://github.com/user-attachments/assets/bdd585e7-c8ef-42ed-bb32-a2abac23769f)

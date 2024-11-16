# Enhancing Phishing Email Detection Using Machine Learning and Behavior Analytics

## Overview
A project leveraging machine learning and user behavior analytics to enhance phishing email detection.

## Features
-**Machine Learning Model**: Trained on diverse email datasets to identify phishing patterns.
- **Interactive Web Interface**: A user-friendly interface to input email content and get classification results.
- **Easy Setup**: Streamlined code and dependencies for quick deployment.

## Project Files
- **`app.ipynb`**: Jupyter Notebook containing the training process, data preprocessing, and evaluation metrics.
- **`index.html`**: HTML file for the web interface.
- **`model.pkl`**: Pre-trained machine learning model for phishing detection.
- **Dataset**: Email dataset used for training and testing the model (not included due to size restrictions; download instructions below).

## Setup Instructions
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/mrdobbs2010/phishing-detection.git
   cd phishing-detection
   
2. **Install Dependencies**
   pip install -r requirements.txt

3. **Download the Dataset**
Download the dataset [here](https://drive.google.com/file/d/17-aFJFbgY3tto2r_NzDB26rRPe5Y28xA/view?usp=drive_link).

4. **Run the Web Application**
Start the Flask Server to use the web interface:
python app.py

5. **Access the Web Interface**
Open your browser and navigate to http://127.0.0.1:5000/.

## **5. Usage Instructions**
1. Launch the web application.
2. Paste email body text into the input field.
3. Click "Analyze" to classify the email as **Phishing** or **Legitimate**.
4. Review the results displayed on the page.

## Key Results
-Achieved **95% accuracy** using SGD Classifier.
-Reduce false positive rate by integrating user behavior analytics.

## Technologies Used
- **Programming Languages**: Python, HTML
- **Frameworks**: Flask (for web app)
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn

## Limitations
- Dataset size may impact classification performance on larger-scale data.
- The model does not handle emails written in languages other than English effectively.

## Future Improvements
- Add support for real-time email stream analysis.
- Expand the dataset to include multilingual email samples.
- Implement additional behavioral analytics features.

## License
This project is licensed under the MIT License. See the [License](LICENSE) file for details.

## Acknowledgements
Special thanks to the authors of the dataset from Kaggle.com and the open-source libraries used in this project.

## How to Contribute
Contributions are welcome!  
1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m 'Add feature'`).  
4. Push to the branch (`git push origin feature-name`).  
5. Open a pull request.

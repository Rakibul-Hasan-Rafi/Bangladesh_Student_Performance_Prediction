
# Bangladesh Student Performance Prediction

This project aims to predict student performance based on various features using machine learning. The model is built using a Random Forest classifier, and the predictions are made using the `student_rf_pipeline.pkl` file. This project also includes a Gradio interface for user interaction.

## Project Structure

```
Bangladesh_student_performance_prediction/
│
├── .git/                          # Git version control information
├── .gradio/                       # Gradio interface folder
├── app.py                         # Main application script for running the model
├── bangladesh_student_performance.csv # Dataset containing student performance data
├── requirements.txt               # List of required Python packages
├── rf_train.py                    # Script to train the Random Forest model
├── student_rf_pipeline.pkl        # Pickled Random Forest model pipeline
└── venv/                          # Virtual environment for the project
```

## Requirements

1. Python 3.x
2. Install the dependencies using the following command:

   ```
   pip install -r requirements.txt
   ```

3. If you're using a virtual environment, activate it with:

   ```
   source venv/bin/activate   # For Linux/macOS
   venv\Scripts\activate      # For Windows
   ```

## Dataset

The dataset used in this project is `bangladesh_student_performance.csv`, which contains information about various student features. This data is used to train and evaluate the performance of the machine learning model.

## Running the Application

To run the application, use the following command:

```
python app.py
```

This will start a Gradio interface where you can input student data and get performance predictions.

## Model Training

To retrain the model, run the following command:

```
python rf_train.py
```

This script will train a Random Forest classifier using the dataset and save the trained model as `student_rf_pipeline.pkl`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

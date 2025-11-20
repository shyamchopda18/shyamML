Mobile User Behavior Classification
🧠 Project Overview
This machine learning project focuses on analyzing mobile device usage patterns to classify users into five distinct behavior categories—ranging from light to extreme usage. By leveraging key metrics such as app usage time, screen-on duration, battery drain, and data consumption, the model aims to uncover meaningful insights into user habits and engagement levels.
📊 Dataset Description
The dataset contains 700 samples, each representing a unique mobile user. It includes the following feature
	
🛠️ Technologies Used
•	Python 3.8+
•	pandas, NumPy
•	scikit-learn
•	matplotlib, seaborn
🚀 Getting Started
Installation
Clone the repository and install dependencies:
git clone https://github.com/yourusername/mobile-user-classification.git cd mobile-user-classification pip install -r requirements.txt 

Running the Project
python main.py 
This script loads the dataset, preprocesses the data, trains a classification model, and evaluates its performance.
📈 Model Evaluation
The model is assessed using standard classification metrics:
•	Accuracy
•	Precision, Recall, F1-Score
•	Confusion Matrix
🔍 Applications
•	Personalization for mobile apps
•	Telecom usage profiling
•	Battery and data optimization strategies
•	Behavioral segmentation for marketing
📌 Future Enhancements
•	Feature engineering and selection
•	Hyperparameter tuning
•	Model deployment via web interface
•	Integration with real-time data streams
Let me know if you'd like to add licensing, contributor info, or link it to a GitHub repo!

Key Features:
●	User ID: Unique identifier for each user.
●	Device Model: Model of the user's smartphone.
●	Operating System: The OS of the device (iOS or Android).
●	App Usage Time: Daily time spent on mobile applications, measured in minutes.
●	Screen On Time: Average hours per day the screen is active.
●	Battery Drain: Daily battery consumption in mAh.
●	Number of Apps Installed: Total apps available on the device.
●	Data Usage: Daily mobile data consumption in megabytes.
●	Age: Age of the user.
●	Gender: Gender of the user (Male or Female).
●	User Behavior Class: Classification of user behavior based on usage patterns (1 to 5).


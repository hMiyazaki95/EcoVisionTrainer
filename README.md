🌍 EcoVisionTrainer
EcoVisionTrainer is a machine learning project designed to train image processing models for classifying and sorting waste as part of an environmental sustainability initiative. Using TensorFlow, this project fine-tunes pre-trained models to detect and categorize garbage into different types, such as plastic, paper, metal, and more. The project leverages the TrashNet dataset to build high-accuracy models and saves the trained models in .h5 format for easy deployment.

🚀 Key Features
🔍 Image Processing: Utilizes image preprocessing techniques such as resizing and normalization to optimize inputs for model training.
🔄 Data Augmentation: Applies data augmentation to increase model robustness by performing transformations like rotation, flipping, and zooming on the images.
🧠 TensorFlow Model Training: Uses TensorFlow's pre-trained models like MobileNetV2 for transfer learning and fine-tuning for garbage classification tasks.
💾 Model Saving: Saves trained models in the .h5 format, ready for integration into other applications such as mobile or web-based waste sorting systems.
🔧 Future Deployment: The model is designed for easy deployment in production environments using .h5 models, or conversion to TensorFlow.js for browser-based applications.

🗂️ Dataset
This project utilizes the TrashNet Dataset, which includes labeled images of garbage in the following categories:
📄 Paper
🍶 Glass
📦 Cardboard
🧴 Plastic
🏗️ Metal
🗑️ Trash
You can download the dataset from the official TrashNet GitHub repository.

⚙️ Installation
To set up the project locally, follow these steps:
1. Clone the Repository:
git clone https://github.com/yourusername/EcoVisionTrainer.git
2. Create and Activate a Virtual Environment:
python3 -m venv env
source env/bin/activate
3. Install Dependencies:
Install the required Python libraries:
pip install tensorflow numpy pandas matplotlib scikit-learn
4. Download the Dataset:
Download the TrashNet dataset and organize the images into their respective folders (plastic, paper, metal, etc.).

🛠️ How to Use
1. Preprocess the Data:
Prepare the dataset using the provided ImageDataGenerator in the utils.py file.
2. Train the Model:
Run the training script to start training the model on the dataset:
python src/train.py
3. Save the Model:
Once trained, the model will be saved as garbage_sorting_model.h5 in the project directory for future use.

🤝 Contributing
We welcome contributions! Feel free to fork this repository and submit pull requests with any improvements or bug fixes.
For detailed contribution guidelines, refer to the CONTRIBUTING.md file.

📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

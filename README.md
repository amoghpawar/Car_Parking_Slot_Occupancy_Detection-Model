# 🚗 IoT-Based Smart Parking System

This project uses an Artificial Neural Network (ANN) to classify parking spaces as either vacant or occupied. The system processes images of parking areas to determine parking space availability and supports smart parking management through IoT-based monitoring.

## 📑 Table of Contents

- [📖 Description](#-description)
- [📸 Project Demo](#-project-demo)
- [🛠️ Technologies Used](#️-technologies-used)
- [⚙️ Installation](#️-installation)
- [🚀 How to Run](#-how-to-run)
- [👨‍💻 My Contribution](#-my-contribution)
- [🤝 Team Project and Credits](#-team-project-and-credits)
- [🤝 Contributions](#-contributions)
- [📝 Contact](#-contact)

## 📖 Description

Parking Space Classification is a machine learning project that leverages an Artificial Neural Network to identify whether parking spaces are vacant or occupied.

The system processes images of parking areas and determines the status of each parking space. The primary goal is to provide a reliable system for monitoring parking lots, which can be integrated into smart parking solutions.

The project also includes ESP32-based IoT integration to support parking status communication and monitoring.

## 📸 Project Demo

The following screenshot demonstrates the parking space occupancy detection system running on a parking lot image.

![Parking Space Occupancy Detection Demo](./Data/readme_photo.png)

- Red boxes indicate parking spaces classified as occupied.
- Green boxes indicate parking spaces classified as vacant.
- The displayed values represent the model's classification output.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Machine Learning:** Artificial Neural Network (ANN)
- **Framework:** TensorFlow
- **Image Processing:** Parking space selection and image labeling
- **IoT Hardware:** ESP32
- **Tools:** Jupyter Notebook, Anaconda, Visual Studio Code

## ⚙️ Installation

To set up this project on your local machine, follow these steps.

### Prerequisites

- Python
- Anaconda
- TensorFlow-GPU environment, as used in the original project
- Required project dependencies

### Steps

1. **Install Anaconda:** Configure the required Python environment.

2. **Clone the repository:**

   ```bash
   git clone https://github.com/amoghpawar/Car_Parking_Slot_Occupancy_Detection-Model.git
   cd Car_Parking_Slot_Occupancy_Detection-Model
   ```

3. **Activate the Conda environment:**

   ```bash
   conda activate py310
   ```

   Replace `py310` with the name of your Anaconda environment if different.

4. **Install the required dependencies:**

   ```bash
   pip install -r module.txt
   ```

   Make sure you are inside the project folder and the Conda environment is active.

   If you are using VS Code, select the appropriate Python environment before installing the dependencies.

5. **Follow the instructions in the How to Run section below.**

---

## 🚀 How to Run

### Step 1: Select Parking Spaces

Run the file `parking_space.py`.

- Check whether the parking spaces are already selected.
- Use LMB (Left Mouse Button) to select a parking space.
- Use RMB (Right Mouse Button) to deselect a parking space.
- Press `q` to quit and save the selected spaces.

### Step 2: Label the Dataset

Run the file `data_labelling.py`.

- Use `0` on the NumPad to label vacant spaces.
- Use `.` to label occupied spaces.
- Make sure NumLock is enabled when using the NumPad.
- The original project notes that 1000+ images may need to be labeled and sorted for training.

### Step 3: Train the ANN Model

Open `model.ipynb` in Jupyter Notebook.

- Run all cells in the notebook.
- The notebook processes the prepared dataset and trains the ANN model.
- Model training may take time depending on your system and dataset.

### Step 4: Run the Parking Detection System

Run the file `mainV2.py`.

The system processes parking lot images and displays the occupancy classification for the selected parking spaces.

---

## 👨‍💻 My Contribution

This was a collaborative 4-member team project. My contributions included:

- **Dataset Preparation:** Assisted in preparing and organizing parking lot image datasets for model development.
- **Image Labeling:** Contributed to labeling parking spaces as vacant or occupied for supervised learning.
- **ANN Model Training:** Participated in training and validating the Artificial Neural Network model.
- **Model Evaluation:** Assisted in testing the model and analyzing its classification performance.
- **IoT Integration:** Participated in ESP32-based integration for parking status communication and real-time monitoring.
- **Testing and Documentation:** Supported system testing, project documentation, and project demonstration.

*Keep only the contribution points that accurately describe the work you personally completed.*

## 🤝 Team Project and Credits

This project was developed collaboratively as a 4-member team.

This repository is my fork of the original team project, maintained to showcase my involvement and contributions. Credit is retained for the original project and its contributors.

### Original Repository

[Car Parking Slot Occupancy Detection Model](https://github.com/krsnna-05/Car_Parking_Slot_Occupancy_Detection-Model)

### Project Contributors

- [Krishna Gavali on GitHub](https://github.com/KrishnaGavali)
- [Sarthak Londhe on GitHub](https://github.com/sarthaklondhe)
- [Amogh Pawar on GitHub](https://github.com/amoghpawar)

## 🤝 Contributions

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes.
4. Commit your changes:

   ```bash
   git add .
   git commit -m "Describe your changes"
   ```

5. Push your changes:

   ```bash
   git push origin feature-name
   ```

6. Create a Pull Request.

## 📝 Contact

For questions or feedback, please reach out to the project contributors:

- [Krishna Gavali on GitHub](https://github.com/KrishnaGavali)
- [Sarthak Londhe on GitHub](https://github.com/sarthaklondhe)
- [Amogh Pawar on GitHub](https://github.com/amoghpawar)


Feel free to get in touch!

# 📊 Audience Data Scientist

This repository contains a Jupyter Notebook designed to data scientist working for a marketing agency. Client, an electric vehicle (EV) manufacturer, is launching a new car. They have a dataset of 10,000 potential customers, attached. Each potential customer is described by the following categories of features showing their potential customers’ beliefs about EVs, related psychographics and demographics:

Range – 1: have this belief about EVs; 0: do not have this belief

Charging – 1: have this belief about EVs; 0: do not have this belief

Cost – 1: have this belief about EVs; 0: do not have this belief

Incentives – 1: have this belief about EVs; 0: do not have this belief

Performance – 1: have this belief about EVs; 0: do not have this belief

Features – 1: have this belief about EVs; 0: do not have this belief

Practicality – 1: have this belief about EVs; 0: do not have this belief

Lifestyle – 1: have this belief about EVs; 0: do not have this belief

Psychographics - A likert scale between 1: definitely disagree and 5: definitely agree.

Age – age as a number

Salary - salary as a number

### Challenge:

The client believes that different segments of potential customers will respond best to different marketing messages. Task is to use machine learning techniques to segment these 10,000 individuals into 3-10 distinct, contiguous groups. 

## 📁 Repository Structure

├── notebook.ipynb # Main Jupyter Notebook

├── requirements.txt # Python dependencies

├── interview_task.csv # File with data

└── README.md # Project instructions and description


## 🚀 Getting Started

This project was developed using:

- **Python 3.10**
- **pip 23.2.1**

To run the notebook on your local machine, follow these steps.

### 1. Clone the Repository
```bash
git clone https://github.com/martynakurbiel52/DS.git
cd DS

### 2. Create a Virtual Environment (Optional but Recommended)
python3.10 -m venv venv
source venv/bin/activate      
venv\Scripts\activate

### 3. Upgrade pip (if needed)
python -m pip install --upgrade pip==23.2.1

### 4. Install Required Packages
pip install -r requirements.txt

### 5. Run jupyter kernel and notebook
ipython kernel install --user --name=venv
jupyter notebook

✅ How to Use
🔁 Important: Run the notebook cell by cell (from top to bottom) to ensure correct execution and proper variable state.

Open the notebook in Jupyter.
Start from the first cell.
Run each cell in order using Shift + Enter.
Check outputs as you go.

If Jupyter shows the wrong kernel, go to Kernel > Change Kernel and select the environment with Python 3.10.

📬 Contact
For any questions, please open an issue or contact me via email martynakurbiel52@gmail.com

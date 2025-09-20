#  Binary Classification with PyTorch

This project is a **binary image classification** task where the goal is to distinguish between **antelope images** and **blank (empty) images**. The implementation uses **PyTorch** and **Python**, with the dataset stored in a local directory structure.


---

##  Project Structure

The dataset is organized as follows:
```
Binary-classification/
│── Notebooks/                     
│   ├── project_file.ipynb          # Main notebook with model training & evaluation
│           
│
│── data_binary/                    
│   └── data/
│       ├── antelope/               
│       ├── blanks/                 
│
│── .gitattributes                  
│── .gitignore                      
│── LICENSE
├── requirements.txt                      
└── README.md                       

```
##  Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<kanyi-Gabriel>/Binary-classification.git
   cd Binary-classification
   
2. Create a virtual environment
    ```bash
    python3 -m venv environment_name

    # activate environment
    source environment_name/bin/activate   # On Linux/Mac
    environment_name\Scripts\activate      # On Windows
    
    # Install dependencies
    pip install -r requirements.txt
  
    
    # Using conda to create environment
    conda create -- name environment_name
    conda activate environment_name
    
    pip install -r requirements.txt
    
3. To add the environment to jupyter notebook
    ```bash
    conda install -c anaconda ipykernel
    python -m ipykernel install --user--name = environment_name

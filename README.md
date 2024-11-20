# EDA Project

Onur EDA project
Client: Amy Williams (Seller) who is A Mafiosi, sells several central houses(top10%) over time, needs average outskirt houses over time to hide from the FBI…


## Requirements

altair==5.0.1
jupyterlab==4.0.1
ipywidgets==8.0.6
jupyterlab-dash==0.1.0a3
seaborn==0.12.2
python-dotenv==1.0.0
psycopg2-binary==2.9.7
SQLAlchemy==2.0.15
missingno==0.5.2
numpy==1.26.4
pandas
plotly

## Files

EDA Project file : 'EDA.ipynb'
PDF version of project file: 'EDA Project.pdf'
Folium Price Distr. High : folium_price_distribution_high_value_non_clustered.html
Plotly Price graph : folium_price_distribution_high_value_non_clustered.html



## Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
 

 **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```
